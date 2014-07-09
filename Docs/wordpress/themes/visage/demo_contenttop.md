---
title: Visage: Recreating the Demo - Content Top
description: Your Guide to Recreating Elements of the Visage Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/visage:Visage

---

Content Top Section
-----

![][demo1]

:   1. **Text** [15%, 10%, se]
    2. **RokContentRotator** [42%, 10%, se]

Here is the widget breakdown for the Content Top section:

* Text
* RokContentRotator

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<strong>Visage</strong> has integrated styled support for several RocketTheme <strong>Plugins</strong>, providing them with a consistent and stunning appearance. Included are: <strong>RokGallery</strong> (Gallery/Widget), RokTabs and <strong>RokContentRotator</strong> (below).
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `RokPlugins Integration`.
* Set the **Title Variation** to **Title 1**.
* Set the **Margin Variation** to **No Margin Bottom**.
* Set the **Padding Variation** to **No Padding Bottom**.
* Enter `nomargintop` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### RokContentRotator

This area of the demo is a RokContentRotator widget. RokContentRotator is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

[roksprocket]: ../../plugins/roksprocket/
[demo1]: assets/demo_7.jpeg
