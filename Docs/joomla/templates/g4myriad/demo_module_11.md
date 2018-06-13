---
title: Myriad: Recreating the Demo - FP Extension
description: Your Guide to Recreating Elements of the Myriad Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

FP Extension
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |    Setting     |
| :--------- | :------------- |
| Title      | `FP Extension` |
| Show Title | Hide           |
| Position   | extension-a    |
| Status     | Published      |
| Access     | Public         |

### Custom Output

~~~ .html
<div class="superhero wow fadeInDown">
    <span>Myriad</span>
</div>

<a href="http://www.rockettheme.com/joomla/templates/myriad" class="readon wow zoomInUp" data-wow-delay="0.5s">Get it for $49</a>
~~~

### Basic

![][demo3]

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

|        Option       |         Setting          |
| :------------------ | :----------------------- |
| Module Class Suffix | `fp-extension rt-center` |

[demo]: assets/demo_12.jpeg
[demo2]: assets/demo_11a.jpeg
[demo3]: assets/demo_11b.jpeg
[demo4]: assets/demo_11c.jpeg
