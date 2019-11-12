---
title: Audacity: Recreating the Demo - FP Feature B
description: Your Guide to Recreating Elements of the Audacity Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/g4audacity:Audacity

---

FP Feature B
-----

![Custom HTML](assets/demo_5.jpeg)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![Details](assets/demo_5b.jpeg)

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `FP Feature B` |
| Show Title  | Hide           |
| Position    | feature-b      |
| Status      | Published      |
| Access      | Public         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div>
    <img src="images/rocketlauncher/home/fp-feature/img-01.jpg" alt="image" />
    <h2 class="title"><span><span class="hidden-tablet">An e</span><span class="visible-tablet">E</span>xtensive<span class="hidden-tablet"> array of</span> Color Chooser controls</span></h2>
    <p class="rt-title-tag">Customization</p>
    <p class="nomarginbottom"><span>Configure text and background colors<span class="hidden-tablet"> for the various sections</span>.</span></p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon3">Read More</a>
</div>

<hr />

<div>
    <img src="images/rocketlauncher/home/fp-feature/img-02.jpg" alt="image" />
    <h2 class="title"><span>Fresh Content <span class="hidden-tablet">Display </span>Layouts &amp; Themes</span></h2>
    <p class="rt-title-tag">RokSprocket</p>
    <p class="nomarginbottom"><span>New themes for RokSprocket Features<span class="hidden-tablet">: Scroller and Stories</span>.</span></p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon3">Read More</a>
</div>
~~~

### Basic

![Basic](assets/demo_5b.jpeg)

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![Advanced](assets/demo_5c.jpeg)

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `fp-feature-b` |