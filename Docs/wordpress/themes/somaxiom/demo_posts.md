---
title: Somaxiom: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Somaxiom Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/somaxiom:Somaxiom

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured articles on the front page. There are a couple things that have to be in order in order to see these articles populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Somaxiom Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent articles in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Somaxiom Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Powered By Gantry**.

| Option         | Settings            |
| :----------    | :----------         |
| Title          | `Powered By Gantry` |
| Status         | Published           |
| Tags           | Blank               |
| Featured Image | Blank               |


Most of the magic takes place in the article content:

~~~ .html
<img alt="image" class="floatright" height="305" src=
"http://demo.rockettheme.com/live/wordpress/somaxiom/wp-content/rockettheme/rt_somaxiom_wp/frontpage/gantry-iphone.jpg"
width="208">

<p><strong>Somaxiom</strong> is driven by the <strong>Gantry</strong>
framework. There are many great features in this Gantry, ranging from
<strong>iPhone</strong> support, to <strong>Google Web Fonts</strong>, to
<strong>Smart Loading</strong>, and much more.</p>

<h3>iPhone Platform Theme</h3>

<p>The <strong>Gantry</strong> framework expands its browser portfolio to
<strong>iPhone</strong>'s Safari, producing a <strong>mobile</strong> version
of the <strong>Somaxiom</strong> theme for all visitors using the popular
smartphone.</p>

<ul class="bullet-1">
    <li><strong>iPhone Theme:</strong> An iPhone specific layout, combining
    pre-existing theme elements with mobile specific styling.</li>

    <li><strong>Aliases:</strong> Assign current module positions to mobile
    equivalents such as <em>mobile-header &rarr; header-a</em></li>
</ul>

<h3>Google Web Fonts</h3>

<p><strong>Google</strong> have launched their new <strong>font
directory</strong> service, which offers a <strong>Font API</strong> for web
developers to load <strong>Custom Fonts</strong> straight from their
servers.</p>

<ul class="bullet-1">
    <li>Preview all available Google fonts from the Google Font Directory
    located <a href="http://code.google.com/webfonts" target="_blank">here</a>
    </li>
</ul>

[readon2 url="#"]More Gantry Information[/readon2]
~~~

[demo]: assets/demo_6.jpeg
[mainbody]: assets/setadvanced.jpeg
