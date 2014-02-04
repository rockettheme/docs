---
title: Fresco: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Fresco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/fresco:Fresco

---

Header Section
-----
![][demo1]

Here is the widget breakdown for the Header section:

* Gantry Logo
* Gantry Divider
* Custom Menu
* Gantry Divider
* RokAjaxSearch

The Header section remains the same across the entire demo site. For this reason, it exists in the default **Widget Override** menu. It is also a fairly simple section to set up.

#### Gantry Logo

The first thing you will need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in the upper-left area of the front page as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Custom Menu

The Custom Menu widget allows us to add an extra menu at the bottom of the page. This menu was created separately from the main menu linked in the header, and can be configured by going to **Administration -> Appearance -> Menus**.

Here is a breakdown of what you will need to change in the widget options to match the demo.

* Set the **Select Menu** option to match the name of the menu you wish to appear in this area.
* Set the **Custom Variations** field to `horizmenu`.
* Leaving all other options at their default settings, click **Save**.

#### RokAjaxSearch

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you will want to change to match the demo. This particular instance of RokAjaxSearch requires no adjustments of options. It works just fine at its default settings.

* Leaving everything at its default setting, select **Save**.

[demo1]: assets/demo_2.jpeg
[faq]: faq.md
