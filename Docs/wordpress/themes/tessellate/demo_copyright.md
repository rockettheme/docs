---
title: Tessellate: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Tessellate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/tessellate:Tessellate

---

Copyright Section
-----

![][demo]

:   1. **Gantry Copyright** [30%, 5%, se]
    2. **Custom Menu** [30%, 78%, se]

Here is the widget breakdown for the Footer section:

* Gantry Copyright
* Gantry Divider
* Custom Menu

#### Gantry Copyright

The Gantry Copyright widget places a tiny Copyright notification at the bottom of the page. The only thing you need to change in this widget to match the demo is the text field, which includes:

~~~ .html
<div class="rt-text-small rt-center">All demo content is for sample purposes only, intended to show a live site. All images are licensed from ShutterStock &amp; PhotoDune for exclusive use on this demo site only. Use the Tessellate RocketLauncher for demo replication.</div>
~~~

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Custom Menu

The **Custom Menu** widget allows us to add an extra menu somewhere on the page. This menu was created separately from the main menu linked in the header, and can be configured by going to **Administration -> Appearance -> Menus**.

Here is a breakdown of what you will need to change in the widget options to match the demo.

* Set the **Select Menu** option to match the name of the menu you wish to appear in this area.
* Set the **Custom Variations** field to `rt-horizmenu`.
* Leaving all other options at their default settings, click **Save**.

[demo]: assets/demo_13.jpeg
[roksprocket]: ../../plugins/roksprocket/
