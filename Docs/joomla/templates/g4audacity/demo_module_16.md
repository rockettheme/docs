---
title: Audacity: Recreating the Demo - Extension
description: Your Guide to Recreating Elements of the Audacity Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/g4audacity:Audacity

---

Extension
-----

![](assets/demo_16.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_16a.png)

| Option     | Setting      |
| :--------- | :----------- |
| Title      | `Extension`  |
| Show Title | Show         |
| Position   | footer-d     |
| Status     | Published    |
| Access     | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul>
    <li><a href="#">Plugins</a></li>
    <li><a href="#">Component</a></li>
    <li><a href="#">Modules</a></li>
    <li><a href="#">Widgets</a></li>
    <li><a href="#">Gizmos</a></li>
    <li><a href="#">Add-on</a></li>
    <li><a href="#">Particle</a></li>
    <li><a href="#">Application</a></li>
</ul>
~~~

### Basic

![](assets/demo_16b.png)

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_16c.png)

| Option              | Setting                           |
| :------------------ | :-------------------------------- |
| Module Class Suffix | `fp-footer-lists hidden-phone`    |
