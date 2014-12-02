---
title: Myriad: Recreating the Demo - About Myriad
description: Your Guide to Recreating Elements of the Myriad Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

About Myriad
----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |    Setting     |
| :--------- | :------------- |
| Title      | `About Myriad` |
| Show Title | Show           |
| Position   | feature-a      |
| Status     | Published      |
| Access     | Public         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p class="rt-lead">Myriad centers around photography, providing an elegant space for displaying full width galleries. The structure, whilst focusing on images, maintains a refined and conservative style option.</p>

<p>The theme makes uses of animated effects to add depth and character to content, without compromising on usability and professionalism. A series of bounce and slide effects are built into Myriad, as triggered by scroll events, with an option to disable them.</p>

<p class="visible-large">A responsive layout adapts automatically to the viewing device's width, such as mobile, tablet or desktop, without the need for a separate layout or content. Mobile modes have a unique menu to aid usability. 960px and 1200px fixed layout options are also available.</p>

<a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon3">Read the Whole Story</a>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

|        Option       |                          Setting                           |
| :------------------ | :--------------------------------------------------------- |
| Module Class Suffix | `fp-feature-a title5 rt-modtitle-uppercase wow fadeInLeft` |

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_4a.jpeg
[demo3]: assets/demo_4b.jpeg
[demo4]: assets/demo_4c.jpeg
