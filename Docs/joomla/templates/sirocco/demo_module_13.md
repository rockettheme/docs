---
title: Sirocco: Recreating the Demo - Newsletter
description: Your Guide to Recreating Elements of the Sirocco Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/sirocco:Sirocco

---

Newsletter
-----

![](assets/demo_13.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_13a.jpeg)

|   Option   |   Setting    |
| :--------- | :----------- |
| Title      | `Newsletter` |
| Show Title | Hide         |
| Position   | footer-c     |
| Status     | Published    |
| Access     | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>Subscribe to the latest news, delivered weekly on your email.</p>

<form class="fp-bottom-form" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify">
    <input type="text" name="email" class="inputbox" placeholder="Your Email" />
    <input type="hidden" name="uri" value="rocketthemeblog" />
    <input type="hidden" value="en_US" name="loc" />
    <input type="submit" value="Join" class="readon" name="Submit" />
</form>
~~~

### Basic

![](assets/demo_13b.jpeg)

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_13c.jpeg)

|        Option       |              Setting              |
| :------------------ | :-------------------------------- |
| Module Class Suffix | `fp-footer-c title5 hidden-phone` |
