---
title: Fresco: Recreating the Demo - Top Extensions
description: Your Guide to Recreating Elements of the Fresco Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/fresco:Fresco

---

Top Extensions
----
![][demo]

:   1. **mod_custom** [18%, 30%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `Top Extensions` |  
| Show Title | Show             |  
| Position   | footer-b         |  
| Status     | Published        |  
| Access     | Public           |  
| Language   | All              |  
| Note       | Blank            |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div>
  <img src="images/rocketlauncher/frontpage/general/ft-img1.jpg" class="rt-image rt-floatleft ft-img1" alt="image" width="52" height="51" />
  <h4 class="smallpaddingtop smallmarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">RokSprocket</a></h4>
  <p class="nomarginbottom">Revolutionary Extension</p>
</div>

<div class="clear"></div>

<div>
  <img src="images/rocketlauncher/frontpage/general/ft-img2.jpg" class="rt-image rt-floatleft ft-img2" alt="image" width="52" height="51" />
  <h4 class="smallpaddingtop smallmarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">RokGallery</a></h4>
  <p class="nomarginbottom">Image Gallery Extension</p>
</div>

<div class="clear"></div>

<div>
  <img src="images/rocketlauncher/frontpage/general/ft-img3.jpg" class="rt-image rt-floatleft ft-img3" alt="image" width="52" height="51" />
  <h4 class="smallpaddingtop smallmarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">RokBooster</a></h4>
  <p class="nomarginbottom">Performance Plugin</p>
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

| Option              | Setting                                                       |  
| :------------------ | :------------------------------------------------------------ |  
| Module Class Suffix | `nopaddingleft nopaddingright nomarginbottom nopaddingbottom` |  

[demo]: assets/demo_12.jpeg
[demo2]: assets/topext_1.jpeg
[demo3]: assets/topext_2.jpeg
[demo4]: assets/topext_3.jpeg