---
title: Interstellar: Recreating the Demo - Footer Section
description: Your Guide to Recreating Elements of the Interstellar Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/interstellar:Interstellar

---

## Introduction

![](assets/demo_9.jpeg)

:	1. **Custom HTML (Particle)** [5%, 1%, se]
	2. **Newsletter (Particle)** [5%, 60%, se]

The **Footer** section includes two particles: **Custom HTML** and a **Newsletter** particle assigned to the **footer-a** and **footer-b** module positions.

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

The **Simple Content** particle is a **Gantry 5 Particle** module placed within the **footer-a** module position. You can create a module position by dragging and dropping a **Module Position** particle into the desired location within the **Layout Manager**. The module position's settings are as follows.

### Module Position Particle Settings

#### Particle Settings

![Demo Extension](demo_footer_1.jpeg)

| Option        | Setting          |
| :-----        | :-----           |
| Particle Name | `FP Extension A` |
| Key           | `footer-a`    |
| Chrome        | `gantry`         |

#### Block Settings

![Demo Extension](demo_footer_2.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `60%`     |

### Custom HTML Particle Settings

The next step involves assigning the particle to the module position. Adding a particle to a module position can be done by creating a **Gantry 5 Particle** module by navigating to **Admin > Extensions > Modules** and clicking the green **New** button. Select the **Gantry 5 Particle** module type and create the particle using the settings found in the section below, and assigning it to the position.

#### Particle Settings

![Demo Extension](demo_footer_3.jpeg)

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

## Newsletter (Particle)

The **Newsletter** particle is a **Gantry 5 Particle** module placed within the **footer-a** module position. You can create a module position by dragging and dropping a **Module Position** particle into the desired location within the **Layout Manager**. The module position's settings are as follows.

### Module Position Particle Settings

#### Particle Settings

![Demo Extension](demo_footer_4.jpeg)

| Option        | Setting          |
| :-----        | :-----           |
| Particle Name | `FP Extension A` |
| Key           | `footer-a`    |
| Chrome        | `gantry`         |

#### Block Settings

![Demo Extension](demo_footer_5.jpeg)

| Option         | Setting   |
| :-----         | :-----    |
| CSS ID         | Blank     |
| CSS Classes    | Blank     |
| Variations     | Blank     |
| Tag Attributes | Blank     |
| Fixed Size     | Unchecked |
| Block Size     | `40%`     |

### Newsletter Particle Settings

The next step involves assigning the particle to the module position. Adding a particle to a module position can be done by creating a **Gantry 5 Particle** module by navigating to **Admin > Extensions > Modules** and clicking the green **New** button. Select the **Gantry 5 Particle** module type and create the particle using the settings found in the section below, and assigning it to the position.

#### Particle Settings

![Demo Extension](demo_footer_6.jpeg)

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