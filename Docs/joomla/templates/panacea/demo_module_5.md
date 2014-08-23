---
title: Panacea: Recreating the Demo - FP Sidebar
description: Your Guide to Recreating Elements of the Panacea Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/panacea:Panacea

---

FP Sidebar
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting          |
| :--------- | :--------------- |
| Title      | `FP Sidebar`     |
| Show Title | Hide             |
| Position   | sidebar-a        |
| Status     | Published        |
| Access     | Public           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="content-block">
<div class="number-image">
<img src="images/stories/demo/frontpage/number-image1.jpg" alt="image" width="91" height="63" />
<span class="number-image-text">One</span>
</div>
<span class="heading1">Amazingly Adaptable</span>
<p>Featuring the most flexible and configurable layout we've ever created, it has the ability to adapt to scores of layout.</p>
</div>

<div class="content-block">
<div class="number-image">
<img src="images/stories/demo/frontpage/number-image2.jpg" alt="image" width="91" height="63" />
<span class="number-image-text">Two</span>
</div>
<span class="heading1">Lean and Clean</span>
<p>A clean and professional design coupled with less overhead, as well as optimized code and images.</p>
</div>

<div class="content-block">
<div class="number-image">
<img src="images/stories/demo/frontpage/number-image3.jpg" alt="image" width="91" height="63" />
<span class="number-image-text">Three</span>
</div>
<span class="heading1">Easier Customization</span>
<p>CSS based colors and organized CSS code blocks, along with less images allowing for quicker color.</p>
</div>
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
| Module Class Suffix | `box1`      |

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg
