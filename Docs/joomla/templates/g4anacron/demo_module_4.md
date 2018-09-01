---
title: Anacron: Recreating the Demo - Dynamic, Scrolling Header
description: Your Guide to Recreating Elements of the Anacron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Anacron:Anacron

---

Dynamic, Scrolling Header
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                     |  
| :--------- | :-------------------------- |  
| Title      | `Dynamic, Scrolling Header` |  
| Show Title | Show                        |  
| Position   | feature-a                   |  
| Status     | Published                   |  
| Access     | Public                      |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-80 gantry-width-block rt-center rt-margin-auto">
    <p>The Dynamic, Scrolling Header, is a custom design feature that adds an animation effect the header, where the logo and menu are contained, whereby the header elegantly collapses upon downward scroll and smoothly reappears on upward scroll.</p>
</div>

<div class="clear"></div>

<span class="rt-title-divider"></span>

<div class="gantry-width-33 gantry-width-block rt-left">
    <div class="gantry-width-spacer">
        <h2><span class="title-icon  icon-th"></span><span>Responsive</span></h2>
        <p>A responsive layout adapts to the viewing device, whether mobile, tablet or a small or larger desktop, to ensure your site is accessible on all devices.</p>
    </div>
</div>
<div class="gantry-width-33 gantry-width-block rt-left">
    <div class="gantry-width-spacer">
        <h2><span class="title-icon  icon-signal"></span><span>Site Performance</span></h2>
        <p>RokBooster compresses and combines CSS, Javascript, Font and Image files, reducing HTTP request and overall file size, increasing site speed.</p>
    </div>
</div>

<div class="gantry-width-33 gantry-width-block rt-left">
    <div class="gantry-width-spacer">
        <h2><span class="title-icon  icon-thumbs-up"></span><span>Great Support</span></h2> 
        <p>Receive exclusive access to the Anacron communty forum board for additional assistance, alongside the free and online documentation.</p>
    </div>
</div>

<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                             |  
| :------------------ | :---------------------------------- |  
| Module Class Suffix | `fp-feature rt-center rt-big-title` |  

[demo]: assets/demo_4.jpeg
[demo2]: assets/header_1.jpeg
[demo3]: assets/header_2.jpeg
[demo4]: assets/header_3.jpeg