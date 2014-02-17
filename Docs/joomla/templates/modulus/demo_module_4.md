---
title: Modulus: Recreating the Demo - FP Footer A
description: Your Guide to Recreating Elements of the Modulus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/modulus:Modulus

---

FP Footer A
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `FP Footer A`      |  
| Show Title | Hide               |  
| Position   | footer-a           |  
| Status     | Published          |  
| Access     | Public             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="floatright">
<ul class="list-icon fp-facebook nomarginbottom largemargintop">
    <li><a href="#"><em class="nobold normal">Facebook</em></a></li>
</ul>
<ul class="list-icon fp-twitter nomarginbottom">
    <li><a href="#"><em class="nobold normal">Twitter</em></a></li>
</ul>
<ul class="list-icon fp-flickr nomarginbottom">
    <li><a href="#"><em class="nobold normal">Flickr</em></a></li>
</ul>
<ul class="list-icon fp-vimeo nomarginbottom">
    <li><a href="#"><em class="nobold normal">Vimeo</em></a></li>
</ul>
</div>

<div class="floatright fp-contact">
<ul class="list-icon nomarginbottom largemargintop">
    <li><span class="text-icon person">7001 St Thomas Avenue</span></li>
    <li><span class="text-icon">Washington, 00000, USA</span></li>
    <li><span class="text-icon phone">1 (555) 555-555 / 555-556</span></li> 
    <li><span class="text-icon email">contact/@modulus.domain</span></li>
</ul>
</div>

<div class="module-title nomarginbottom"><h3 class="title">Contact Information</h3></div>
<p>Modulus <em>(June 2011)</em> Joomla Club Template, designed by RocketTheme LLC, available as part of a Joomla Club Subscription.</p>
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

| Option              | Setting                      |  
| :------------------ | :--------------------------- |  
| Module Class Suffix | `flushbottom nomarginbottom` |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/footera_1.jpeg
[demo3]: assets/footera_2.jpeg
[demo4]: assets/footera_3.jpeg