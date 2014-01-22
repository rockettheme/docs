---
title: Stratos: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Stratos Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/stratos:Stratos

---

Sidebar Section
-----

![][demo]

:	1. **RokAjaxSearch** [12%, 17%, se]
	2. **Text** [31%, 17%, se]

Here is the widget breakdown for the Sidebar section:

* RokAjaxSearch
* Text

#### RokAjaxSearch

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you will want to change to match the demo.

* Enter `Site Search` in the **Title** field.
* Set the **Box Variation** to **Box 1**.
* Set the **Margin Variation** to **No Margin Bottom**.
* Leaving everything else at its default setting, select **Save**.

#### Text

The following is entered in the main text field.

~~~ .html
<p class="hidden-tablet">A responsive theme with colorful iconography.</p>

<p class="box3 fp-sidebar-img">
    <img src="http://demo.rockettheme.com/wordpress-themes/wp_stratos/wp-content/rockettheme/rt_stratos_wp/frontpage/sidebar/img1.png" alt="image" />
</p>

<p>Built with Gantry4 and LESS CSS.</p>

<a href="http://demo.rockettheme.com/wordpress-themes/wp_stratos/features/" class="readon">Read More</a>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `[span class=\"hidden-tablet\"]About [/span]Stratos` in the **Title** field.
* Set the **Box Variation** option to **Box 6**.
* Set the **Margin Variation** option to **No Margin Top**.
* Enter `fp-utility hidden-phone` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_3.jpeg