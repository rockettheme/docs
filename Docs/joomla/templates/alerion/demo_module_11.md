---
title: Alerion: Recreating the Demo - Guest Speakers
description: Your Guide to Recreating Elements of the Alerion Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

Guest Speakers
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                                                                           |  
| :--------- | :-------------------------------------------------------------------------------- |  
| Title      | `[span class="hidden-tablet"]Guest [/span]Speakers [small]Speakers Table[/small]` |  
| Show Title | Show                                                                              |  
| Position   | sidebar-a                                                                         |  
| Status     | Published                                                                         |  
| Access     | Public                                                                            |  

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present in the **Title** field. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~ .html
[solid-separator /]

[speaker img="images/rocketlauncher/frontpage/sidebar/img1.jpg" name="Mary Watson" position="Software Architech" info="Gantry offers powerful under the hood features and extras." link="#"]View Full Bio[/speaker]

[solid-separator /]

<div class="hidden-tablet">
[speaker img="images/rocketlauncher/frontpage/sidebar/img2.jpg" name="Peter Malkay" position="Design Visionary" info="Beautifully integrated typography to add life to your content." link="#"]View Full Bio[/speaker]

[solid-separator /]
</div>

<div class="visible-large">
[speaker img="images/rocketlauncher/frontpage/sidebar/img3.jpg" name="Franklin Johnston" position="CEO &amp; Founder" info="Integrated styling for K2 is also provided, but not demoed." link="#"]View Full Bio[/speaker]
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

| Option              | Setting                           |  
| :------------------ | :-------------------------------- |  
| Module Class Suffix | `box2 fp-sidebar-a2 hidden-phone` |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/speakers_1.jpeg
[demo3]: assets/speakers_2.jpeg
[demo4]: assets/speakers_3.jpeg