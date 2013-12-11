---
title: Metropolis: Recreating the Demo - FP MainBottom
description: Your Guide to Recreating Elements of the Metropolis Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/metropolis:Metropolis

---

FP MainBottom
----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

>> The MainBottom section is made up of four almost identical modules in the **mainbottom-a**, **mainbottom-b**, **mainbottom-c**, and **mainbottom-d** positions. A similar look can be achieved using RokGallery's **Grid** layout, with slight functional differences.

### Details
![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | `FP MainBottom A` |  
| Show Title | Hide              |  
| Position   | mainbottom-a      |  
| Status     | Published         |  
| Language   | All               |  
| Note       | Blank             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-image">
    <img alt="image" src="images/rocketlauncher/frontpage/mainbottom/img1.jpg" />
    <div class="rt-image-description">
        <span class="icon-eye-open rt-big-icon"></span>
        <h4>Template Configuration</h4>
        <p>Guides Available</p>
        <a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=114" class="readon"><span>Read More</span></a>
    </div>
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

| Option              | Setting                              |  
| :------------------ | :----------------------------------- |  
| Module Class Suffix | `basic nopaddingleft nopaddingright` |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/mainbottom_1.jpeg
[demo3]: assets/mainbottom_2.jpeg
[demo4]: assets/mainbottom_3.jpeg
