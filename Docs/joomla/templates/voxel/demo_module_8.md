---
title: Voxel: Recreating the Demo - Template Tutorials
description: Your Guide to Recreating Elements of the Voxel Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/voxel:Voxel

---

Template Tutorials
-----
![][demo]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                  |  
| :--------- | :----------------------- |  
| Title      | `Template Tutorials`     |  
| Show Title | Show                     |  
| Position   | content-bottom-b         |  
| Status     | Published                |  
| Access     | Public                   |  
| Language   | All                      |  
| Note       | Blank                    |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<img class="rt-floatleft" src="images/rocketlauncher/frontpage/general/tut1.jpg" alt="image" />
<p>Learn how to install the template, extensions and RocketLauncher, with this demo's <a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115" class="nobold">Installation</a> tutorial.</p>
<div class="clear"></div>

<img class="rt-floatleft" src="images/rocketlauncher/frontpage/general/tut2.jpg" alt="image" />
<p class="nomarginbottom">Explore even more with a range of template specific <a href="http://www.rockettheme.com/forum/index.php?f=607&amp;rb_v=viewforum" class="nobold">Forum-based Tutorials</a>, such as mobile setup.</p>
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

| Option              | Setting  |  
| :------------------ | :------- |  
| Module Class Suffix | `title5` |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/tutorial_1.jpeg
[demo3]: assets/tutorial_2.jpeg
[demo4]: assets/tutorial_3.jpeg