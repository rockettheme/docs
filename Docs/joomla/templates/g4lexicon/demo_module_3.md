---
title: Lexicon: Recreating the Demo - Browser Survey
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

Browser Survey
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

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
<span>Google Chrome</span>
<span class="rt-text-small"><em>Webkit-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span>

<hr />

<span>Apple Safari</span>
<span class="rt-text-small"><em>Webkit-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star-half-empty"></span> <span class="icon-star-empty"></span>

<hr />

<span>Mozilla Firefox</span>
<span class="rt-text-small"><em>Gecko-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star-empty"></span>

<hr />

<span>Microsoft Internet Explorer</span>
<span class="rt-text-small"><em>Trident-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star-empty"></span> <span class="icon-star-empty"></span>

<hr />

<span>Opera</span>
<span class="rt-text-small"><em>Presto-based</em></span>
<span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star"></span> <span class="icon-star-empty"></span>
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
