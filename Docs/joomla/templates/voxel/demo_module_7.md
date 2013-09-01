---
title: Voxel: Recreating the Demo - RokBox Video
description: Your Guide to Recreating Elements of the Voxel Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/voxel:Voxel

---

RokBox Video
-----
![][demo]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `RokBox Video`   |  
| Show Title | Show             |  
| Position   | content-bottom-a |  
| Status     | Published        |  
| Access     | Public           |  
| Language   | All              |  
| Note       | Blank            |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<a href="http://www.youtube.com/watch?v=a0_FIK6h7t8" title="Thor - Official Trailer @ http://www.youtube.com/watch?v=a0_FIK6h7t8" rel="rokbox[580 320]">
  <img alt="Image" src="images/rocketlauncher/frontpage/general/sample-video.jpg" width="267" height="174" />
</a>
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
| Module Class Suffix | `title5` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/rokbox_1.jpeg
[demo3]: assets/rokbox_2.jpeg
[demo4]: assets/rokbox_3.jpeg