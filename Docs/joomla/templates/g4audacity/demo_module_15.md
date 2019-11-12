---
title: Audacity: Recreating the Demo - Content
description: Your Guide to Recreating Elements of the Audacity Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/g4audacity:Audacity

---

Content
-----

![](assets/demo_15.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_15a.jpeg)

| Option     | Setting      |
| :--------- | :----------- |
| Title      | `Content`    |
| Show Title | Show         |
| Position   | footer-c     |
| Status     | Published    |
| Access     | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul>
    <li><a href="#">Fonts</a></li>
    <li><a href="#">Typography</a></li>
    <li><a href="#">Menus</a></li>
    <li><a href="#">Blog Posts</a></li>
    <li><a href="#">Videos</a></li>
    <li><a href="#">Icons & Images</a></li>
    <li><a href="#">Documentation</a></li>
    <li><a href="#">Testimonials</a></li>
</ul>
~~~

### Basic

![](assets/demo_15b.jpeg)

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_15c.jpeg)

| Option              | Setting                           |
| :------------------ | :-------------------------------- |
| Module Class Suffix | `fp-footer-lists hidden-phone`    |
