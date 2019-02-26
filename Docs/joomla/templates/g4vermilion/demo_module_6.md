---
title: Vermilion: Recreating the Demo - FP ExpandedTop
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

FP ExpandedTop
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting          |
| :---------- | :----------      |
| Title       | `FP Expandedtop` |
| Show Title  | Hide             |
| Position    | expandedtop-a    |
| Status      | Published        |
| Access      | Public           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <div class="rt-icon-badge rt-text-accent2"><span class="fa fa-desktop"></span></div>
            <h5 class="medpaddingtop rt-text-accent2">Responsive Layout</h5>
            <p>A responsive layout automatically adapts to the viewing device, allowing for an optimized appearance on multiple devices, such as tablets.</p>
            <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon4">Read More</a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <div class="rt-icon-badge rt-text-accent3"><span class="fa fa-th"></span></div>
            <h5 class="medpaddingtop rt-text-accent3">Editable Structure</h5>
            <p>The template manager offers configuration options to individually control each module position row, per page, allowing for custom widths.</p>
            <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon3">Read More</a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <div class="rt-icon-badge rt-text-accent2"><span class="fa fa-mobile-phone"></span></div>
            <h5 class="medpaddingtop rt-text-accent2">Mobile Support</h5>
            <p>Vermilion has responsive styling for smartphones, but also benefits from a mobile specific menu to better match the touch based user interface.</p>
            <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon4">Read More</a>
        </div>
    </div>  
</div>
<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                    |
| :----------         | :----------                |
| Module Class Suffix | `fp-expandedtop rt-center` |

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg
