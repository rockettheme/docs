---
title: Galatea: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Galatea Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/galatea:Galatea

---

# Introduction

The **Blog** example page demonstrates how you can create a beautiful page with the Galatea theme. Here is some information to help you replicate this page as it appears in the demo.

# Particles

![](assets/page_blog.jpeg)

The bulk if this page is made up of **Page Content** generated in the **Mainbar** section.

# Mainbar Section

![](assets/page_blog_1.jpeg)

The **Mainbar** section includes several posts assigned to the **Blog** category, displayed through the **Page Content** particle. Here are the settings found in the **Gantry 5 Framework is the powerhouse behind the Galatea theme** article.

| Option        | Setting                                                         |
| :-----        | :-----                                                          |
| Title         | `Gantry 5 Framework is the powerhouse behind the Galatea theme` |
| Category      | `Blog`                                                          |
| Parent        | `Blog`                                                          |
| Page Template | Blog item                                                       |
| Process       | Markdown and Twig                                               |

![](assets/page_blog_2.jpeg)

![](assets/page_blog_3.jpeg)

![](assets/page_blog_4.jpeg)

**Content Body**

~~~ .html
![Sample Blog](gantry-media://backgrounds/above/above-bg.jpg)

<p class="g-lead"><span class="g-shadow-letter">R</span>Romuque ante augue, iaculis eget fringilla vel, gravida non nibh. Nullam dignissim, felis eu imperdiet feugiat, libero ipsum gravida arcu, eu fermentum elit metus vel mauris.</p>

<p>In sed nunc tincidunt, faucibus quam vel, finibus arcu. Proin nec euismod nisi, id tristique augue. Nam in erat est. Dliquam ante augue, iaculis eget fringilla vel, gravida non nibh.</p>

<p>Proin nec euismod nisi, id tristique augue. Nam in erat est. Nullam dignissim, felis eu imperdiet feugiat, libero ipsum gravida arcu, eu fermentum elit metus vel mauris.</p>

<a class="button button-2" href="{{ url('pages/blog/gantry-5-framework-is-the-powerhouse-behind-galatea') }}">Read More</a>
~~~
