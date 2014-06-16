---
title: Reaction: Recreating the Demo - Subscribe RSS
description: Your Guide to Recreating Elements of the Reaction Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/reaction:Reaction

---

Subscribe RSS
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting          |
| :--------- | :--------------- |
| Title      | `Subscribe RSS`       |
| Show Title | Show             |
| Position   | sidebar-a        |
| Status     | Published        |
| Access     | Public           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="demo-rss-left">
    <img src="images/stories/demo/frontpage/rss.png" alt="RSS" class="demo-rss-img" />
    <a href="#"><strong>Subscribe via RSS?</strong></a>
</div>

<div class="demo-rss-right">
    <img src="images/stories/demo/frontpage/twitter.png" alt="Twitter" class="demo-rss-img" />
    <span><strong>Follow us on Twitter?</strong></span>
</div>

<div class="demo-divider"></div>

<div class="demo-rss-left">
    <img src="images/stories/demo/frontpage/email.png" alt="Email" class="demo-rss-email" />
    <span><strong>Subscribe via Email?</strong></span>
</div>

<div class="demo-rss-right">
    <img src="images/stories/demo/frontpage/facebook.png" alt="Facebook" class="demo-rss-img" />
    <span><strong>Find us on Facebook?</strong></span>
</div>

<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | Yes         |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix |             |

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg
