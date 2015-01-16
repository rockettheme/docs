---
title: Stratos: Recreating the Demo - About Stratos
description: Your Guide to Recreating Elements of the Stratos Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/stratos:Stratos

---

About Stratos
-----

![][demo1]

The **About Stratos** area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|       Option      |                      Setting                       |
| :---------------- | :------------------------------------------------- |
| Title             | `[span class="hidden-tablet"]About [/span]Stratos` |
| Show Title        | Show                                               |
| Position          | sidebar-a                                          |
| Status            | Published                                          |
| Access            | Public                                             |

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="hidden-tablet">A responsive template with colorful iconography.</p>
<p class="box3 fp-sidebar-img"><img src="images/rocketlauncher/frontpage/sidebar/img1.png" border="0" alt="image" /></p>
<p>Built with Gantry4 and LESS CSS.</p>
<p><a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108">Read More</a></p>
~~~

### Basic

![][demo3]

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

|        Option       |      Setting       |
| :------------------ | :----------------- |
| Alternative Layout  | Default            |
| Module Class Suffix | `box6 nomargintop` |

[demo1]: assets/about_1.jpeg
[demo2]: assets/about_2.jpeg
[demo3]: assets/about_3.jpeg
[demo4]: assets/about_4.jpeg
