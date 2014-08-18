---
title: Plethora: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Plethora Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/plethora:Plethora

---

Copyright Section
-----

![][demo]

:   1. **Gantry Branding** [30%, 5%, se]
    2. **Gantry Copyright** [30%, 20%, se]
    3. **Gantry To Top** [30%, 89%, se]

Here is the widget breakdown for the Footer section:

* Gantry Branding
* Gantry Divider
* Gantry Copyright
* Gantry Divider
* Gantry To Top

#### Gantry Branding

The Gantry Branding widget does little more than display our logo at the bottom of the page. Simply click and drag the **Gantry Branding** widget into the widget section for this to appear.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Copyright

The Gantry Copyright widget places a tiny Copyright notification at the bottom of the page. The only thing you need to change in this widget to match the demo is the text field, which includes: 

~~~ .html
<div class="rt-text-small rt-center">All demo content is for sample purposes only, intended to show a live site. All images are licensed from ShutterStock &amp; PhotoDune for exclusive use on this demo site only. Use the Plethora RocketLauncher for demo replication.</div>
~~~

#### Gantry To Top

The Gantry To Top widget is a simple indicator which allows users to jump to the top of a page with a single click. Just click and drag this widget into the section to activate it. We entered `Top` in the **To Top Text** field.

[demo]: assets/demo_8.jpeg
[roksprocket]: ../../plugins/roksprocket/
