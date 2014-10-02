---
title: Osmosis: Recreating the Demo - FP Top A
description: Your Guide to Recreating Elements of the Osmosis Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/osmosis:Osmosis

---

FP Top A
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting    |  
| :--------- | :--------- |  
| Title      | `FP Top A` |  
| Show Title | Hide       |  
| Position   | top-a      |  
| Status     | Published  |  
| Access     | Public     |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-vertical-center">
    <p class="rt-text-extra-large">Osmosis</p>
    <p class="promo2 noitalic">Vibrant, Interactive &amp; Elegant</p>
    <span class="rt-readon-no-animate">
        <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon4" data-hover="Features">Features</a>
    </span>
</div>
~~~

### Options

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting              |
| :----------         | :----------          |
| Module Class Suffix | `fp-top-a rt-center` |

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
