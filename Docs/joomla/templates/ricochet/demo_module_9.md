---
title: Ricochet: Recreating the Demo - The Crew
description: Your Guide to Recreating Elements of the Ricochet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ricochet:Ricochet

---

The Crew
-----

![](assets/demo_9.jpeg)

We used a **RokSprocket** module with the **Strips** layout to make up this area of the front page. You will find the settings used in our demo below.

### Details

![](assets/demo_9a.jpeg)

|      Option      |  Setting   |
| :--------------- | :--------- |
| Title            | `The Crew` |
| Show Title       | Show       |
| Access           | Public     |
| Position         | sidebar-a  |
| Status           | Published  |
| Content Provider | Simple     |
| Type             | Strips     |

### Simple Item Example

| Option | Setting |
| :----- | :------ |
| Title  | None    |
| Image  | Custom  |
| Link   | None    |

#### Description

~~~ .html
<h2 class="title nomarginall">Annie Smith</h2>

<ul class="rt-tags">
    <li>UI Designer</li>

    <li>England</li>
</ul>

<p class="smallmargintop">As as expert in designing User Interfaces for the
past 10 years, Annie brings experience and passion to Ricochet.</p>

<div class="rt-social-buttons rt-center">
    <a class="social-button" href="#" target="_blank"><span class=
    "fa fa-twitter"></span></a> <a class="social-button" href="#" target=
    "_blank"><span class="fa fa-facebook"></span></a> <a class="social-button"
    href="#" target="_blank"><span class="fa fa-google-plus"></span></a>
    <a class="social-button" href="#" target="_blank"><span class=
    "fa fa-linkedin"></span></a>
</div>
~~~

### Layout Options

![](assets/demo_9b.jpeg)

|       Option      |   Setting    |
| :---------------- | :----------- |
| Theme             | Default      |
| Display Limit     | `∞`          |
| Preview Length    | `∞`          |
| Strip HTML Tags   | No           |
| Previews Per Page | `1`          |
| Items Per Row     | `1`          |
| Arrow Navigation  | Show         |
| Pagination        | Hide         |
| Animation         | Fade Delayed |
| Autoplay          | Disable      |
| Autoplay Delay    | 5            |
| Image Resize      | Disable      |

### Advanced

![](assets/demo_9c.jpeg)

|        Option       |                        Setting                        |
| :------------------ | :---------------------------------------------------- |
| Module Class Suffix | `fp-roksprocket-strips-sidebar title6 box6 rt-center` |
