---
title: Panacea: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Panacea Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/panacea:Panacea

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured articles on the front page. There are a couple things that have to be in order in order to see these articles populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Panacea Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent articles in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Panacea Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Panacea February Theme Release**.

| Option         | Settings                         |
| :----------    | :----------                      |
| Title          | `Panacea February Theme Release` |
| Status         | Published                        |
| Tags           | Blank                            |
| Featured Image | Blank                            |


Most of the magic takes place in the article content:

~~~ .html
<p class="dropcap"><span class="dropcap">P</span>anacea, the <strong>February 2011</strong> Theme Club release, encapsulates stylistc <strong>freedom</strong> with the inclusion of the <strong>Color Chooser</strong>, allowing for easy style customization with just a few clicks. An unconventional feature for such a design choice.</p>

<div class="demo-grid-4">
  <span class="heading1">Feature Rich Foundation</span>
  <p><strong>Panacea</strong> is built with the <strong>Gantry Framework</strong>, offering a powerful base for the theme with such notable features as the <strong>960 Grid System</strong>, amongst others.</p>
  [readon2 url="#"]Learn more[/readon2]
</div>
<div class="demo-grid-2">
  <span class="heading1">Key Features</span>
  <ul class="bullet-star">
    <li>Color Chooser</li>
    <li>Background Rotator</li>
    <li>Fusion Menu</li>
    <li>Smartloading</li>
  </ul>
</div>

<div class="clear"></div>
~~~

[demo]: assets/demo_8.jpeg
[mainbody]: assets/setadvanced.jpg
