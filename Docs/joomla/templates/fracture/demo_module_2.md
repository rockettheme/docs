---
title: Fracture: Recreating the Demo - Gantry
description: Your Guide to Recreating Elements of the Fracture Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/fracture:Fracture

---

Gantry
-----
![][demo]
This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting   |  
| :--------- | :-------- |  
| Title      | `Gantry.` |  
| Show Title | Show      |  
| Position   | feature-a |  
| Status     | Published |  
| Access     | Public    |  
| Language   | All       |  
| Note       | Blank     |   

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-center">
  <p class="promo1">is a comprehensive set of building blocks to enable rapid development ...</p>
  <a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">Read More</a>
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
| Module Class Suffix | `title3` |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/gantry_1.jpeg
[demo3]: assets/gantry_2.jpeg
[demo4]: assets/gantry_3.jpeg