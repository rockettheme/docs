---
title: Lexicon: Recreating the Demo - Browser Survey
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

Browser Survey
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `Browser Survey` |  
| Show Title | Show             |  
| Position   | sidebar-a        |  
| Status     | Published        |  
| Access     | Public           |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>Google Chrome <span class="rt-text-small"><em>Webkit-based</em></span></p>
<hr>

<p>Apple Safari <span class="rt-text-small"><em>Webkit-based</em></span></p>
<hr>

<p>Mozilla Firefox <span class="rt-text-small"><em>Gecko-based</em></span></p>
<hr>

<p>Microsoft Internet Explorer <span class=
"rt-text-small"><em>Trident-based</em></span></p>
<hr>

<p>Opera <span class="rt-text-small"><em>Presto-based</em></span></p>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                     |  
| :------------------ | :-------------------------- |  
| Module Class Suffix | `box2 title2 fp-sidebar-02` |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg
