---
title: Dominion: Recreating the Demo - Powered by Gantry
description: Your Guide to Recreating Elements of the Dominion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/dominion:Dominion

---

Powered by Gantry
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting             |
| :---------- | :----------         |
| Title       | `Powered by Gantry` |
| Show Title  | Show                |
| Position    | maintop-a           |
| Status      | Published           |
| Access      | Public              |

### Custom Output

~~~ .html
<div class="demo-img"><img src="images/stories/demo/frontpage/fta-1.jpg" alt="Feature Demo Image" class="rt-image"/></div>
<div class="clear"></div>
<h3 class="demo-title">Version 2.0 has arrived!</h3>

<p>Dominion is sporting the brand new expansion of the Gantry Framework, <span class="demo-title">version 2.0</span>, bringing with it many new and powerful tools and features.</p>

[readon url="index.php?option=com_content&amp;view=article&amp;id=49&amp;Itemid=156"]Learn More[/readon]
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
| Module Class Suffix | `med`       |

[demo]: assets/demo_2.jpeg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/demo_2c.jpeg
