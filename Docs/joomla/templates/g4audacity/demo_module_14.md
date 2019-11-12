---
title: Audacity: Recreating the Demo - Theme
description: Your Guide to Recreating Elements of the Audacity Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/g4audacity:Audacity

---

Theme
-----

![](assets/demo_14.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_14a.jpeg)

| Option     | Setting      |
| :--------- | :----------- |
| Title      | `Theme`      |
| Show Title | Show         |
| Position   | footer-b     |
| Status     | Published    |
| Access     | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul>
    <li><a href="#">Template</a></li>
    <li><a href="#">Design</a></li>
    <li><a href="#">Pattern</a></li>
    <li><a href="#">Overlay</a></li>
    <li><a href="#">Style</a></li>
    <li><a href="#">Layout</a></li>
    <li><a href="#">Framework</a></li>
    <li><a href="#">Composition</a></li>
</ul>
~~~

### Basic

![](assets/demo_14b.jpeg)

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_14c.jpeg)

| Option              | Setting                           |
| :------------------ | :-------------------------------- |
| Module Class Suffix | `fp-footer-lists hidden-phone`    |
