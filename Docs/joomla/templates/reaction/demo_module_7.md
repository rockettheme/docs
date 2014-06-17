---
title: Reaction: Recreating the Demo - Photo Showcase
description: Your Guide to Recreating Elements of the Reaction Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/reaction:Reaction

---

Photo Showcase
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |
| :--------- | :----------------- |
| Title      | `Photo Showcase`   |
| Show Title | Show               |
| Position   | bottom-a           |
| Status     | Published          |
| Access     | Public             |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<img src="images/stories/demo/frontpage/photo1.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo2.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo3.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo4.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo5.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo6.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo7.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo8.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo9.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo10.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo11.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo12.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo13.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo14.jpg" alt="Photo" class="rt-image" />
<img src="images/stories/demo/frontpage/photo15.jpg" alt="Photo" class="rt-image" />
<div class="clear"></div>
<p><a href="#"><strong>View More Photos?</strong></a></p>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `rt-photo`  |

[demo]: assets/demo_7.jpeg
[demo2]: assets/demo_7a.jpeg
[demo3]: assets/demo_7b.jpeg
[demo4]: assets/demo_7c.jpeg
