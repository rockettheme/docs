---
title: Visage: Recreating the Demo - Top Sellers
description: Your Guide to Recreating Elements of the Visage Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/visage:Visage

---

Top Sellers
-----

![][demo]

:   1. **mod_custom** [9%, 20%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `Top Sellers`  |  
| Show Title | Show           |  
| Position   | sidebar-a      |  
| Status     | Published      |  
| Access     | Public         |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="fp-side largemarginbottom"></div>
<div class="fp-side largemarginbottom">
    <img src="images/stories/demo/frontpage/ts1.jpg" width="80" height="62" alt="image" class="rt-image floatleft largemarginbottom" />
    <span><strong>iHome iD3 Speakers</strong></span><br />
    <a href="#">$199.99</a>
    <div class="clear"></div>
</div>
<div class="fp-side largemarginbottom">
    <img src="images/stories/demo/frontpage/ts2.jpg" width="80" height="62" alt="image" class="rt-image floatleft largemarginbottom" />
    <span><strong>Incase Workstation</strong></span><br />
    <a href="#">$29.99</a>
    <div class="clear"></div>
</div>
<div class="fp-side largemarginbottom">
    <img src="images/stories/demo/frontpage/ts3.jpg" width="80" height="62" alt="image" class="rt-image floatleft largemarginbottom" />
    <span><strong>Remote Control Car</strong></span><br />
    <a href="#">$79.99</a>
    <div class="clear"></div>
</div>
<div class="fp-side largemarginbottom">
    <img src="images/stories/demo/frontpage/ts4.jpg" width="80" height="62" alt="image" class="rt-image floatleft largemarginbottom" />
    <span><strong>iPhone Zip Wallet</strong></span><br />
    <a href="#">$89.99</a>
    <div class="clear"></div>
</div>
<div class="fp-side largemarginbottom">
    <img src="images/stories/demo/frontpage/ts5.jpg" width="80" height="62" alt="image" class="rt-image floatleft largemarginbottom" />
    <span><strong>Apple World Travel Kit</strong></span><br />
    <a href="#">$39.99</a>
    <div class="clear"></div>
</div>
<div class="clear"></div>

<a href="#" class="readon"><span>More Products</span></a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting  |  
| :------------------ | :------- |  
| Module Class Suffix | `icon16` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/topsellers_1.jpeg
[demo3]: assets/topsellers_2.jpeg
[demo4]: assets/topsellers_3.jpeg