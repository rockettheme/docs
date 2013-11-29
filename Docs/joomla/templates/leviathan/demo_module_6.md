---
title: Leviathan: Recreating the Demo - FP Footer A
description: Your Guide to Recreating Elements of the Leviathan Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/leviathan:Leviathan

---

FP Footer A
-----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting       |  
| :--------- | :------------ |  
| Title      | `FP Footer A` |  
| Show Title | Hide          |  
| Position   | footer-a      |  
| Status     | Published     |  
| Access     | Public        |  
| Language   | All           |  
| Note       | Blank         |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>
    <img class="rt-noborder" src="images/rocketlauncher/frontpage/footer/logo-footer.png" alt="Logo" />
</p>

<span>All demo content is for <strong>sample</strong> purposes only, intended to show a live site. All images are licensed from <a href="http://www.shutterstock.com" target="_blank"><strong>ShutterStock</strong></a> for  exclusive use on this <strong>demo</strong> site.</span>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                          |  
| :------------------ | :------------------------------- |  
| Module Class Suffix | `nomarginbottom nopaddingbottom` |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/footer_1.jpeg
[demo3]: assets/footer_2.jpeg
[demo4]: assets/footer_3.jpeg