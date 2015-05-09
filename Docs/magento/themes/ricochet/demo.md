---
title: Ricochet: Recreate the Demo
description: Your Guide to Using the Ricochet Theme for Magento
tags: [Theme, RokMage, Requirements, Setup, Demo, Tutorial]
breadcrumb: /magento:Magento/!themes:Themes/ricochet:Ricochet

---

Introduction
-----

You can recreate a number of different elements found on the front page of the Ricochet demo by modifying some basic extension settings. Depending on which extension you wish to recreate on the page, you may only need to add and adjust the settings of a single module.

The Ricochet theme handles most of the visual details for you.

All of the settings that need to be adjusted to match the demo can be found in the relevant sections under **System -> Configuration -> RT RokMage Modules**. Any options not mentioned below can be left at default settings.

![Admin](assets/admincontrol.png)

ModalHeader
-----

The **ModalHeader** module adds in some extra functionality to the header section of a Magento store. It connects the "Log In" link to a modal login form, and adds a text-resizer. It also adds a modal shopping cart viewer and styling to the search form and breadcrumbs.

#### GENERAL

|            Option           | Setting |
| :-------------------------- | :------ |
| Enable Modal Header         | Yes     |
| Enable Custom Form Elements | Yes     |
| Enable Custom Breadcrumbs   | Yes     |
| Build Title Spans           | No      |
| Disable Modal Log In        | No      |
| Disable Modal Cart          | No      |
| Disable Text Resizer        | Yes     |
| Disable Date                | Yes     |

#### Modal Window Animation Settings

~~~ .html
overlayopacity: 0.2,overlayinspeed: 300,modalpreposition: {"top":"43%"},modalpauseb4entry: 200,modalentryanimation: {"top": "50%", "opacity": "1"},modalentryspeed: 550,modalexitanimation: {"top": "55%", "opacity": "0"},modalexitspeed: 350,pauseb4overlayfadeout: 500,overlayoutspeed: 200
~~~

#### IE Support

| Option                      | Setting |  
| :-------------------------- | :------ |  
| Redirect IE6/7 Visitors     | Yes     |  
| Load 6/7 helper files       | No      |  
| Add Classes for IE6 PNG fix | Blank   |  

**Add Classes for PIE**

~~~ .html
#homepage-contentslider-container .images button.button, #homepage-contentslider-container .backward, #homepage-contentslider-container .forward, .arrow-box, #search_mini_form input, ul#magemenu-top > li.active, ul#magemenu-top li ul, .cms-index-index .surround
~~~

MageMenus
-----

Replace the default Magento dropdown menu with fully configurable, animated, jQuery based top and side menus.

#### General

| Option                          | Setting |  
| :------------------------------ | :------ |  
| Enable Top Menu                 | Yes     |  
| Enable Left Side Menu           | Yes     |  
| Enable Right Side Menu          | No      |  
| Enable Top Menu LavaLamp Effect | No      |  

#### Top Menu Settings

|           Option           |           Setting           |
| :------------------------- | :-------------------------- |
| Double Column Dropdown     | No                          |
| Apple Right Offset Fix     | No                          |
| Include Home Link          | Yes                         |
| Include Catalog Categories | Yes - as standard dropdowns |
| Slot #1 CMS Page Link      | About Us                    |
| Slot #1 sub-menu Items     | Blank                       |
| Slot #2 CMS Page Link      | Customer Service            |
| Slot #2 sub-menu Items     | `enable-cookies`            |
| Include Contact Link       | Yes                         |

#### TOP MENU ANIMATION SETTINGS

~~~ .html
mm_slidedownspeed: 100,mm_fadeoutspeed: 50,mm_css_pre: {left: 100, opacity: 0 },mm_animatein: {left: 165, opacity: 1},mm_animateout: {opacity: 0, left: 185},mm_animate_speed: 150,mm_pause: 0
~~~

#### TOP "MEGAMENU SETTINGS

| Option                       | Setting |  
| :--------------------------- | :------ |  
| Mega Dropdown Width          | `400`   |  
| Visible Sub-categories Depth | `4`     |  
| Number of Inner Columns      | `3`     |  
| Inner Column Width           | `133`   |  
| Enable Static Blocks         | Yes     |  

#### SIDE MENU LEFT SETTINGS

| Option                          | Setting                      |  
| :------------------------------ | :--------------------------- |  
| Menu Title                      | `Product Catalog`            |  
| Include Catalog Categories      | Yes - as standard accordions |  
| Visible Categories Depth        | `4`                          |  
| Collapse 1st Level Parents      | No                           |  
| Default to Open Accordion State | No                           |  
| Show Item Count                 | Yes                          |  
| Slot #2 sub-menu Items          | `enable-cookies`             |  
| Include 'Contact' link          | Yes                          |  

#### SIDE MENU RIGHT SETTINGS

| Option                          | Setting            |  
| :------------------------------ | :----------------- |  
| Menu Title                      | `Customer Service` |  
| Include Catalog Categories      | No                 |  
| Visible Categories Depth        | `4`                |  
| Collapse 1st Level Parents      | No                 |  
| Default to Open Accordion State | No                 |  
| Show Item Count                 | No                 |  
| Slot #1 CMS Page Link           | About Us           |  
| Slot #1 sub-menu items          | Blank              |  
| Slot #2 CMS Page Link           | Customer Service   |  
| Slot #2 sub-menu Items          | Blank              |  
| Include 'Contact' link          | Yes                |  

HomePage Grid
-----

Set up your store homepage with just a few clicks, with a welcome message and product lists defined in the Admin Panel.

#### GENERAL

| Option               | Setting |  
| :------------------- | :------ |  
| Enable Homepage Grid | Yes     |  

#### PRODUCT GRID SETTINGS

| Option                               | Setting                                                         |
| :----------------------------------- | :-------------------------------------------------------------- |
| Product Grid Title                   | `Latest products`                                               |
| Product Grid Text                    | `<p>Check out a selection of our items currently for sale:</p>` |
| Number of products to show in grid   | `6`                                                             |
| Default Products Layout              | Grid                                                            |
| Filter Products By                   | Recently Added Products                                         |
| Randomize Products                   | Off                                                             |
| Truncate Product Titles/Descriptions | Truncate On                                                     |
| Max Titles Length                    | 50                                                              |
| Max Descriptions Length              | 110                                                             |
| Item Height                          | 300                                                             |
| Item Width                           | 300                                                             |
| Disable Ribbons                      | Yes                                                             |

**Welcome Message**

~~~ .html
<div class="page-title">
<h1>Welcome</h1>
</div>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec pellentesque consectetur nunc, id aliquet libero tempor id. Vestibulum bibendum congue nunc, id vulputate diam. Proin commodo vitae odio ut commodo. Integer porta dolor sed molestie ullamcorper.</p>
~~~

RokMage Layouts
-----

The settings used in the RokMage Layouts module are listed below.

#### STORE LAYOUT OVERRIDES

| Option                  | Setting |  
| :---------------------- | :------ |  
| Enable LAyout Overrides | Yes     |  
| Use 2 Columns Layout    | No      |  
| Layout Update XML       | Blank   |  

#### RESPONSIVE LAYOUT SETTINGS

| Option                    | Setting |  
| :------------------------ | :------ |  
| Enable Responsive Layouts | Yes     |  
| Fix to Specific Width     | No      |  

ContentSlider
-----

Add a fully configurable content slider to the homepage and category pages, choosing which products to show.

#### GENERAL

| Option                 | Setting             |
| :--------------------- | :------------------ |
| Enable Homepage Slider | Yes                 |
| Enable Category Slider | Yes                 |
| Homepage Content Type  | Show Custom Content |
| Enable Autoplay        | Autoplay OFF        |
| Show Prev/Next Arrows  | Yes                 |
| Duration               | `4`                 |
| Disable Ribbons        | Yes                 |

#### HOMEPAGE SLIDER PRODUCTS

|                Option                |         Setting         |
| :----------------------------------- | :---------------------- |
| Filter Products By                   | Recently Added Products |
| Number of Products                   | `4`                     |
| Truncate Product Titles/Descriptions | Truncate On             |
| Image Size                           | `350`                   |
| Max Titles Length                    | `60`                    |
| Max Descriptions Length              | `250`                   |
| Randomize Products                   | Off                     |

#### CATEGORY SLIDER PRODUCTS

|                Option                |         Setting         |
| :----------------------------------- | :---------------------- |
| Filter Products By                   | Recently Added Products |
| Number of Products                   | `4`                     |
| Truncate Product Titles/Descriptions | Truncate On             |
| Image Size                           | `230`                   |
| Max Titles Length                    | `30`                    |
| Max Descriptions Length              | `130`                   |
| Hide Description                     | No                      |
| Randomize Products                   | On                      |

#### HOMEPAGE SLIDE #1 CUSTOM CONTENT

| Option                   | Setting                                                                             |
| :----------------------- | :---------------------------------------------------------------------------------- |
| Slide #1 Title           | `An Explosion of Possibilities to Showcase your Products.`                          |
| Use Image as Background  | Yes                                                                                 |
| Slide #1 Button Text     | `Read More`                                                                         |
| Slide #1 Button/Link URL | `#`                                                                                 |
| Full Size Link           | No                                                                                  |

**Slide #1 Content**

~~~ .html
<p>Ricochet combines an elegant and corporate design with rich content visuals to professionally present your products.</p>
~~~

#### HOMEPAGE SLIDE #2 CUSTOM CONTENT

| Option                   | Setting                                                      |
| :-----                   | :-----                                                       |
| Slide #2 Title           | `An Array of Template Specific Styling for RokMage Modules.` |
| Use Image as Background  | Yes                                                          |
| Slide #2 Button Text     | `Read More`                                                  |
| Slide #2 Button/Link URL | `#`                                                          |
| Full Size Link           | No                                                           |

**Slide #2 Content**

~~~ .html
<p>The RokMage Modules benefit from custom styling to make sure they blend perfectly with the theme.</p>
~~~

#### HOMEPAGE SLIDE #3 CUSTOM CONTENT

| Option                   | Setting   |
| :-----                   | :-----    |
| Slide #3 Title           | `disable` |
| Slide #3 Content         | Blank     |
| Use Image as Background  | No        |
| Slide #3 Button Text     | Blank     |
| Slide #3 Button/Link URL | Blank     |
| Full Size Link           | No        |


#### HOMEPAGE SLIDE #4 CUSTOM CONTENT

| Option                   | Setting   |
| :-----                   | :-----    |
| Slide #3 Title           | `disable` |
| Slide #3 Content         | Blank     |
| Use Image as Background  | No        |
| Slide #3 Button Text     | Blank     |
| Slide #3 Button/Link URL | Blank     |
| Full Size Link           | No        |

ProductScroller
-----

Add a fully configurable, jQuery based, animated horizontal product scroller to the homepage and category pages.

#### GENERAL

| Option                              | Setting     |
| :---------------------------------- | :---------- |
| Enable Homepage Scroller            | Yes         |
| Enable Category Scroller            | Yes         |
| Prev/Next Function                  | Page        |
| Enable Scroll Button Fade Animation | No          |
| Truncate Product Titles             | Truncate On |
| Max Titles Length                   | `32`        |
| Image Size                          | `160`       |
| Speed                               | `1`         |
| Circular                            | Loop ON     |
| Enable Autoscroll                   | No          |
| Autoscroll Interval                 | `3`         |
| Products Per Page                   | `6`         |
| Use Tooltip for Details             | Yes         |
| Use Tooltip Animations              | No          |
| Set Tooltip Offset                  | `10,2`      |
| Disable Ribbons                     | Yes         |

#### HOMEPAGE SCROLLER PRODUCTS

|       Option       |        Setting         |
| :----------------- | :--------------------- |
| Number of Products | `16`                   |
| Filter Products By | Highest Rated Products |
| Randomize Products | OFF                    |

#### CATEGORY SCROLLER PRODUCTS

|       Option       |        Setting         |
| :----------------- | :--------------------- |
| Number of Products | `16`                   |
| Filter Products By | Highest Rated Products |
| Randomize Products | OFF                    |

CategoryView
-----

Add the ability to truncate product titles and descriptions, and switch between grid and list views without a page refresh.

#### GENERAL

| Option                               | Setting     |
| :----------------------------------- | :---------- |
| Enable Category View                 | Yes         |
| Use 2 Column Layout                  | No          |
| Truncate Product Titles/Descriptions | Truncate On |
| Max Titles Length                    | `50`        |
| Max Descriptions Length              | `300`       |
| Default Products Layout              | Grid        |


#### PRODUCT FILTER SETTINGS

|              Option             | Setting |
| :------------------------------ | :------ |
| Use Accordion Effect            | Yes     |
| Product Filter Title            | Blank   |
| Open First Accordion By Default | No      |

#### CATEGORY PRODUCT IMAGE SETTINGS

|    Option    | Setting |
| :----------- | :------ |
| Image Height | `300`   |
| Image Width  | `300`   |

ProductView
-----

Replace the default zoom with a jQuery version, add improved thumbnails, and show additional info in switchable tabs.

#### General

| Option              | Setting |
| :------------------ | :------ |
| Enable Product View | Yes     |
| Use 2 Column Layout | No      |

#### PRODUCT INFO SETTINGS

|           Option           |        Setting         |
| :------------------------- | :--------------------- |
| Enable Tabbed Product Info | Yes                    |
| Quick Info Attribute       | Short Description      |
| Quick Info Content         | `{{value}}`            |
| Tab #1 Attribute           | Description            |
| Tab #1 Content             | `{{value}}`            |
| Tab #2 Attribute           | Additional Information |
| Tab #2 Content             | `{{value}}`            |
| Show Product Reviews       | Yes                    |
| Equalize Tab Heights       | No                     |
| Upsell Columns             | 2                      |

#### PRODUCT IMAGE SETTINGS

|              Option             |               Setting               |
| :------------------------------ | :---------------------------------- |
| Enable RokMage media view       | Yes                                 |
| Resize product image background | No                                  |
| Image background location       | default/rokmage-productview/images/ |
| Small Image Width               | `260`                               |
| Small Image Height              | `260`                               |
| Large Image Width               | `800`                               |
| Large Image Height              | `800`                               |
| Thumbnail Width                 | `78`                                |
| Thumbnail Height                | `78`                                |
| Disable Zoomer                  | No                                  |
| Enable Lightbox                 | No                                  |
| Original Size Lightbox Images   | No                                  |
| Use Overlaid Thumb Gallery      | Yes                                 |
| Spacing Offset                  | `20`                                |

CmsCallouts
-----

Add your left and right sidebar callout content directly from the admin - no need to touch any template or layout files.

#### GENERAL

| Option                   | Setting |  
| :----------------------- | :------ |  
| Enable Left CMS Callout  | Yes     |  
| Enable Right CMS Callout | Yes     |  

#### CONTENT

| Option              | Setting           |  
| :------------------ | :---------------- |  
| Left Callout Title  | Left CMS Callout  |  
| Right Callout Title | Right CMS Callout |  
| Include CMS Block   | Disabled          |  

**Left Callout Text**

~~~
<p>You can add your content here by going to Admin -&gt; Config -&gt; CmsCallouts -&gt; Left Callout Text. You can also disable this box entirely.</p>
~~~

**Right Callout Text**

~~~
<p>You can add your content here by going to Admin -&gt; Config -&gt; CmsCallouts -&gt; Right Callout Text. You can also disable this box entirely.</p>
~~~

FeaturedProducts
-----

Define your featured products from the admin, using selected category, attribute, or multi-select product list.

#### GENERAL

|         Option        |    Setting    |
| :-------------------- | :------------ |
| Get Featured Products | Featured List |

#### SETTINGS

|           Option          |                                                  Setting                                                   |
| :------------------------ | :--------------------------------------------------------------------------------------------------------- |
| Select Featured Category  | Root Catalog                                                                                               |
| Select Featured Attribute | Featured                                                                                                   |
| Select Featured List      | Select your 'Featured' products from this list. Hold **ctrl** and click to multi-select (**cmd** on a Mac) |
| Filter by Store Root      | No                                                                                                         |

ImageBorders
-----

Use jQuery and CSS to style your product images, giving the ability to add any border or frame you desire.

#### GENERAL

|        Option        | Setting |
| :------------------- | :------ |
| Enable Image Borders | No      |

FooterBlock
-----

Add product lists to the footer, a text box (for disclaimers etc), styled footer menu and Cart count linked to the modal cart viewer.

#### GENERAL

|             Option             |   Setting   |
| :----------------------------- | :---------- |
| Enable Footer Block            | Yes         |
| Number of Items in Lists       | `6`         |
| Truncate Product Titles        | Truncate On |
| Max Titles Length              | `22`        |
| Randomize Products             | OFF         |
| Show Recently Viewed in Folder | Yes         |

#### SETTINGS

|            Option            |        Setting         |
| :--------------------------- | :--------------------- |
| 1st Column Content           | Recently Added List    |
| 2nd Column Content           | Highest Rated Products |
| 3rd Column Content           | Featured Products List |
| Text Box Columns CMS Block   | Ricochet Social Links   |
| Include Cart Link            | Yes                    |
| Include Sitemap Link         | Yes                    |
| Include Search Terms Link    | Yes                    |
| Include Advanced Search Link | Yes                    |
| Include Contact Us Link      | Yes                    |
| Include Returns Link         | No                     |
| Disable Footer Logo          | No                     |

**Text Block Content**

~~~ .html
<h3>Disclaimer</h3>
<p><strong>Important:</strong> This demo is purely for demonstration purposes and all the content relating to products, services and events are fictional. This is not an actual store, only representative of one.</p>
<p><strong>You can edit this text by going to Admin -&gt; Configuration -&gt; RT RokMage Modules -&gt; FooterBlock -&gt; Text Box Content.</strong></p>
~~~

TinyMCE
-----

Enables the Tiny MCE editor for RokMage Extensions.

#### GENERAL

| Option                                 | Setting                |  
| :------------------------------------- | :--------------------- |  
| Enable Tiny MCE for RokMage Extensions | Yes                    |  

**Textareas to enable for**

~~~ .html
#homepage_grid_settings_welcome_msg, #homepage_grid_settings_grid_text, #content_slider_settings_custom_one_slide_one_content, #content_slider_settings_custom_two_slide_two_content, #content_slider_settings_custom_three_slide_three_content, #content_slider_settings_custom_four_slide_four_content, #cms_callouts_settings_leftcallouttext, #cms_callouts_settings_rightcallouttext, #footer_block_settings_first-custom-text, #footer_block_settings_second-custom-text, #footer_block_settings_third-custom-text, #footer_block_settings_text-box
~~~
