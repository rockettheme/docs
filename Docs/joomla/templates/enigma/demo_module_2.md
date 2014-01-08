---
title: Enigma: Recreating the Demo - FP Feature A
description: Your Guide to Recreating Elements of the Enigma Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Enigma:Enigma

---

FP Feature A
-----

![][demo]

:   1. **mod_custom** [19%, 8%, se]

This area of the front page is made up of three **mod_custom** modules. You will find the settings used in our demo below for the first of these three modules.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | `FP Feature A`    |  
| Show Title | Hide              |  
| Position   | feature-a         |  
| Status     | Published         |  
| Access     | Public            |  
| Language   | All               |  
| Note       | Blank             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<a href=
"index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108"><img alt="RocketTheme"
class="rt-image floatleft" height="52" src=
"images/stories/demo/frontpage/fp-feature1.jpg" width="52"></a>

<h4 class="nomargintop medmarginbottom rt-upper">Gantry Framework</h4>

<p>Powerful core framework, providing for base features and functions.</p><br>
<a href=
"index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115"><img alt="RocketTheme"
class="rt-image floatleft" height="52" src=
"images/stories/demo/frontpage/fp-feature2.jpg" width="52"></a>

<h4 class="nomargintop medmarginbottom rt-upper">Fusion with MegaMenu</h4>

<p>Highly customizable, Mootools powered CSS dropdown menu.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting          |  
| :------------------ | :--------------- |  
| Module Class Suffix | `nomarginbottom` |  

[demo]: assets/demo_2.jpeg
[demo2]: assets/featurea_1.jpeg
[demo3]: assets/featurea_2.jpeg
[demo4]: assets/featurea_3.jpeg