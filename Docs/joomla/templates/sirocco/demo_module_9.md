---
title: Sirocco: Recreating the Demo - FP SideBar
description: Your Guide to Recreating Elements of the Sirocco Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/sirocco:Sirocco

---

FP SideBar
-----

![](assets/demo_9.jpeg)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_9a.jpeg)

|   Option   |   Setting    |
| :--------- | :----------- |
| Title      | `FP SideBar` |
| Show Title | Hide         |
| Position   | sidebar-a    |
| Status     | Published    |
| Access     | Public       |

### Custom Output

~~~ .html
<div class="rt-sidebar-item">
    <h2 class="title rt-uppercase">Powerful Desktop-Level Code Editor</h2>
    <div class="boldfont">RokPad</div>
    <hr />
    <img src="images/rocketlauncher/home/fp-sidebar/img-01.jpg" alt="" />
    <div><span class="rt-title-tag">Editor</span></div> 
</div>

<div class="rt-sidebar-item">
    <h2 class="title rt-uppercase">Responsive Multi-Media Modals</h2>
    <div class="boldfont">RokBox</div>
    <hr />
    <img src="images/rocketlauncher/home/fp-sidebar/img-02.jpg" alt="" />
    <div><span class="rt-title-tag">System Plugin</span></div>  
</div>

<div class="rt-sidebar-item">
    <h2 class="title rt-uppercase">Simple Macros to Complex HTML</h2>
    <div class="boldfont">RokCandy</div>
    <hr />
    <img src="images/rocketlauncher/home/fp-sidebar/img-03.jpg" alt="" />
    <div><span class="rt-title-tag">Component</span></div>  
</div>

~~~

### Basic

![](assets/demo_9b.jpeg)

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_9c.jpeg)

|        Option       |          Setting          |
| :------------------ | :------------------------ |
| Module Class Suffix | `fp-sidebar hidden-phone` |
