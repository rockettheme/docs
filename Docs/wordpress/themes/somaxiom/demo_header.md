---
title: Somaxiom: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Somaxiom Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/somaxiom:Somaxiom

---

Header Section
-----

![][demo]

:   1. **Text** [20%, 6%, se]
    2. **Gantry Logo** [20%, 30%, se]
    3. **Gantry Categories** [20%, 73%, se]

Here is the widget breakdown for the Header section:

* Text
* Gantry Divider
* Gantry Logo
* Gantry Divider
* Gantry Categories

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>The Gantry Framework forms the core foundation of <strong>Somaxiom</strong>, combining a complex and <strong>powerful</strong> infrastructure with an <strong>intuitive</strong> and simple control interface.</p>
<a class="readon" href="#"><span>Read More</span></a><div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Gantry`.
* Switch the **Widget Variations** option to **Underline**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Logo

The first thing you will need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

In this instance, the **Per Style Logo** option has been checked.

#### Gantry Categories

The **Gantry Categories** widget displays post categories in an easy-to-use list for visitors. The settings used in the demo are listed below.

| Option            | Setting       |
| :----------       | :----------   |
| Title             | Blank         |
| Display           | List          |
| Order By          | Category Name |
| List Class        | `menu`        |
| Show Post Count   | No            |
| Show Hierarchy    | Yes           |
| Hide Empty        | No            |
| Exclude           | Blank         |
| Depth             | `0`           |
| Widget Variations | Number        |

[demo]: assets/demo_1.jpeg
[menu]: ../../start/menus.md
[faq]: faq.md
