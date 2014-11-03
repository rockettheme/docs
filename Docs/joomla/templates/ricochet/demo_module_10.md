---
title: Ricochet: Recreating the Demo - FP Sidebar
description: Your Guide to Recreating Elements of the Ricochet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ricochet:Ricochet

---

FP Sidebar
-----

![](assets/demo_10.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_10a.jpeg)

|   Option   |   Setting    |
| :--------- | :----------- |
| Title      | `FP Sidebar` |
| Show Title | Hide         |
| Position   | sidebar-a    |
| Status     | Published    |
| Access     | Public       |

### Custom Output

~~~ .html
<div class="rt-image">
    <img src="images/rocketlauncher/home/fp-sidebar/img-04.jpg" alt="image" />
    <div class="rt-corner-triangle"><span class="fa fa-mobile"></span></div>
</div>
<div class="rt-box-content">
    <div class="gantry-width-spacer">
        <h2 class="title">Mobile Menu</h2>
        <ul class="rt-tags">
            <li>Panel</li>
            <li>SelectBox</li>
        </ul>
        <p class="largemargintop">Choose between a side panel menu or selectbox for small / mobile devices.</p>             
    </div>
</div>
~~~

### Basic

![](assets/demo_10b.jpeg)

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_10c.jpeg)

|        Option       |                 Setting                  |
| :------------------ | :--------------------------------------- |
| Module Class Suffix | `fp-sidebar box4 nopaddingall rt-center` |
