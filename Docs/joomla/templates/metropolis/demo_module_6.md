---
title: Metropolis: Recreating the Demo - Our Users
description: Your Guide to Recreating Elements of the Metropolis Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/metropolis:Metropolis

---

Our Users
-----
![][demo]

:   1. **RokSprocket** [58%, 52%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting     |  
| :--------- | :---------- |  
| Title      | `Our Users` |  
| Show Title | Show        |  
| Position   | sidebar-a   |  
| Status     | Published   |  
| Access     | Public      |  
| Language   | All         |  
| Note       | Blank       |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="images/rocketlauncher/frontpage/sidebar/user1.jpg" alt="image">
    </span>
  </div>
</div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="images/rocketlauncher/frontpage/sidebar/user2.jpg" alt="image">
    </span>
  </div>
</div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="images/rocketlauncher/frontpage/sidebar/user3.jpg" alt="image">
    </span>
  </div>
</div>

<div class="clear"></div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="images/rocketlauncher/frontpage/sidebar/user4.jpg" alt="image">
    </span>
  </div>
</div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="images/rocketlauncher/frontpage/sidebar/user5.jpg" alt="image">
    </span>
  </div>
</div>

<div class="rt-demo-block gantry-width-33 gantry-width-block">
  <div class="gantry-width-spacer">
    <span class="rt-image">
      <img src="images/rocketlauncher/frontpage/sidebar/user6.jpg" alt="image">
    </span>
  </div>
</div>

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

| Option              | Setting                                        |  
| :------------------ | :--------------------------------------------- |  
| Module Class Suffix | `fp-recent-users icon-user basic hidden-phone` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/users_1.jpeg
[demo3]: assets/users_2.jpeg
[demo4]: assets/users_3.jpeg