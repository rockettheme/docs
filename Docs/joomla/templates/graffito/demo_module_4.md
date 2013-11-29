---
title: Graffito: Recreating the Demo - Graffito Demo
description: Your Guide to Recreating Elements of the Graffito Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/graffito:Graffito

---

Graffito Demo
-----
![][demo]

:   1. **mod_custom** [15%, 5%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `Graffito Demo.` |  
| Show Title | Show             |  
| Position   | extension-a      |  
| Status     | Published        |  
| Access     | Public           |  
| Language   | All              |  
| Note       | Blank            |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-image largemarginbottom">
    <img alt="image" src="images/rocketlauncher/frontpage/general/featured-2.jpg">
</div>

<p class="medmarginbottom"><strong>RocketLauncher</strong> is a customized <strong>Joomla</strong> install, that installs a <strong>replica</strong> of the <strong>demo</strong>.</p>

<p>All sample content images, shown in this demo, will be replaced with blanks in the <a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115"><strong>RocketLauncher</strong></a> package to avoid any copyright issue.</p>
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

[demo]: assets/demo_5.jpeg
[demo2]: assets/graffitodemo_1.jpeg
[demo3]: assets/graffitodemo_2.jpeg
[demo4]: assets/graffitodemo_3.jpeg