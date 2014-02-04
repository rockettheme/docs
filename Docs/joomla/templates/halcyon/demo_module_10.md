---
title: Halcyon: Recreating the Demo - Promotion
description: Your Guide to Recreating Elements of the Halcyon Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/halcyon:Halcyon

---

Promotion
-----

![][demo]

:   1. **mod_custom** [15%, 68%, se]

This area of the front page is a series of three **mod_custom** modules. You will find the settings used in our demo below. In this example, we're focusing on the third module in this set, **Promotion**.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `Promotion`          |  
| Show Title | Show                 |  
| Position   | extension-b          |  
| Status     | Published            |  
| Access     | Public               |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p><img src="images/stories/demo/frontpage/ex3.jpg" alt="image" width="240" height="180" class="rt-image" /></p>
<span class="rt-upper">Advertisement</span>
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
[demo2]: assets/promotion_1.jpeg
[demo3]: assets/promotion_2.jpeg
[demo4]: assets/promotion_3.jpeg