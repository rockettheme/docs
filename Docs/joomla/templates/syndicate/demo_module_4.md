---
title: Syndicate: Recreating the Demo - FP Content Top A Banners
description: Your Guide to Recreating Elements of the Syndicate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/syndicate:Syndicate

---

FP Content Top A Banners
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                    |
| :--------- | :----------                |
| Title      | `FP Content Top A Banners` |
| Show Title | Hide                       |
| Position   | content-top-a              |
| Status     | Published                  |
| Access     | Public                     |

### Custom Output

~~~ .html
<div class="imu-wrapper">
    <div class="box1 floatleft imu-banner468"><p class="imu-caption imu-banner60">468x60 IMU</p></div>
    <div class="box1 floatleft imu-banner120"><p class="imu-caption imu-banner60">120x60 IMU</p></div>
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

| Option              | Setting   |
| :------------------ | :-------- |
| Module Class Suffix | `flush`   |

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_4a.jpeg
[demo3]: assets/demo_4b.jpeg
[demo4]: assets/demo_4c.jpeg
