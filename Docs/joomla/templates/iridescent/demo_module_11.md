---
title: Iridescent: Recreating the Demo - Newsletter
description: Your Guide to Recreating Elements of the Iridescent Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/iridescent:Iridescent

---

Newsletter
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |   Setting    |
| :--------- | :----------- |
| Title      | `Newsletter` |
| Show Title | Show         |
| Position   | bottom-c     |
| Status     | Published    |
| Access     | Public       |

### Custom Output

~~~ .html
<p>Sign up and we'll let you know about our new stuff and products.</p>

<form class="fp-bottom-form" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify">
    <input type="text" name="email" class="inputbox" placeholder="Your Email" />
    <input type="hidden" name="uri" value="rocketthemeblog" />
    <input type="hidden" value="en_US" name="loc" />
    <input type="submit" value="Join" class="readon" name="Submit" />
</form>
~~~

### Basic

![][demo3]

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

|        Option       |                             Setting                             |
| :------------------ | :-------------------------------------------------------------- |
| Module Class Suffix | `fp-bottom-c rt-modtitle-uppercase hidden-phone wow fadeInDown` |

[demo]: assets/demo_11.jpeg
[demo2]: assets/demo_11a.jpeg
[demo3]: assets/demo_11b.jpeg
[demo4]: assets/demo_11c.jpeg
