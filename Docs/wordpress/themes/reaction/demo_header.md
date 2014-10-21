---
title: Reaction: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Reaction Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/reaction:Reaction

---

Header Section
-----

![][demo]

:   1. **Gantry Logo** [18%, 6%, se]
    2. **Text** [50%, 6%, se]
    3. **Text** [20%, 48%, se]

Here is the widget breakdown for the Header section:

* Gantry Logo
* Text
* Gantry Divider
* Text

#### Gantry Logo

The first thing you will need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in the upper-left area of the front page as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

In this instance, the **Per Style Logo** option is selected.

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="module-content">
    <span class="rt-desc1">An <span>Individual</span> chronological
    <span>journal</span> of thoughts, <span>expressed</span> freely to
    all.<span class="rt-super">1</span></span> <span class="rt-desc2">Reaction
    is founded on the fresh, contemporary framework <em>Gantry</em>, with
    features such as the 960 grid system and a totally redesigned
    administrative interface.</span>
</div>
~~~

Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="module-content">
                    <div class="header-demo"></div>             </div>
~~~

Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_1.jpeg
[colorchooser]: assets/demo_colorchooser.png
[faq]: faq.md
