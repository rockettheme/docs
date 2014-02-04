---
title: Corvus: Recreating the Demo - FP Footer A
description: Your Guide to Recreating Elements of the Corvus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

FP Footer A
----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

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

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-footer-logo-block">
    <span class="rt-footer-logo"></span>
</div>

<p class="rt-uppercase"><span>All demo content is for <strong>sample</strong> purposes only<span class="visible-large">, intended to show a live site</span>. <span class="hidden-tablet">Use the <a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115"><strong>RocketLauncher</strong></a> for demo replication.</span> All images are copyrighted to their respective owners.</span></p>

<p class="rt-copyright-text nomarginbottom">Designed by <a href="http://www.rockettheme.com/" target="_blank">RocketTheme</a></p>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting       |  
| :------------------ | :------------ |  
| Module Class Suffix | `fp-footer-a` |  

[demo]: assets/demo_11.jpeg
[demo2]: assets/footer_1.jpeg
[demo3]: assets/footer_2.jpeg
[demo4]: assets/footer_3.jpeg