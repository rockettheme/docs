---
title: How to Use the Popup Module Feature
description: Your guide to setting up a Popup Module in Joomla.
breadcrumb: /joomla:Joomla/!basic:Basic Tutorials/!how_to_use_popup_module.md:How to Use the Popup Module Feature

---

Introduction
-----

The Popup Module feature is made possible with RokBox and is featured in numerous Gantry-powered RocketTheme templates. This feature enables you to position a module within a popup for enhanced visual presentation and added effect.

Using this feature is fairly straightforward, and can be done with just about any module type. In general, a button is set in a position on your site which activates the popup module, loading any module set to the `popup` position.

>> Note: Before beginning any of the steps below, you should make sure you have the latest version of [RokBox Plugins][rokbox] installed and activated on your site.

![][popup1]

1. In your Administrator panel, navigate to **Extensions → Template Manager** and select your default RocketTheme template.

2. In the **Features** tab, set the **Popup Panel** option to **On**.

3. Set the position to where you would like the popup activation button to appear on your site. You can also set the button text that will let the user know what that button does.

4. **Save** your changes and close the **Template Manager**.

5. Navigate to **Extensions → Module Manager** and create or select the module you wish to assign to a RokBox popup.

6. Assign it to the `popup` module position.

7. **Save** your changes and publish the module.

![][popup2]

#### Use within an Article or Custom HTML Module

If you want to use either the **Popup** or **Login Panel** directly from an article or within the content body of a text block (such as a Custom HTML module), you will need to use specific div IDs in order to identify these panels and load the special stylings for them.

For the Popup Panel it's `data-rokbox-element="#rt-popupmodule"` and the Login Panel uses `data-rokbox-element="#rt-popuplogin"`. These IDs should be used in conjunction with the reference link like so:

~~~ .html
<a data-rokbox data-rokbox-element="#rt-popuplogin" href="#">My Element</a>
~~~

You will also need to make sure that the Popup module you have created is assigned to any and all menu items you intend to use it from. The same goes for **Login Panel** modules. More information about using these features with RokBox can be found in the [RokBox Documentation][rokbox].

[popup1]: assets/popup_1.jpeg
[popup2]: assets/popup_2.jpeg
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
