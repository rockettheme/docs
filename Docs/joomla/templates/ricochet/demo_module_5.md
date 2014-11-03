---
title: Ricochet: Recreating the Demo - FP MainBottom
description: Your Guide to Recreating Elements of the Ricochet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ricochet:Ricochet

---

FP MainBottom
-----

![](assets/demo_5.jpeg)

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_5a.jpeg)

|   Option   |     Setting     |
| :--------- | :-------------- |
| Title      | `FP MainBottom` |
| Show Title | Hide            |
| Position   | mainbottom-a    |
| Status     | Published       |
| Access     | Public          |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<ul class="rt-tags">
    <li>Colors</li>
    <li>Backgrounds</li>
    <li>Overlays</li>
</ul>
<span class="rt-promo-title">Customize the Style with Ease via the Extensive Color Chooser Options</span>
~~~

### Basic

![](assets/demo_5b.jpeg)

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![](assets/demo_5c.jpeg)

|        Option       |          Setting          |
| :------------------ | :------------------------ |
| Module Class Suffix | `fp-mainbottom rt-center` |
