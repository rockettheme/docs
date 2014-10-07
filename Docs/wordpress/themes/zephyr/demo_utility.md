---
title: Zephyr: Recreating the Demo - Utility
description: Your Guide to Recreating Elements of the Zephyr Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/zephyr:Zephyr

---

Utility Section
-----

![][demo]

:   1. **Gantry Popup Button** [35%, 6%, se]
    2. **Gantry Date** [35%, 30%, se]
    3. **RokAjaxSearch** [35%, 53%, se]

Here is the widget breakdown for the Utility section:

* Gantry Popup Button
* Gantry Date
* RokAjaxSearch

#### Gantry Popup Button

The **Gantry Popup Button** widget activates the **Popup** widget position which displays widgets placed in this position in a popup for visitors. Simply drag this widget to the widget section (there's a separate widget section for the **Popup** widgets) and complete the following to replicate the demo.

* Enter `Popup Widget` in the **Text** field.
* Enter `250` in the **Width** field.
* Enter `265` in the **Height field.
* Leaving everything else at its default setting, select **Save**. 

**Text Widget**

Here is the information needed to recreate the **Text** widget placed in the **Popup** widget position.

You will need to enter the following in the main text field.

~~~ .html
<p>This is the <strong>Popup Widget</strong>. Add any widget to the <strong>popup</strong> widget position, and place anywhere Gantry Popup widget to trigger the RokBox.</p>

<p>You can configure its height and width from the widget settings.</p>

<a class="readon" href="#"><span>More Information</span></a>            
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Popup Widget`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Date

The **Gantry Date** widget displays the current date for visitors. The options used in the demo are listed below.

| Option           | Setting                     |
| :--------------- | :-------------------------- |
| Client Side Date | Unchecked                   |
| Date Format      | Tuesday, October 7, 2014    |

All other options are either left blank or set to their default.

#### RokAjaxSearch

The RokAjaxSearch widget allows users to search your site for interesting content. In our demo, we simply clicked and dragged the RokAjaxSearch widget into position.

[demo]: assets/demo_10.jpeg
[menu]: ../../start/menus.md
[faq]: faq.md
