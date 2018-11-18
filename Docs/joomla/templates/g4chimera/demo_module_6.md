---
title: Chimera: Recreating the Demo - FP ExpandedTop B
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

FP ExpandedTop B
-----


![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `FP ExpandedTop B` |  
| Show Title | Hide               |  
| Position   | expandedtop-b      |  
| Status     | Published          |  
| Access     | Public             |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div>Initial Conceptual Design</div>
<div class="progress">
  <div class="progress-bar progress-bar-default" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%">
    <span class="sr-only">80%</span>
  </div>
</div>

<div>Wireframing and Structure</div>
<div class="progress">
  <div class="progress-bar progress-bar-default" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width: 50%">
    <span class="sr-only">50%</span>
  </div>
</div>

<div>User Interface Implementation</div>
<div class="progress">
  <div class="progress-bar progress-bar-default" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
    <span class="sr-only">100%</span>
  </div>
</div>

<div>Animation and Polish</div>
<div class="progress">
  <div class="progress-bar progress-bar-default" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">
    <span class="sr-only">75%</span>
  </div>
</div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting              |
| :----------         | :----------          |
| Module Class Suffix |                      |

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg
