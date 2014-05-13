---
title: Paradigm: Recreate the Demo - Custom Home Page Content
description: Your Guide to Using the Paradigm Theme for Magento
tags: [Theme, RokMage, Requirements, Setup, Demo, Tutorial]
breadcrumb: /magento:Magento/!themes:Themes/paradigm:Paradigm

---

%%NOTWIG%%

Introduction
-----

![Home][home]

To set up this area of your homepage as it appears in the Paradigm demo, navigate to **CMS > Pages** from the administration area of the site. 

Then, open your homepage, click the **Content** tab, and paste the following into the content area, leaving the **Content Heading** blank:

~~~ .html
<div class="promo-wrapper">
<div class="promo-content">
        <span class="rt-width-30 left"><span class="rt-icon">&nbsp;<span class=
        "icon-desktop title">&nbsp;</span></span> <strong class=
        "title">Maecenas enim</strong></span>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
        enim arcu, vestibulum id elementum id, faucibus nec
        lectus.</p><button class="button" onclick=
        "setLocation('http://rockettheme.com')"><span>Read More</span></button>
        <span class="rt-width-30 left"><span class="rt-icon">&nbsp;<span class=
        "icon-thumbs-up title">&nbsp;</span></span> <strong class=
        "title">Mauris ut nulla</strong></span>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
        enim arcu, vestibulum id elementum id, faucibus nec
        lectus.</p><button class="button" onclick=
        "setLocation('http://rockettheme.com')"><span>Read More</span></button>
        <span class="rt-width-30 left"><span class="rt-icon">&nbsp;<span class=
        "icon-tasks title">&nbsp;</span></span> <strong class="title">Curabitur
        gravida</strong></span>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
        enim arcu, vestibulum id elementum id, faucibus nec
        lectus.</p><button class="button" onclick=
        "setLocation('http://rockettheme.com')"><span>Read More</span></button>
        <div class="clearfloat">
            &nbsp;
        </div>
    </div>
</div>
<div class="clearfloat">
    &nbsp;
</div>
<div>
    {{block type="catalog/product_list" name="rokmage_homepage_grid"
    template="rokmagemodules/rokmage-homepagegrid/rokmage-homepage-grid.phtml"}}
</div>
~~~
    
Next, click the **Design** tab, select the **RokMage 2 columns right layout** as the **Page Layout**, and in the **Layout Update XML** text area, add the following:

~~~ .html
<remove name="right" />
~~~

Once this is done, select **Save** and check your results on the frontend.

[home]: assets/home.jpg