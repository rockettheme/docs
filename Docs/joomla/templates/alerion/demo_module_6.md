---
title: Alerion: Recreating the Demo - FP Utility Map
description: Your Guide to Recreating Elements of the Alerion Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

FP Utility Map
-----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | FP Utility Map     |  
| Show Title        | Show               |  
| Position          | utility-a          |  
| Status            | Published          |  
| Access            | Public             |  
| Ordering          | 1. FP Utility Map  |  
| Start Publishing  | 0000-00-00 00:00:0 |  
| Finish Publishing | 0000-00-00 00:00:0 |  
| Language          | All                |  
| Note              | Blank              |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<img class="rt-map rt-img-circle hidden-phone" src="images/rocketlauncher/frontpage/utility/img1.jpg" alt="image" />
<img class="rt-map-phone visible-phone" src="images/rocketlauncher/frontpage/utility/img2.png" alt="image" />

[span class="rt-map-pins hidden-phone"]
    [pin top="-30px" left="-50px"]1[/pin]
	[pin top="60px" left="60px"]2[/pin]
	[pin top="50px" left="-335px"]3[/pin]
[/span]
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                   |  
| :------------------ | :------------------------ |  
| Module Class Suffix | `fp-utility-a` |

[demo]: assets/demo_5.jpeg
[demo2]: assets/utility_1.jpeg
[demo3]: assets/utility_2.jpeg
[demo4]: assets/utility_3.jpeg