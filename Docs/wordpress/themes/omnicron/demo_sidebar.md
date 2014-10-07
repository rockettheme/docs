---
title: Omnicron: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Omnicron Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/omnicron:Omnicron

---

Sidebar Section
-----

![][demo]

:   1. **Gantry Recent Comments** [9%, 15%, se]
    2. **Text** [55%, 15%, se]

Here is the widget breakdown for the Sidebar section:

* Gantry Recent Comments
* Text

#### Gantry Recent Comments

The login form located on the front page is actually a **Gantry Recent Comments** widget. Here are the widget options you will need to change in order to match the demo.

| Option                     | Setting                         |
| :----------------          | :------------------------------ |
| Title                      | `Latest Comments`               |
| Number of Comments to Show | `4`                             |
| Word Limit                 | `8`                             |
| List Class                 | `comments`                      |
| Title Variation            | Title 6                         |


#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="quote-l"><div class="quote-r">
<blockquote>
    From day one I have never regretted choosing such a great service - 5 star quality with everything.
</blockquote>
<p>- John Smith, <em>JS &amp; Co LLC.</em></p>
</div></div>                        <div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Client Testimonial`.
* Switch the **Box Variation** option to **Box 3**.
* Switch the **Title Variation** option to **Title 6**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_2.jpeg
[rokgallery]: ../../plugins/rokgallery/
[roksprocket]: ../../plugins/roksprocket/
