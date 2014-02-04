---
title: Halcyon: Recreating the Demo - FP Feature A
description: Your Guide to Recreating Elements of the Halcyon Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/halcyon:Halcyon

---

FP Feature A
-----
![][demo]

:   1. **mod_custom** [16%, 7%, se]

This area of the front page is a series of four **mod_custom** modules. You will find the settings used in our demo below. In this example, we're focusing on the first module in this set, **FP Feature A**.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `FP Feature A` |  
| Show Title | Show           |  
| Position   | feature-a      |  
| Status     | Published      |  
| Access     | Public         |  
| Language   | All            |  
| Note       | Blank          |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p><img src="images/stories/demo/frontpage/ft1.jpg" alt="image" width="182" height="135" class="rt-image" /></p>
<div class="module-title"><h2 class="title">Ecwid Styling</h2></div>
<p class="nomarginbottom">A <strong>free</strong> and popular third party <strong>ecommerce</strong> extension.</p>
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

[demo]: assets/demo_4.jpeg
[demo2]: assets/feature_1.jpeg
[demo3]: assets/feature_2.jpeg
[demo4]: assets/feature_3.jpeg