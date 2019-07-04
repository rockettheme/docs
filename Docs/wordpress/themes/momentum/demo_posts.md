---
title: Momentum: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Momentum Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/momentum:Momentum

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured posts on the front page. There are a couple things that have to be in order in order to see these posts populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Momentum Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent posts in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Momentum Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **RokGallery Theme Integration**.

| Option         | Settings                       |
| :------------- | :-----------------             |
| Title          | `RokGallery Theme Integration` |
| Status         | Published                      |
| Tags           | Blank                          |
| Featured Image | Blank                          |


Most of the magic takes place in the post content:

~~~ .html
<p><strong>RokGallery</strong> is an advanced photo <strong>gallery</strong> solution for WordPress, that rests on a <strong>custom tagging architecture</strong>, combined with native application <strong>slice</strong> editing.</p>

<div class="rt-demo-grid-4 nomarginleft">
  <ul class="checkmark normalfont nomarginbottom">
    <li><strong>Gallery Styling:</strong> the theme has integrated styled for the main Gallery pages</li>
    <li><strong>Administrator:</strong> select the main background image via the RokGallery interface</li>
  </ul>
</div>
<div class="rt-demo-grid-4">
  <ul class="checkmark normalfont nomarginbottom">
    <li><strong>Slideshow:</strong> use RoKGallery's slideshow to rotate between main background images</li>
    <li><strong>Grid Layout:</strong> the RokGallery widget, in Grid mode, also benefits from styled suppor.</li>
  </ul>
</div>
<div class="clear"></div>

[loadposition id="fp-rokgallery"]

~~~ 

The embedded RokGallery element is a standard **RokGallery** widget placed in the **FP RokGallery** widget position. The **Grid Columns** option has been set to **4** and it has a **4** slice limit. The **Gallery Layout** is set to **Grid**.

[demo]: assets/demo_3.jpeg
[mainbody]: assets/mainbody.jpeg