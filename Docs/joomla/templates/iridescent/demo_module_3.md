
---
title: Iridescent: Recreating the Demo - Latest News
description: Your Guide to Recreating Elements of the Iridescent Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/iridescent:Iridescent

---

Latest News
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |                                           Setting                                           |
| :--------- | :------------------------------------------------------------------------------------------ |
| Title      | `[span class="rt-title-tag"]Latest News[/span]An Exquisitely Designed RocketTheme Template` |
| Show Title | Show                                                                                        |
| Position   | top-b                                                                                       |
| Status     | Published                                                                                   |
| Access     | Public                                                                                      |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>Iridescent is a vibrant design with various integrated elements to provide a seamless and versatile template environment.<span class="hidden-tablet"> A full page RokSprocket slideshow provides a rich interface to impress, complemented by other layout options, to expand beyond its core base.</span></p>
<p class="visible-large">The template features a selection of animated extras, that without detracting from the content, provide depth to your page.</p>
<a class="readon3" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Read More</a>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

|        Option       |      Setting      |
| :------------------ | :---------------- |
| Module Class Suffix | `title5 fp-top-b` |

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg
