---
title: Photon: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Photon Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/photon:Photon

---

# Introduction

The **Blog** example page demonstrates how you can create a beautiful page with the Photon theme. Here is some information to help you replicate this page as it appears in the demo.

# Particles

![](assets/page_blog.jpeg)

The bulk if this page is made up of **Page Content** generated in the **Mainbar** section. Pages (posts) are assigned to the Blog page using the **Blog List** tab in the main **Blog** page's settings. `@self.children` is listed in the **Items** field.

![](assets/page_blog_mainbar.png)

Even though there are widget and particle sections placed in the layout, as there are no other elements assigned to this page, only the content in the **Page Content** particle are displayed.

# Mainbar Section

![](assets/page_blog_1.jpeg)

The **Mainbar** section includes several pages assigned to the **Joomla Blog** category, displayed through the **Page Content** particle. Here are the settings found in the **The Layout Manager allows for complex structures to be created easily** article.

| Option     | Setting                                                                            |
| :--------- | :--------------------------------------------------------------------------------- |
| Title      | `The Layout Manager allows for complex structures to be created easily`            |

**Content Body**

~~~ .html
<p><img src="{{ url('gantry-media://rocketlauncher/pages/about-us/mainbar/img-01.jpg') }}" alt="Sample Blog"></p>

<p>Omudis ante augue, iaculis eget fringilla vel, gravida non nibh. Nullam dignissim, felis eu imperdiet feugiat, libero ipsum gravida arcu, eu fermentum elit metus vel mauris.</p>

<p>In sed nunc tincidunt, faucibus quam vel, finibus arcu. Proin nec euismod nisi, id tristique augue. Nam in erat est. Dliquam ante augue, iaculis eget fringilla vel, gravida non nibh.</p>

<p>Proin nec euismod nisi, id tristique augue. Nam in erat est. Nullam dignissim, felis eu imperdiet feugiat, libero ipsum gravida arcu, eu fermentum elit metus vel mauris.</p>

<a class="button button-2" href="{{ url('#') }}">Read More</a>
~~~
