---
title: Audacity: Recreating the Demo - Newsletter
description: Your Guide to Recreating Elements of the Audacity Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/g4audacity:Audacity

---

Newsletter
-----

![](assets/demo_19.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_19a.jpeg)

| Option     | Setting      |
| :-----     | :-----       |
| Title      | `Newsletter` |
| Show Title | Show         |
| Position   | footer-f     |
| Status     | Published    |
| Access     | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<form class="fp-bottom-form" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify">
    <input type="text" name="email" class="inputbox" placeholder="Email" />
    <input type="hidden" name="uri" value="rocketthemeblog" />
    <input type="hidden" value="en_US" name="loc" />
    <input type="submit" value="Join" class="readon" name="Submit" />
</form>

<!--<p>We will not spam you.<span class="hidden-tablet"> You can unsubscribe at anytime.</span></p>-->
~~~

### Basic

![](assets/demo_19b.jpeg)

| Option                    | Setting |
| :-----                    | :-----  |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_19c.jpeg)

| Option              | Setting                                |
| :-----              | :-----                                 |
| Module Class Suffix | `fp-footer-f nomargintop nopaddingtop` |
