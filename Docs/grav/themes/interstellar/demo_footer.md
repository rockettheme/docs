---
title: Interstellar: Recreating the Demo - Footer Section
description: Your Guide to Recreating Elements of the Interstellar Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/interstellar:Interstellar

---

## Introduction

![](assets/demo_9.jpeg)

:   1. **Custom HTML (Particle)** [5%, 1%, se]
    2. **Newsletter (Particle)** [5%, 60%, se]

The **Footer** section includes two particles: **Custom HTML** and **Newsletter**.

![](assets/home_footer.jpeg)

Here is a breakdown of the module(s) and particle(s) that appear in this section:

* [Custom HTML (particle)](#custom-html-(particle))
* [Newsletter (particle)](#newsletter-(particle))

## Section Settings

![](assets/demo_footer_settings.jpeg)

| Option           | Setting                   |
| :--------------- | :----------               |
| Layout           | Fullwidth (Boxed Content) |
| CSS Classes      | Blank                     |
| Tag Attributes   | Blank                     |

## Custom HTML (Particle)

### Particle Settings

![Demo Extension](demo_footer_1.jpeg)

| Option             | Setting       |
| :-----             | :-----        |
| Particle Name      | `Custom HTML` |
| Process Twig       | Unchecked     |
| Process Shortcodes | Unchecked     |

**Custom HTML**

~~~ .html
<div class="g-grid g-sample-sitemap">
<div class="g-block">
<ul class="nomarginall noliststyle">
<li><a href="#">About</a></li>
<li><a href="#">Our Blog</a></li>
<li><a href="#">Our Team</li>
<li><a href="#">We're hiring!</a></li>
</ul>
</div>
<div class="g-block">
<ul class="nomarginall noliststyle">
<li><a href="#">FAQ</a></li>
<li><a href="#">Support</a></li>
<li><a href="#">Showcase</li>
<li><a href="#">Contact Us</a></li>
</ul>
</div>
<div class="g-block">
<ul class="nomarginall noliststyle">
<li><a href="#">Tumblr</a></li>
<li><a href="#">Facebook</a></li>
<li><a href="#">Twitter</li>
<li><a href="#">Pinterest</a></li>
</ul>
</div>
</div>
~~~

### Block Settings

![Demo Extension](demo_footer_2.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `60%`     |

## Newsletter (Particle)

### Particle Settings

![Demo Extension](demo_footer_3.jpeg)

| Option         | Setting                                                                       |
| :-----         | :-----                                                                        |
| Particle Name  | `Newsletter`                                                                  |
| CSS Classes    | Blank                                                                         |
| Width          | Full Width                                                                    |
| Layout         | Stack Compact                                                                 |
| Style          | Square                                                                        |
| Title          | Blank                                                                         |
| Heading Text   | `Let's stay in touch. Subscribe to our newsletter to get the weekly updates.` |
| Side Text      | Blank                                                                         |
| InputBox Text  | `Your email address`                                                          |
| Button Icon    | `fa fa-chevron-circle-right`                                                  |
| Button Text    | Blank                                                                         |
| Feedburner URI | Blank                                                                         |
| Button Classes | Blank                                                                         |

### Block Settings

![Demo Extension](demo_footer_4.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `40%`     |
