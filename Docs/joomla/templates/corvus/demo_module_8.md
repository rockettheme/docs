---
title: Corvus: Recreating the Demo - RocketLauncher Package
description: Your Guide to Recreating Elements of the Corvus Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

RocketLauncher Package
-----
![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                              |  
| :--------- | :--------------------------------------------------- |  
| Title      | `Replicate the demo with the RocketLauncher package` |  
| Show Title | Hide                                                 |  
| Position   | mainbottom-a                                         |  
| Status     | Published                                            |  
| Access     | Public                                               |  
| Language   | All                                                  |  
| Note       | Blank                                                |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<h3 class="nomargintop">Replicate the <a href="#">demo</a> with the RocketLauncher package</h3>
<p><a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115"><span class="rt-image-b"><img src="images/rocketlauncher/frontpage/mainbottom-a/img1.jpg" alt="image"></span></a></p>
<p><span>The RocketLauncher package installs a full version of Joomla<span class="hidden-tablet"> with the demo sample data and sample images included</span>.</span></p>
<span class="readon-wrapper2"><a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115" class="readon">Read More</a></span>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                |  
| :------------------ | :--------------------- |  
| Module Class Suffix | `fp-mainbottom-a box5` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/rocketlauncher_1.jpeg
[demo3]: assets/rocketlauncher_2.jpeg
[demo4]: assets/rocketlauncher_3.jpeg