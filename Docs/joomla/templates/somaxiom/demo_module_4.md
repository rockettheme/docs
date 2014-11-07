---
title: Somaxiom: Recreating the Demo - New RokStories Layout
description: Your Guide to Recreating Elements of the Somaxiom Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/somaxiom:Somaxiom

---

New RokStories Layout
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |         Setting         |
| :--------- | :---------------------- |
| Title      | `New RokStories Layout` |
| Show Title | Show                    |
| Position   | feature-b               |
| Status     | Published               |
| Access     | Public                  |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="caption-surround"><img src="images/stories/demo/frontpage/feature-b1.jpg" width="260" height="94" alt="Feature Image" class="fp-image" /><div class="caption-icon">0</div>
  <div class="caption-text">This is a caption</div></div>
<p>June sees the release of an updated <strong>RokStories</strong>, with a 5th layout option with <strong>image masking</strong>, as well as <strong>vertical number listing</strong>.</p>
[readon2 url="index.php?option=com_content&view=article&id=8&Itemid=112"]More Extension Information[/readon2]
~~~

### Options

![][demo3]

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

|        Option       |  Setting   |
| :------------------ | :--------- |
| Module Class Suffix | `tab2 bg2` |

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_4a.jpeg
[demo3]: assets/demo_4b.jpeg
[demo4]: assets/demo_4c.jpeg