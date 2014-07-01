---
title: Plethora: Recreating the Demo - FP Feature C
description: Your Guide to Recreating Elements of the Plethora Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/plethora:Plethora

---

FP Feature C
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `FP Feature C` |
| Show Title  | hide           |
| Position    | feature-c      |
| Status      | Published      |
| Access      | Public         |

### Custom Output

~~~ .html
<div class="rt-image-group">
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="images/rocketlauncher/home/fp-feature-c/img-01.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Layouts</span>
        </div>
        <div class="rt-image-content">
            <div class="rt-image-title">
                <span class="hidden-tablet">Multiple RokSprocket layout and theme options.</span>
                <span class="visible-tablet">Layouts and themes.</span>
            </div>      
            <div class="rt-image-desc">
                <p>Several content display options to <span class="hidden-tablet">choose and </span>configure.</p>
                <a href="#">Read the whole story <i class="fa fa-angle-double-right"></i></a>
            </div>              
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
| Module Class Suffix | `fp-feature-c` |

[demo]: assets/demo_8.jpeg
[demo2]: assets/demo_8a.jpeg
[demo3]: assets/demo_8b.jpeg
[demo4]: assets/demo_8c.jpeg
