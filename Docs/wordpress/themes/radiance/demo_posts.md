---
title: Radiance: Recreating the Demo - Featured Posts
description: Your Guide to Recreating Elements of the Radiance Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/radiance:Radiance

---

Featured Posts Section
-----

![][demo]

This area of the front page is the mainbody. It allows you to display featured articles on the front page. There are a couple things that have to be in order in order to see these articles populated in the MainBody section of the page.

![][mainbody]

First, you will need to have the **Display Mainbody** option set to **On** in your template settings. You can find this option by navigating to **Admin -> Radiance Theme -> Advanced -> Display Mainbody**. You will also want to make sure that the posts you want to display are set in the published status.

By default, WordPress displays the most recent articles in this area of the page. You can assign specific categories to the blog view by navigating to **Admin -> Radiance Theme -> Content -> Blog View -> Blog Category** and entering (comma separated) category IDs. If the field is left blank, the most recent posts will appear. 

Below, we have listed the settings of the post titled **Radiance Gallery**.

| Option         | Settings           |
| :------------- | :----------------- |
| Title          | `Radiance Gallery` |
| Status         | Published          |
| Tags           | Blank              |
| Featured Image | Blank              |


Most of the magic takes place in the article content:

~~~ .html
[loadposition id="gallery"] 
~~~ 

The embedded RokGallery element is a standard **RokGallery** widget placed in the **RokGallery** widget position. The **Grid Columns** option has been set to **4** and it has a **8** slice limit. The **Gallery Layout** is set to **Grid**.

[demo]: assets/demo_7.jpeg
[mainbody]: assets/mainbody.jpg