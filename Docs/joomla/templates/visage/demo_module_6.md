---
title: Visage: Recreating the Demo - RocketLauncher
description: Your Guide to Recreating Elements of the Visage Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/visage:Visage

---

RocketLauncher
-----

![][demo]

:   1. **mod_custom** [15%, 15%, se]

This area of the front page is a series of two **mod_custom** modules. You will find the settings for the first of these modules used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                                                              |  
| :--------- | :------------------------------------------------------------------- |  
| Title      | `[title1]RocketLauncher[/title1][title2]Quick Demo Replica[/title2]` |  
| Show Title | Show                                                                 |  
| Position   | sidebar-a                                                            |  
| Status     | Published                                                            |  
| Access     | Public                                                               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p>With <a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=114">RocketLauncher</a>, easily replicate the demo, which contains a <strong>full</strong> Joomla install, the template and any other <strong>sample</strong> data.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                                 |  
| :------------------ | :-------------------------------------- |  
| Module Class Suffix | `title6 nomarginbottom nopaddingbottom` |  

[demo]: assets/demo_10.jpeg
[demo2]: assets/rocketlauncher_1.jpeg
[demo3]: assets/rocketlauncher_2.jpeg
[demo4]: assets/rocketlauncher_3.jpeg