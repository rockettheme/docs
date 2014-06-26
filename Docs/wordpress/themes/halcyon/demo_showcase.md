---
title: Halcyon: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Halcyon Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/halcyon:Halcyon

---

Showcase Section
-----

![][demo2]

:   1. **RokStories** [16%, 8%, se]
    2. **Text** [80%, 15%, se]

Here is the widget breakdown for the Showcase section:

* RokStories
* Text

#### RokStories

This area of the demo is a RokStories widget. RokStories is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="customnomargintop nopaddingtop nomarginbottom rt-center">
    <a href="#" class="readon largemarginleft largemarginright"><span>Free Delivery &amp; Returns</span></a>
<a href="#" class="readon largemarginleft largemarginright"><span>Special/Seasonal Offers</span></a>
<a href="#" class="readon largemarginleft largemarginright"><span>Low Prices Every Week</span></a>
<a href="#" class="readon largemarginleft largemarginright"><span>Request a Catalogue</span></a></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Align Variation** option to **RT-Center**.
* Switch the **Margin Variation** option to **No Margin Top**.
* Switch the **Padding Variation** option to **No Padding Top**.
* Enter `nomarginbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo2]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket/
