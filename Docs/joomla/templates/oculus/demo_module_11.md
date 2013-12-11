---
title: Oculus: Recreating the Demo - Our Users
description: Your Guide to Recreating Elements of the Oculus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/oculus:Oculus

---

Our Users
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `Our Users`          |  
| Show Title | Show                 |  
| Position   | sidebar-b            |  
| Status     | Published            |  
| Access     | Public               |  
| Language   | All                  |  
| Note       | Blank                |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>Basic K2 style support <span class="hidden-tablet">is available with this template.</span></p>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="images/rocketlauncher/frontpage/sidebar/img1.jpg">
    </span>
  </div>
</div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="images/rocketlauncher/frontpage/sidebar/img2.jpg">
    </span>
  </div>
</div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="images/rocketlauncher/frontpage/sidebar/img3.jpg">
    </span>
  </div>
</div>

<div class="clear"></div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="images/rocketlauncher/frontpage/sidebar/img4.jpg">
    </span>
  </div>
</div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="images/rocketlauncher/frontpage/sidebar/img5.jpg">
    </span>
  </div>
</div>

<div class="gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img alt="image" src="images/rocketlauncher/frontpage/sidebar/img6.jpg">
    </span>
  </div>
</div>

<div class="clear"></div>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                                                                                 |  
| :------------------ | :-------------------------------------------------------------------------------------- |  
| Module Class Suffix | `box6 icon-camera-retro rt-horizontal-gradient fp-sidebar-b nomarginright hidden-phone` |  

[demo]: assets/demo_module_7.jpeg
[demo2]: assets/users_1.jpeg
[demo3]: assets/users_2.jpeg
[demo4]: assets/users_3.jpeg