---
title: Ximenia: Recreating the Demo - K2 Integrated Styling
description: Your Guide to Recreating Elements of the Ximenia Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ximenia:Ximenia

---

K2 Integrated Styling
-----
![][demo]

:   1. **mod_custom** [50%, 8%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                  |  
| :--------- | :----------------------- |  
| Title      | `K2 Integrated Styling`  |  
| Show Title | Show                     |  
| Position   | content-top-a            |  
| Status     | Published                |  
| Access     | Public                   |  
| Language   | All                      |  
| Note       | Blank                    |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<span class="icon-list-alt fp-icon"></span>

<h4 class="nomargintop largepaddingtop"><a href="index.php?option=com_k2&amp;view=latest&amp;layout=latest&amp;Itemid=123"><em>K2 is a versatile Third Party Content Control Kit</em></a></h4>

<div class="clear"></div>

<p>Ximenia has integrated styling for <strong>K2</strong> through custom CSS that can be activated or disabled from the <strong>Advanced</strong> tab in the Joomla Template Manager.</p>

<p class="rt-center nomarginbottom"><a class="readon" href="index.php?option=com_k2&amp;view=latest&amp;layout=latest&amp;Itemid=123"><span>See More</span></a></p>
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
[demo2]: assets/k2style_1.jpeg
[demo3]: assets/k2style_2.jpeg
[demo4]: assets/k2style_3.jpeg