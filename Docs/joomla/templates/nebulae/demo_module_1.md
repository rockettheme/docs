---
title: Nebulae: Recreating the Demo - FP Scroller Images
description: Your Guide to Recreating Elements of the Nebulae Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nebulae:Nebulae

---

FP Scroller Images
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

This module is the first part of a two-module set ending with **FP Content Top A** which appears at the top of two stacked modules. You can switch between these modules on the frontend by clicking the **More** button above and below the module content body.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `FP Scroller Images` |  
| Show Title | Hide                 |  
| Position   | content-top-a        |  
| Status     | Published            |  
| Access     | Public               |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<a href="images/stories/demo/frontpage/scroll-image1-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan — http://fantasticfunmachine.blogspot.com/"><img src="images/stories/demo/frontpage/scroll-image1.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="images/stories/demo/frontpage/scroll-image2-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan — http://fantasticfunmachine.blogspot.com/"><img src="images/stories/demo/frontpage/scroll-image2.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="images/stories/demo/frontpage/scroll-image3-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan — http://fantasticfunmachine.blogspot.com/"><img src="images/stories/demo/frontpage/scroll-image3.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="images/stories/demo/frontpage/scroll-image4-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan — http://fantasticfunmachine.blogspot.com/"><img src="images/stories/demo/frontpage/scroll-image4.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="images/stories/demo/frontpage/scroll-image5-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan — http://fantasticfunmachine.blogspot.com/"><img src="images/stories/demo/frontpage/scroll-image5.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="images/stories/demo/frontpage/scroll-image6-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan — http://fantasticfunmachine.blogspot.com/"><img src="images/stories/demo/frontpage/scroll-image6.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="images/stories/demo/frontpage/scroll-image7-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan — http://fantasticfunmachine.blogspot.com/"><img src="images/stories/demo/frontpage/scroll-image7.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<a href="images/stories/demo/frontpage/scroll-image8-large.jpg" rel="rokbox(gallery)[478 543]" title="Gallery Images :: &copy; Charles Guan — http://fantasticfunmachine.blogspot.com/"><img src="images/stories/demo/frontpage/scroll-image8.jpg" alt="image" width="135" height="135" class="scroll-image" /></a>
<div class="clear"></div>
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

[demo]: assets/demo_1.jpeg
[demo2]: assets/images_1.jpeg
[demo3]: assets/images_2.jpeg
[demo4]: assets/images_3.jpeg
