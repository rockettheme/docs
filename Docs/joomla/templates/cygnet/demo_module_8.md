---
title: Cygnet: Recreating the Demo - Pricing
description: Your Guide to Recreating Elements of the Cygnet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cygnet:Cygnet

---

Pricing
-----

![Custom HTML](assets/demo_7.jpeg)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![Details](assets/demo_8a.jpeg)

| Option      | Setting       |
| :---------- | :----------   |
| Title       | `Pricing`     |
| Show Title  | Show          |
| Position    | expandedtop-a |
| Status      | Published     |
| Access      | Public        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p class="rt-text-medium">RokSprocket enables you to display tabular data with image support, plus rows for price, four features, a description, as well as custom link labels and title.<a class="readon3" href="#"> Learn More</a></p>
~~~

### Basic

![Basic](assets/demo_8b.jpeg)

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![Advanced](assets/demo_8c.jpeg)

| Option              | Setting                         |
| :----------         | :----------                     |
| Module Class Suffix | `fp-expandedtop-a rt-big-title` |