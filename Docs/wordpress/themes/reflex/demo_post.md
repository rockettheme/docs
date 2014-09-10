---
title: Reflex: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Reflex Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/reflex:Reflex

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured articles on the front page. There are a couple things that have to be in order in order to see these articles populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Reflex Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent articles in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Reflex Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **Introducing Reflex with RokGallery**.

| Option         | Settings                             |
| :------------- | :-----------------                   |
| Title          | `Introducing Reflex with RokGallery` |
| Status         | Published                            |
| Tags           | Blank                                |
| Featured Image | Blank                                |


Most of the magic takes place in the article content:

~~~ .html
<p><strong>Reflex</strong> is an elegant, professional and highly flexible theme. It is the first to debut <strong>RokGallery</strong>, an advanced new <strong>multiple tagging gallery</strong> solution for WordPress, with integrated styling and accompanying documentation, instructing you on using its simple, but <strong>powerful feature</strong> set.</p>

<div class="rt-demo-grid-4 nomarginleft">
    <ul class="checkmark normalfont nomarginbottom">
        <li><strong>Gantry Framework:</strong> The theme's core, providing extensive and scalable features such as the 960 Grid System.</li>
        <li><strong>Preset Styles:</strong> A selection of six style variations, as configurable int the user friendly theme manager interface.</li>
    </ul>
</div>
<div class="rt-demo-grid-4">
    <ul class="checkmark normalfont nomarginbottom">
        <li><strong>Fusion Menu:</strong> A javascript enhanced CSS dropdown menu, with multi-column support, plus much more.</li>
        <li><strong>Extensions:</strong> Reflex has styled support for RokTabs, RokNewsFlash, RokGallery, RokNewsPager and RokAjaxSearch.</li>
    </ul>
</div>
<div class="clear"></div>
~~~ 

[demo]: assets/demo_5.jpeg
[mainbody]: assets/mainbody.jpeg