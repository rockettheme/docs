---
title: Fresco: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Fresco Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/fresco:Fresco

---

Contact Us
----
![][demo]

:   1. **mod_custom** [18%, 75%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

### Details
![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `Contact Us!`    |  
| Show Title | Show             |  
| Position   | footer-d         |  
| Status     | Published        |  
| Access     | Public           |  
| Language   | All              |  
| Note       | Blank            |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div>
  <img src="images/rocketlauncher/frontpage/general/ft-icon1.png" class="rt-floatleft" alt="image" width="15" height="15" />
  <h4 class="nomarginbottom">+1 (555) 555555</h4>
</div>

<div class="clear"></div>

<div>
  <img src="images/rocketlauncher/frontpage/general/ft-icon2.png" class="rt-floatleft" alt="image" width="15" height="15" />
  <h4 class="nomarginbottom"><a href="#">noreply/@fresco.com</a></h4>
</div>
<div class="clear"></div>

<div>
  <img src="images/rocketlauncher/frontpage/general/ft-icon3.png" class="rt-floatleft" alt="image" width="15" height="15" />
  <h4 class="nomarginbottom">Fresco City, CO, USA</h4>
</div>

<div class="clear"></div>

<div>
  <img src="images/rocketlauncher/frontpage/general/ft-icon4.png" class="rt-floatleft" alt="image" width="15" height="15" />
  <h4 class="nomarginbottom"><a href="#">Facebook</a></h4>
</div>

<div class="clear"></div>

<div>
  <img src="images/rocketlauncher/frontpage/general/ft-icon5.png" class="rt-floatleft" alt="image" width="15" height="15" />
  <h4 class="nomarginbottom"><a href="#">Twitter</a></h4>
</div>

<div class="clear"></div>

<div>
  <img src="images/rocketlauncher/frontpage/general/ft-icon6.png" class="rt-floatleft" alt="image" width="15" height="15" />
  <h4 class="nomarginbottom"><a href="#">RSS</a></h4>
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
| Module Class Suffix | `nopaddingleft nomarginbottom nopaddingbottom` |  

[demo]: assets/demo_12.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg