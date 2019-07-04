---
title: Zephyr: Recreating the Demo - MainBody
description: Your Guide to Recreating Elements of the Zephyr Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/zephyr:Zephyr

---

MainBody Section
-----

![][demo]

This area of the front page is the MainBody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Zephyr Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Zephyr Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear.

Below, we have listed the settings of the post titled **Ultimate Style Control**.

| Option         | Settings                     |
| :----------    | :----------                  |
| Title          | `Ultimate Style Control`     |
| Status         | Published                    |
| Tags           | Blank                        |
| Featured Image | Blank                        |


Most of the magic takes place in the post content:

~~~ .html
<p><strong>Transparency</strong> lays at the heart of the Zephyr theme, with the entire theme being developed around it. Every structural image is transparent to allow <strong>background colors</strong> to bleed through seamlessly.</p>

<p>In unison is the <strong>Color Chooser</strong>, providing extension controls, in a user friendly interface, over all style in the theme, ranging from <strong>background, text or link colors</strong> to the overlay styles.</p>
~~~

[demo]: assets/demo_5.jpeg
[mainbody]: assets/setadvanced.jpeg
