---
title: Omnicron: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Omnicron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/omnicron:Omnicron

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your theme settings. You can find this option by navigating to **Admin -> Omnicron Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Omnicron Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Frequently Asked Questions**.

| Option         | Settings                     |
| :----------    | :----------                  |
| Title          | `Frequently Asked Questions` |
| Status         | Published                    |
| Tags           | Blank                        |
| Featured Image | Blank                        |


Most of the magic takes place in the post content:

~~~ .html
<div class="rt-demo-grid-4">
    <ul class="bullet-notes">
        <li><em>What is RokFeatureTable?</em></li>
    </ul>

    <div class="rt-block">
        <p><strong>RokFeatureTable</strong> is designed to show tabular <strong>data</strong>, offering a user friendly <strong>interface</strong> and integrated styling.</p><a class="readon" href="#"><span>More Details</span></a>
    </div>
</div>

<div class="rt-demo-grid-4">
    <ul class="bullet-calendar">
        <li><em>What is Fusion with MegaMenu?</em></li>
    </ul>

    <div class="rt-block">
        <p><strong>MegaMenu</strong> describes a series of advanced features, such as <strong>grouped items</strong> and <strong>item distribution</strong>, to the <strong>Fusion</strong> dropdown menu.</p><a class="readon" href="#"><span>More Details</span></a>
    </div>
</div>

<div class="rt-demo-grid-4">
    <ul class="bullet-monitor">
        <li><em>What are the CSS 3 Features?</em></li>
    </ul>

    <div class="rt-block">
        <p><strong>Border radiuses</strong> for rounded corners, <strong>color transitions</strong> on hover, box shadows and CSS <strong>rotation</strong> are all included.</p><a class="readon" href="#"><span>More Details</span></a>
    </div>
</div>

<div class="rt-demo-grid-4">
    <ul class="bullet-briefcase">
        <li><em>What is the Gantry Framework?</em></li>
    </ul>

    <div class="rt-block">
        <p><strong>Gantry</strong> is an advanced <strong>framework</strong> that powers our latest themes, offering an excellent <strong>foundation</strong>, full of <strong>features</strong>.</p><a class="readon" href="#"><span>More Details</span></a>
    </div>
</div>
~~~

[demo]: assets/demo_5.jpeg
[mainbody]: assets/setadvanced.jpeg
