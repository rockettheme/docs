---
title: Halcyon: Recreating the Demo - Other Menu Options
description: Your Guide to Recreating Elements of the Halcyon Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/halcyon:Halcyon

---

Other Menu Options
-----

![][demo]

:   1. **mod_custom** [15%, 6%, se]

This area of the front page is a series of three **mod_custom** modules. You will find the settings used in our demo below. In this example, we're focusing on the first module in this set, **Other Menu Options**.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `Other Menu Options` |  
| Show Title | Show                 |  
| Position   | extension-a          |  
| Status     | Published            |  
| Access     | Public               |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="fp-side largepaddingbottom largemarginbottom">
    <img src="images/stories/demo/frontpage/ex1.jpg" width="110" height="82" alt="image" class="rt-image floatleft"/>
    <span><strong>SplitMenu</strong></span><br />
    <span>A basic, horizontal <em>dropline</em> menu system, with configurable options such as <em>suffix</em> and position.</span>
    <div class="clear"></div>
</div>
<div>
    <img src="images/stories/demo/frontpage/ex2.jpg" width="110" height="82" alt="image" class="rt-image floatleft"/>
    <span><strong>Fusion with MegaMenu</strong></span><br />
    <span>A <em>Mootools</em> enhanced, CSS <em>dropdown</em> menu, with animated dropdowns, column width/allocation control plus much more.</span>
    <div class="clear"></div>
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

| Option              | Setting  |  
| :------------------ | :------- |  
| Module Class Suffix | `title1` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/other_1.jpeg
[demo3]: assets/other_2.jpeg
[demo4]: assets/other_3.jpeg