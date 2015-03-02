---
title: Audacity: Recreating the Demo - Website
description: Your Guide to Recreating Elements of the Audacity Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/audacity:Audacity

---

Website
-----

![](assets/demo_13.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_13a.jpeg)

| Option     | Setting      |
| :--------- | :----------- |
| Title      | `Website`    |
| Show Title | Show         |
| Position   | footer-a     |
| Status     | Published    |
| Access     | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul>
    <li><a href="#">News</a></li>
    <li><a href="#">Blog</a></li>
    <li><a href="#">Directory</a></li>
    <li><a href="#">E-Commerce</a></li>
    <li><a href="#">Corporate</a></li>
    <li><a href="#">Dating</a></li>
    <li><a href="#">Community</a></li>
    <li><a href="#">Religious</a></li>
</ul>
~~~

### Basic

![](assets/demo_13b.jpeg)

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_13c.jpeg)

| Option              | Setting                           |
| :------------------ | :-------------------------------- |
| Module Class Suffix | `fp-footer-lists hidden-phone`    |
