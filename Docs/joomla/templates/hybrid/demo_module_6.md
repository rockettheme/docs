---
title: Hybrid: Recreating the Demo - Images from Gallery
description: Your Guide to Recreating Elements of the Hybrid Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hybrid:Hybrid

---

Images from Gallery
-----

![][demo]

:   1. **mod_custom** [20%, 52%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting               |  
| :--------- | :-------------------- |  
| Title      | `Images from Gallery` |  
| Show Title | Show                  |  
| Position   | bottom-c              |  
| Status     | Published             |  
| Access     | Public                |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<img src="images/stories/demo/frontpage/bt1.jpg" alt="Bottom Image" class="floatleft rt-image" width="93" height="81"/>
<img src="images/stories/demo/frontpage/bt2.jpg" alt="Bottom Image" class="floatleft rt-image" width="93" height="81"/>
<img src="images/stories/demo/frontpage/bt3.jpg" alt="Bottom Image" class="floatleft rt-image" width="93" height="81"/>
<img src="images/stories/demo/frontpage/bt4.jpg" alt="Bottom Image" class="floatleftlast rt-image" width="93" height="81"/>
<div class="clear"></div>
<img src="images/stories/demo/frontpage/bt5.jpg" alt="Bottom Image" class="floatleft rt-image" width="93" height="81"/>
<img src="images/stories/demo/frontpage/bt6.jpg" alt="Bottom Image" class="floatleft rt-image" width="93" height="81"/>
<img src="images/stories/demo/frontpage/bt7.jpg" alt="Bottom Image" class="floatleft rt-image" width="93" height="81"/>
<img src="images/stories/demo/frontpage/bt8.jpg" alt="Bottom Image" class="floatleftlast rt-image" width="93" height="81"/>
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

| Option              | Setting       |  
| :------------------ | :------------ |  
| Module Class Suffix | `title1`      |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg
