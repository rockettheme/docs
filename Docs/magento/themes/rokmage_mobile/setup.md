---
title: RokMage Mobile: Setup Guide
description: Your Guide to Using the RokMage Mobile Theme for Magento
tags: [Theme, RokMage, Requirements, Setup, Demo, Tutorial]
breadcrumb: /magento:Magento/!themes:Themes/rokmage_mobile:RokMage Mobile

---

Introduction
-----

RokMage Mobile is an excellent theme to use in conjunction with a primary theme to create a more fluid experience for users, regardless of the platform they choose to visit your site through. If you are using a RocketTheme theme as your primary theme for desktop users, the setup process works a little differently than it would if you are using it as a secondary theme to a third-party product.

Below, we've detailed setup instructions that enable you to set RokMage Mobile up to work with another RocketTheme product, as well as in a setting where your primary theme is provided by a third party.

How to Set up RokMage Mobile with a RocketTheme Template
-----

In order to direct your mobile visitors to your mobile theme, you need to make use of Magento's design exceptions. Here is a quick set of instructions for setting this up.

* Download and unzip the theme package.
* Upload the app, media, and skin folders to your Magento root. (Be sure to **merge** and not overwrite the files.)
* Navigate to **System -> Configuration -> Design** and select your store view from the **Current Configuration Scope**.
* Under the **Package** heading, click **Add Exception**.
* In the **Matched Expression** input, add the following: 

~~~
iPhone|iPod|BlackBerry|Palm|Googlebot-Mobile|Mobile|mobile|mobi|Windows Mobile|Safari Mobile|Android|Opera Mini
~~~

* In the **Value** input field, add `rokmagemobile`.
* Under the **Themes** heading, click **Add Exception** on each input.
* In the **Matched Expression** input, add the following:

~~~
iPhone|iPod|BlackBerry|Palm|Googlebot-Mobile|Mobile|mobile|mobi|Windows Mobile|Safari Mobile|Android|Opera Mini
~~~

* Enter `default` in each **Value** field in the **Themes** section (pictured below).

![][setup1]

Now, you can go to the RokMage Mobile configuration page (under the **RT RokMage Modules** tab on the left) and edit your settings. 

By default, the homepage slider will be enabled, and will show three demo slides. Also, the logo and touch icon are set to use the demo versions. Simply uploading your own images in the config will override these demo images with your own.

>> This mobile theme uses its own navigation block on the homepage. This is now part of the **MageMenus** extension, so you will need to download the latest version here and replace the following file with the new one from the downloaded zip, located here: **app/code/community/Rockettheme/MageMenus/Block/Navigation.php**.

How to Use the "Theme Switcher"
-----

If you want to add a button for switching to the desktop version, there's an option in the settings to Include '**View Desktop Site**' link. Set that to "Yes". This will add a button in the footer. Once viewing the desktop site, you now need a way to return to the mobile view. To add this to your theme, open both **app/design/frontend/base/default/layout/local2columns.xml** and **app/design/frontend/base/default/layout/local3columns.xml** and add immediately after the initial <default> tag the following:

~~~
<!-- START - Add Mobile Check -->
<reference name="before_body_end">
<block type="core/template" name="mobile.check">
<action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
<template>rokmagemobile/mobilecheck.phtml</template>
</action>
</block>
</reference>
<!-- END - Add Mobile Check -->
~~~

This will be added to the RokMage Layout extension in the next update.

How to Set Up RokMage Mobile with Third Party Themes
-----

If you wish to use our mobile theme on a store that's using a third party theme, and hence none of our extensions, you will need to make two adjustments.

First, open **app/design/frontend/rokmagemobile/default/layout/local.xml** and replace contents with the following and save (copy manually, selecting from first < to last >, as sometimes the auto copy messes things up):

~~~
<?xml version="1.0" encoding="UTF-8"?>
<layout version="0.1.0">
 
    <default>
        <reference name="head">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-modalheader/rokmage-head.phtml</template>
            </action>
            <action method="addItem" ifconfig="rokmage_mobile/general/enable"><type>skin_css</type><name>css/rokmagemobile.css</name></action>
            <action method="addItem" ifconfig="rokmage_mobile/general/enable"><type>skin_js</type><script>js/jquery.cookie.js</script></action>
        </reference>
        <reference name="header">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-modalheader/rokmage-modal-header.phtml</template>
            </action>
        </reference>
        <block type="checkout/cart_sidebar" name="rokmage_header_cart" template="rokmagemodules/rokmage-modalheader/rokmage-header-cart.phtml" >
            <action method="addItemRender"><type>simple</type><block>checkout/cart_item_renderer</block><template>rokmagemodules/rokmage-modalheader/headercart-item-renderer.phtml</template></action>
            <action method="addItemRender"><type>grouped</type><block>checkout/cart_item_renderer_grouped</block><template>rokmagemodules/rokmage-modalheader/headercart-item-renderer.phtml</template></action>
            <action method="addItemRender"><type>configurable</type><block>checkout/cart_item_renderer_configurable</block><template>rokmagemodules/rokmage-modalheader/headercart-item-renderer.phtml</template></action>
            <action method="addItemRender"><type>bundle</type><block>bundle/checkout_cart_item_renderer</block><template>rokmagemodules/rokmage-modalheader/headercart-item-renderer.phtml</template></action>
        </block>
        <reference name="top.search">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-modalheader/rokmage-form-mini.phtml</template>
            </action>
        </reference>
        <reference name="account.links">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-modalheader/mobile-links.phtml</template>
            </action>
        </reference>
        <reference name="top.links">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-modalheader/mobile-links.phtml</template>
            </action>
        </reference>
        <reference name="top.menu">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-magemenus/rokmage-mobilemenu.phtml</template>
            </action>
        </reference>
        <reference name="footer">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                    <template>rokmagemodules/rokmage-footerblock/rokmage-footer.phtml</template>
            </action>
            <block type="page/template_links" name="footer_links" as="footer_links">
                <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                    <template>rokmagemodules/rokmage-footerblock/rokmage-footerblock.phtml</template>
                </action>
            </block>
        </reference>
        <remove name="cms_footer_links"/>
        <reference name="footer_links">
            <action method="addLink" translate="label title" ifconfig="rokmage_mobile/footer_settings/sitemap_link"><label>Site Map</label><url helper="catalog/map/getCategoryUrl" /><title>Site Map</title></action>
            <action method="addLink" translate="label title" ifconfig="rokmage_mobile/footer_settings/searchterms_link"><label>Search Terms</label><url helper="catalogsearch/getSearchTermUrl" /><title>Search Terms</title></action>
            <action method="addLink" translate="label title" ifconfig="rokmage_mobile/footer_settings/advancedsearch_link"><label>Advanced Search</label><url helper="catalogsearch/getAdvancedSearchUrl" /><title>Advanced Search</title></action>
            <action method="addLink" translate="label title" ifconfig="rokmage_mobile/footer_settings/contact_link"><label>Contact Us</label><url>contacts</url><title>Contact Us</title><prepare>true</prepare></action>
        </reference>
    </default>
 
        <catalog_category_default>
        <reference name="product_list">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-categoryview.phtml</template>
            </action>
        </reference>
        <reference name="category.products">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-mobileview.phtml</template>
            </action>
        </reference>
        <reference name="product_list_toolbar">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-toolbar.phtml</template>
            </action>
            <action method="addPagerLimit" ifconfig="rokmage_mobile/general/enable"><mode>grid</mode><limit>10</limit></action>
            <action method="addPagerLimit" ifconfig="rokmage_mobile/general/enable"><mode>grid</mode><limit>50</limit></action>
            <action method="addPagerLimit" ifconfig="rokmage_mobile/general/enable" translate="label"><mode>grid</mode><limit>all</limit><label>All</label></action>
        </reference>
        <reference name="product_list_toolbar_pager">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-pager.phtml</template>
            </action>
        </reference>
    </catalog_category_default>
 
<!--
Category layered navigation layout
-->
 
    <catalog_category_layered>
        <reference name="product_list">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-categoryview.phtml</template>
            </action>
        </reference>
        <reference name="category.products">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-mobileview.phtml</template>
            </action>
        </reference>
        <reference name="product_list_toolbar">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-toolbar.phtml</template>
            </action>
            <action method="addPagerLimit" ifconfig="rokmage_mobile/general/enable"><mode>grid</mode><limit>10</limit></action>
            <action method="addPagerLimit" ifconfig="rokmage_mobile/general/enable"><mode>grid</mode><limit>50</limit></action>
            <action method="addPagerLimit" ifconfig="rokmage_mobile/general/enable" translate="label"><mode>grid</mode><limit>all</limit><label>All</label></action>
        </reference>
        <reference name="product_list_toolbar_pager">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-pager.phtml</template>
            </action>
        </reference>
    </catalog_category_layered>
 
    <tag_product_list>
        <reference name="search_result_list">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-categoryview.phtml</template>
            </action>
        </reference>
        <reference name="category.products">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-mobileview.phtml</template>
            </action>
        </reference>
        <reference name="product_list_toolbar">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-toolbar.phtml</template>
            </action>
        </reference>
        <reference name="product_list_toolbar_pager">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-pager.phtml</template>
            </action>
        </reference>
    </tag_product_list>
 
<!--
Set the category view template to show search results
-->
 
    <catalogsearch_result_index translate="label">
        <reference name="search_result_list">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-categoryview.phtml</template>
            </action>
        </reference>
        <reference name="category.products">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-mobileview.phtml</template>
            </action>
        </reference>
        <reference name="product_list_toolbar">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-toolbar.phtml</template>
            </action>
        </reference>
        <reference name="product_list_toolbar_pager">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-pager.phtml</template>
            </action>
        </reference>
    </catalogsearch_result_index>
 
    <catalogsearch_advanced_result translate="label">
        <reference name="search_result_list">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-categoryview.phtml</template>
            </action>
        </reference>
        <reference name="category.products">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-mobileview.phtml</template>
            </action>
        </reference>
        <reference name="product_list_toolbar">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-toolbar.phtml</template>
            </action>
        </reference>
        <reference name="product_list_toolbar_pager">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-categoryview/rokmage-pager.phtml</template>
            </action>
        </reference>
    </catalogsearch_advanced_result>
 
    <catalog_product_view>
        <reference name="head">
            <action method="addItem" ifconfig="rokmage_mobile/general/enable"><type>skin_js</type><script>js/klass.min.js</script></action>
            <action method="addItem" ifconfig="rokmage_mobile/general/enable"><type>skin_js</type><script>js/code.photoswipe.jquery-3.0.4.min.js</script></action>
        </reference>
 
        <reference name="product.info">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-productview/rokmage-mobileproductview.phtml</template>
            </action>
        </reference>
 
        <reference name="product.info">  
            <reference name="product.info.media" as="media" before="-">
                <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                    <template>rokmagemodules/rokmage-productview/rokmage-productview-media.phtml</template>
                </action>
            </reference>
            <block type="catalog/product_view_media" name="rokmage_product_video" >
                <action method="setTemplate" ifconfig="product_view/general/enableproductview">
                    <template>rokmagemodules/rokmage-productview/rokmage-productvideo.phtml</template>
                </action>
            </block>
        </reference>
        <reference name="product.info.upsell">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                    <template>rokmagemodules/rokmage-productview/rokmage-productview-upsell.phtml</template>
            </action>
         </reference>
         <block type="page/html_pager" name="product_review_list.toolbar" />
         <block type="review/product_view_list" name="product.info.product_additional_data" as="product_additional_data" template="review/product/view/list.phtml">
            <block type="review/form" name="product.review.form" />
         </block>
    </catalog_product_view>
 
    <cms_index_index>
        <reference name="cms_page">
            <action method="setTemplate" ifconfig="rokmage_mobile/general/enable">
                <template>rokmagemodules/rokmage-magemenus/rokmage-mobilemenu.phtml</template>
            </action>
        </reference>
        <reference name="head">
            <action method="addItem" ifconfig="rokmage_mobile/slider_settings/enable"><type>skin_js</type><script>js/jquery.moodular.js</script></action>
            <action method="addItem" ifconfig="rokmage_mobile/slider_settings/enable"><type>skin_js</type><script>js/jquery.moodular.controls.js</script></action>
        </reference>
        <reference name="root">
            <block type="catalog/product_send" name="rokmage_content_slider">
                     <action method="setTemplate" ifconfig="rokmage_mobile/slider_settings/enable">
                        <template>rokmagemodules/rokmage-contentslider/rokmage-content-slider.phtml</template>
                     </action>
             </block>
        </reference>
    </cms_index_index>
 
</layout>
~~~

Second, copy **app/code/core/Mage/Catalog/Block/Navigation.php**, add the following folder structure - **app/code/community/Mage/Catalog/Block/** - and paste the file there, and open it and add before the closing } the following:

~~~ .html
   protected function getActiveChildren($parent, $level)
    {
        $activeChildren = array();
        // --- check level ---
        $maxLevel = (int)Mage::getStoreConfig('mage_menus/settings_megamenu/subcats');
        if ($maxLevel > 0)
        {
            if ($level >= ($maxLevel - 1)) return $activeChildren;
        }
        // --- check level ---
        if (Mage::helper('catalog/category_flat')->isEnabled())
        {
            $children = $parent->getChildrenNodes();
            $childrenCount = count($children);
        }
        else
        {
            $children = $parent->getChildren();
            $childrenCount = $children->count();
        }
        $hasChildren = $children && $childrenCount;
        if ($hasChildren)
        {
            foreach ($children as $child)
            {
                if ($child->getIsActive())
                {
                    array_push($activeChildren, $child);
                }
            }
        }
        return $activeChildren;
    }
 
    private function explodeByColumns($target, $num)
    {
        $count = count($target);
        if ($count) $target = array_chunk($target, ceil($count / $num));
        $target = array_pad($target, $num, array());
        return $target;  
    }
 
    private function _countChild($children, $level, &$count)
    {
        foreach ($children as $child)
        {
            if ($child->getIsActive())
            {
                $count++; $activeChildren = $this->getActiveChildren($child, $level);
                if (count($activeChildren) > 0) $this->_countChild($activeChildren, $level + 1, $count);
            }
        }
    }
 
    public function drawMenuItem($children, $level = 1)
    {
        $html = '<div class="itemMenu level' . $level . '">';
        $keyCurrent = $this->getCurrentCategory()->getId();
        foreach ($children as $child)
        {
            if ($child->getIsActive())
            {
                // --- class for active category ---
                $active = '';
                if ($this->isCategoryActive($child))
                {
                    $active = ' active';
                    if ($child->getId() == $keyCurrent) $active = ' active';
                }
                // --- format category name ---
                $name = $this->escapeHtml($child->getName());
                $name = str_replace(' ', '&nbsp;', $name);
                $html.= '<a class="itemMenuName level' . $level . $active . '" href="' . $this->getCategoryUrl($child) . '"><span>' . $name . '</span></a>';
                $activeChildren = $this->getActiveChildren($child, $level);
                if (count($activeChildren) > 0)
                {
                    $html.= '<div class="itemSubMenu level' . $level . '">';
                    $html.= $this->drawMenuItem($activeChildren, $level + 1);
                    $html.= '</div>';
                }
            }
        }
        $html.= '</div>';
        return $html;
    }
 
    // Add accordion menu
 
    public function showAccordionMenu( $category, $object )
    {
       
        echo '<a href="' . $object->getCategoryUrl( $category ) . '" class="mageside-menu-heading ' . ($object->isCategoryActive( $category ) ? 'activecurrent current' : '' ) . '">';
        echo '<span ';
        if(Mage::helper('catalog/category_flat')->isEnabled()) {
            if ( ( $children = $category->getChildrenNodes() ) && count($children) )
            {
            echo 'class="parent"';
            }
        }  
        else
        {
            if ( ( $children = $category->getChildren() ) && $children->count() )
            {
                echo 'class="parent"';
            }
        };
        echo '>';
        echo $object->htmlEscape( $category->getName() );
        echo '</span></a>';
 
             
        if(Mage::helper('catalog/category_flat')->isEnabled()) {
            if ( ( $children = $category->getChildrenNodes() ) && count($children) )
            {
                echo '<div class="mageside-menu-toggle-button' . ($object->isCategoryActive( $category ) ? '-current' : '' ) . '"></div><div class="mageside-menu-toggle-container' . ($object->isCategoryActive( $category ) ? ' active' : '' ) . '"><ul>';
                foreach ( $children as $child_category)
                    $this->showCategoryTree( $child_category, $object );
                echo '</ul></div>';
            }
        }  
        else
            {
                if ( ( $children = $category->getChildren() ) && $children->count() )
                {
                    echo '<div class="mageside-menu-toggle-button' . ($object->isCategoryActive( $category ) ? '-current' : '' ) . '"></div><div class="mageside-menu-toggle-container' . ($object->isCategoryActive( $category ) ? ' active' : '' ) . '"><ul>';
                    foreach ( $children as $child_category)
                        $this->showCategoryTree( $child_category, $object );
                    echo '</ul></div>';
                }
            }
    }
 
    // Add category tree menu
 
    public function showCategoryTree( $category, $object )
    {
       
        // Check if item count to be shown
        $itemcount = (int)Mage::getStoreConfig('mage_menus/settings_sideleft/itemcount');
        // Get category level
        $catlevel = $category->getLevel();
        // Get levels to show from admin
        $catalog_cats = (int)Mage::getStoreConfig('mage_menus/settings_sideleft/catalog_cats');
        if($catalog_cats == 'normal' || $catalog_cats == 'tree'){ $visiblelevel = (int)Mage::getStoreConfig('mage_menus/settings_sideleft/subcats'); }
        else{ $visiblelevel = (int)Mage::getStoreConfig('mage_menus/settings_sideright/subcats'); };
        echo '<li>';
        echo '<a href="' . $object->getCategoryUrl( $category ) . '"' . ($object->isCategoryActive( $category ) ? 'class="activecurrent current"' : '' ) . '>';
        echo $object->htmlEscape( $category->getName() );
        echo '</a>';
        if($itemcount == 1) {
            $category_object = Mage::getModel('catalog/category')->load($category->getId()); // If you don't already have one
            $total = Mage::getModel('catalog/layer')->setCurrentCategory( $category_object )->getProductCollection()->getSize();
            echo "<span class=\"mageside-prod-num\">&nbsp;(".$total.")</span>";
            };
             
        if(Mage::helper('catalog/category_flat')->isEnabled()) {
            if ( ( $children = $category->getChildrenNodes() ) && count($children) && $catlevel <= $visiblelevel )
            {
            echo '<ul>';
            foreach ( $children as $child_category)
                $this->showCategoryTree( $child_category, $object );
            echo '</ul>';
            }
        }  
        else
            {
                if ( ( $children = $category->getChildren() ) && $children->count() && $catlevel <= $visiblelevel )
                {
                    echo '<ul>';
                    foreach ( $children as $child_category)
                        $this->showCategoryTree( $child_category, $object );
                    echo '</ul>';
                }
            }
 
        echo '</li>';
    }
 
    // Add custom menu for mobile theme
 
    public function showMobileTree( $category, $object )
    {      
        // Check if item count to be shown
        $itemcount = (int)Mage::getStoreConfig('rokmage_mobile/menu_settings/show_count');
        // Get category level
        $catlevel = $category->getLevel();
        // Get levels to show from admin
        $visiblelevel = (int)Mage::getStoreConfig('rokmage_mobile/menu_settings/subcats');
        echo '<li ';
        if($catlevel == '2'){ echo 'data-theme="a"';} else { echo 'data-theme="b"';};
        echo ' class="level'.$catlevel.'">';
        echo '<a href="' . $object->getCategoryUrl( $category ) . '"' . ($object->isCategoryActive( $category ) ? ' class="active"' : '' ) . '>';
        echo $object->htmlEscape( $category->getName() );
       
        if($itemcount == 1) {
            $category_object = Mage::getModel('catalog/category')->load($category->getId()); // If you don't already have one
            $total = Mage::getModel('catalog/layer')->setCurrentCategory( $category_object )->getProductCollection()->getSize();
            echo '<span class="numcount ';
            if($catlevel == '2') { echo 'ui-btn-up-a'; } else { echo 'ui-btn-up-b'; };
            echo ' ui-btn-corner-all">'.$total.'</span>';
        };
        echo '</a>';
        echo '</li>';
                 
        if(Mage::helper('catalog/category_flat')->isEnabled()) {
            if ( ( $children = $category->getChildrenNodes() ) && count($children) && $catlevel <= $visiblelevel )
            {
            foreach ( $children as $child_category)
                $this->showMobileTree( $child_category, $object );
            }
        }  
        else
            {
            if ( ( $children = $category->getChildren() ) && $children->count() && $catlevel <= $visiblelevel )
            {
            foreach ( $children as $child_category)
                $this->showMobileTree( $child_category, $object );
            }
       }  
    }
 
    // Add custom accordion menu for mobile theme
 
    public function showMobileTreeCollapsed( $category, $object )
    {      
        // Check if item count to be shown
        $itemcount = (int)Mage::getStoreConfig('rokmage_mobile/menu_settings/show_count');
        // Get category level
        $catlevel = $category->getLevel();
        // Get levels to show from admin
        $visiblelevel = (int)Mage::getStoreConfig('rokmage_mobile/menu_settings/subcats');
        // Check children
        $activeChildren = $this->getActiveChildren($category, $level);
 
        echo '<li ';
        if($catlevel == '2'){ echo 'data-role="collapsible" data-theme="a" data-iconpos="right"';} else { echo 'data-theme="b"';};
        echo ' class="level'.$catlevel.'">';
        if($catlevel == '2'){ echo '<h3 data-icon="arrow-r"' . ($object->isCategoryActive( $category ) ? ' class="active"' : '' ) . '>';}
        else { echo '<a href="' . $object->getCategoryUrl( $category ) . '"' . ($object->isCategoryActive( $category ) ? ' class="active"' : '' ) . '>'; }
        echo $object->htmlEscape( $category->getName() );  
        if($itemcount == 1) {
            $category_object = Mage::getModel('catalog/category')->load($category->getId()); // If you don't already have one
            $total = Mage::getModel('catalog/layer')->setCurrentCategory( $category_object )->getProductCollection()->getSize();
            echo '<span class="numcount ';
            if($catlevel == '2') { echo 'ui-btn-up-a'; } else { echo 'ui-btn-up-b'; };
            echo ' ui-btn-corner-all">'.$total.'</span>';
        };
        if($catlevel == '2') { echo '</h3>';} else { echo '</a>'; };
        // If no children, add parent as child
        if($catlevel == '2'){
            echo '<ul data-role="listview"><li data-theme="b" class="level3">';
            echo '<a href="' . $object->getCategoryUrl( $category ) . '"' . ($object->isCategoryActive( $category ) ? ' class="active"' : '' ) . '>';
            echo $this->__('View All').' '.$object->htmlEscape( $category->getName() );
            if($itemcount == 1) {
                $category_object = Mage::getModel('catalog/category')->load($category->getId()); // If you don't already have one
                $total = Mage::getModel('catalog/layer')->setCurrentCategory( $category_object )->getProductCollection()->getSize();
                echo '<span class="numcount ui-btn-up-b ui-btn-corner-all">'.$total.'</span>';
            };
            echo '</a></li></ul>';
        };              
        if(Mage::helper('catalog/category_flat')->isEnabled()) {
            if ( ( $children = $category->getChildrenNodes() ) && count($children) && $catlevel <= $visiblelevel )
            {
            echo '<ul data-role="listview">';
                foreach ( $children as $child_category)
                    $this->showMobileTree( $child_category, $object );
            echo '</ul>';
            }
        }  
        else
            {
            if ( ( $children = $category->getChildren() ) && $children->count() && $catlevel <= $visiblelevel )
            {
            echo '<ul data-role="listview">';
                foreach ( $children as $child_category)
                    $this->showMobileTree( $child_category, $object );
            echo '</ul>';
            }
       }
       echo '</li>';
    }
~~~

>> If your theme uses its own Navigation file, you should add the above code to the end of that, instead.

How to Create a Style using Theme Roller
-----

RokMage Mobile was built with the jQuery Mobile Framework. One of the main reasons for this was so we could integrate the Theme Roller to enable simple, lightning-fast customization. You simply need to make the style with the [Theme Roller][themeroller], download and unzip, open the minified css file and copy and paste the contents into the style input in the RokMage Mobile config. And that's it.

![][style2]

### Using the Theme Roller

When you visit the Theme Roller site, you'll see 3 identical "swatches", marked A, B and C:

![][style1]

These correspond with different sections of the theme.

| Swatch | Sections |
| :----- | :------- |
| A | Header, Footer, and Parent Category Navigation links |
| B | Sub-categories of the navigation and Call to Action buttons (Add to Cart) | 
| C | Product Lists, Product Info Pages, and all other pages |

Simply drag and drop your colors from the top onto the different parts of the swatches, then download the theme and you're done. You can also have more control over the styling by adjusting the theme settings on the left. Here you can adjust things like the gradients used etc.

To give an idea of how it will turn out, here's some examples:

![][example1]

![][example2]

![][example3]

[themeroller]: http://jquerymobile.com/themeroller/
[style1]: assets/style_1.jpg
[style2]: assets/style_2.jpg
[setup1]: assets/setup_1.jpg
[example1]: assets/rokmage_example_1.jpg
[example2]: assets/rokmage_example_2.jpg
[example3]: assets/rokmage_example_3.jpg