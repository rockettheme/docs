---
title: Chapelco: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Chapelco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/chapelco:Chapelco

---

Copyright Section
-----

![][copyright]

:   1. **Text** [40%, 5%, se]
	2. **Custom Menu** [40%, 28%, se]
	3. **Gantry To Top** [40%, 88%, se]

Here is the widget breakdown for the Copyright section:

* Text
* Gantry Divider
* Custom Menu
* Gantry Divider
* Gantry To Top

The Copyright section remains the same for all areas of the site. Because of this, it is preserved as a Default widget override.

#### Text
The text widget in this area has no title. You will need to enter the following in the main text field.

~~~
<span class="rt-text-1">Designed by</span> <span class="rt-text-2">RocketTheme</span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Leave everything at its default setting, select **Save**.

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Custom Menu
The Custom Menu widget allows us to add an extra menu at the bottom of the page. This menu was created separately from the main menu linked in the header, and can be configured by going to **Administration -> Appearance -> Menus**.

Here is a breakdown of what you will need to change in the widget options to match the demo.

* Set the **Select Menu** option to match the name of the menu you wish to appear in this area.
* Enter `horizmenu hidden-phone` in the **Custom Variations** field.
* Leaving all other options at their default settings, click **Save**.

#### Gantry To Top
The Gantry To Top widget is a simple indicator which allows users to jump to the top of a page with a single click. Just click and drag this widget into the section to activate it.

[copyright]: assets/demo_10.jpeg
