---
title: Metropolis: Recreating the Demo - Demo Info
description: Your Guide to Recreating Elements of the Metropolis Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/metropolis:Metropolis

---

Demo Info
----
![][demo]

:   1. **mod_custom** [20%, 6%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting     |  
| :--------- | :---------- |  
| Title      | `Demo Info` |  
| Show Title | Show        |  
| Position   | footer-a    |  
| Status     | Published   |  
| Access     | Public      |  
| Language   | All         |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>All demo content is for <strong>sample</strong> purposes only, intended to show a live site. All images are licensed from <a href="http://www.shutterstock.com" target="_blank"><strong>ShutterStock</strong></a> for  exclusive use on this <strong>demo</strong> site only.</p>

<p class="rt-image hidden-tablet">
    <img class="rt-noborder" src="images/rocketlauncher/frontpage/footer/logo-footer.png" alt="Logo" />
</p>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |    

[demo]: assets/demo_7.jpeg
[demo2]: assets/info_1.jpeg
[demo3]: assets/info_2.jpeg
[demo4]: assets/info_3.jpeg