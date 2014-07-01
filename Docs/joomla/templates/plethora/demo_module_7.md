---
title: Plethora: Recreating the Demo - FP Feature B
description: Your Guide to Recreating Elements of the Plethora Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/plethora:Plethora

---

FP Feature B
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `FP Feature B` |
| Show Title  | Hide           |
| Position    | feature-b      |
| Status      | Published      |
| Access      | Public         |

### Custom Output

~~~ .html
<div class="rt-image-group">
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="images/rocketlauncher/home/fp-feature-b/img-01.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Speed</span>
        </div>
        <div class="rt-image-content">
            <p class="smallmarginbottom">Improve site speed<span class="hidden-tablet"> performance</span></p>
            <span class="rt-text-small"><em>RokBooster</em></span>
        </div>      
    </div>
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="images/rocketlauncher/home/fp-feature-b/img-02.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Search</span>
        </div>      
        <div class="rt-image-content">
            <p class="smallmarginbottom">Ajax <span class="hidden-tablet">powered </span>site and Google search</p> 
            <span class="rt-text-small"><em>RokAjaxSearch</em></span>
        </div>      
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

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `fp-feature-b` |

[demo]: assets/demo_7.jpeg
[demo2]: assets/demo_7a.jpeg
[demo3]: assets/demo_7b.jpeg
[demo4]: assets/demo_7c.jpeg
