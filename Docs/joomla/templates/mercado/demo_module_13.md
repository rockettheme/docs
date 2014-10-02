---
title: Mercado: Recreating the Demo - Product Quick List
description: Your Guide to Recreating Elements of the Mercado Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/mercado:Mercado

---

Product Quick List
-----

![][demo]

:   1. **mod_custom** [22%, 22%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `Product Quick List` |  
| Show Title | Show                 |  
| Position   | footer-b             |  
| Status     | Published            |  
| Access     | Public               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-grid-2 rt-demo-grid-omega medmarginright">
    <a href=
    "index.php?option=com_rokecwid&amp;view=ecwid&amp;Itemid=153#ecwid:category=741485&amp;mode=category&amp;offset=0&amp;sort=normal">
    <em class="nobold normal"><strong>Digital SLRs</strong></em></a><br>
    <a href=
    "index.php?option=com_rokecwid&amp;view=ecwid&amp;Itemid=153#ecwid:category=741486&amp;mode=category&amp;offset=0&amp;sort=normal">
    <em class="nobold normal"><strong>Compact Cameras</strong></em></a><br>
    <a href=
    "index.php?option=com_rokecwid&amp;view=ecwid&amp;Itemid=153#ecwid:category=741488&amp;mode=category&amp;offset=0&amp;sort=normal">
    <em class="nobold normal"><strong>Video Cameras</strong></em></a><br>
    <a href=
    "index.php?option=com_rokecwid&amp;view=ecwid&amp;Itemid=153#ecwid:category=741487&amp;mode=category&amp;offset=0&amp;sort=normal">
    <em class="nobold normal"><strong>Lenses</strong></em></a>
</div>

<div class="rt-demo-grid-2">
    <a href=
    "index.php?option=com_rokecwid&amp;view=ecwid&amp;Itemid=153#ecwid:category=741490&amp;mode=category&amp;offset=0&amp;sort=normal">
    <em class="nobold normal"><strong>Accessories</strong></em></a><br>
    <a href=
    "index.php?option=com_rokecwid&amp;view=ecwid&amp;Itemid=153#ecwid:category=741489&amp;mode=category&amp;offset=0&amp;sort=normal">
    <em class="nobold normal"><strong>Camera Bags</strong></em></a><br>
    <a href=
    "index.php?option=com_rokecwid&amp;view=ecwid&amp;Itemid=153#ecwid:category=741490&amp;mode=category&amp;offset=0&amp;sort=normal">
    <em class="nobold normal"><strong>Miscellaneous</strong></em></a>
</div>

<div class="clear">
    &nbsp;
</div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_12.jpeg
[demo2]: assets/demo_13a.jpeg
[demo3]: assets/demo_13b.jpeg
[demo4]: assets/demo_13c.jpeg
