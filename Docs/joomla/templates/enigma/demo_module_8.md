---
title: Enigma: Recreating the Demo - Site Map
description: Your Guide to Recreating Elements of the Enigma Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/enigma:Enigma

---

Site Map
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting    |  
| :--------- | :--------- |  
| Title      | `Site Map` |  
| Show Title | Show       |  
| Position   | footer-b   |  
| Status     | Published  |  
| Access     | Public     |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-grid-2 rt-demo-grid-omega">
    <a class="mod-var-link" href="/nov11/index.php">Home</a><br>
    <a class="mod-var-link" href="/nov11/features">Features</a><br>
    <a class="mod-var-link" href="/nov11/extensions">Extensions</a>
</div>
<div class="floatright">
    <a class="mod-var-link" href="/nov11/tutorials">Tutorials</a><br>
    <a class="mod-var-link" href="/nov11/styles">Styles</a><br>
    <a class="mod-var-link" href="/nov11/j-stuff">J! Stuff</a>
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

| Option              | Setting                          |  
| :------------------ | :------------------------------- |  
| Module Class Suffix | `nomarginbottom nopaddingbottom` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/sitemap_1.jpeg
[demo3]: assets/sitemap_2.jpeg
[demo4]: assets/sitemap_3.jpeg