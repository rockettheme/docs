---
title: Nebulae: Recreating the Demo - FP Content Top A
description: Your Guide to Recreating Elements of the Nebulae Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nebulae:Nebulae

---

FP Content Top A
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

This module is the second part of a two-module set beginning with **FP Scroller Images** which appears at the top of two stacked modules. You can switch between these modules on the frontend by clicking the **More** button above and below the module content body.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `FP Content Top A` |  
| Show Title | Hide               |  
| Position   | content-top-a      |  
| Status     | Published          |  
| Access     | Public             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-grid-4">
<div class="module-title"><h2 class="title">Scrolling Modules</h2></div>
<p><strong>Scrolling Positions</strong> is a feature of Gantry, which, when activated, modifies the behaviour of <strong>stacked</strong> modules. Instead of appearing vertically, the additional modules assigned to a given position become accessible via a <strong>javascript transition button</strong>, in this case: "More".</p>
<p>The <a href="#">Content Top</a> and <a href="#">Content Bottom</a> position rows have this feature.</p>
</div>
<div class="rt-demo-grid-4 floatright">
<div class="module-title"><h2 class="title">Hidden Component</h2></div>
<p>In this demo, we have disabled the frontpage component from displaying, therefore, only modules will appear. This is achievable via a setting in <strong>Admin &rarr; Extensions &rarr; Template Manager &rarr; rt_nebulae_j15 &rarr; Advanced Disable Component : On/Off</strong>.</p>
<p>Additionally, you can disable the entire mainbody area with the <strong>Disable Mainbody</strong> setting.</p>
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

| Option              | Setting       |  
| :------------------ | :------------ |  
| Module Class Suffix |               |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/contenttopa_1.jpeg
[demo3]: assets/contenttopa_2.jpeg
[demo4]: assets/contenttopa_3.jpeg
