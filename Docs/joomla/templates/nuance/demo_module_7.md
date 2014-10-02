---
title: Nuance: Recreating the Demo - FP MainBottom
description: Your Guide to Recreating Elements of the Nuance Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nuance:Nuance

---

FP MainBottom
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting         |
| :---------- | :----------     |
| Title       | `FP MainBottom` |
| Show Title  | Hide            |
| Position    | mainbottom-a    |
| Status      | Published       |
| Access      | Public          |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-row rt-center">
    <div class="gantry-width-container">
        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <i class="fa fa-coffee fp-mainbottom-icon"></i><br />
                <h3 class="fp-mainbottom-title">06</h3>
                <span class="fp-mainbottom-text">Style Variations</span>
            </div>
        </div>
        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <i class="fa fa-thumbs-up fp-mainbottom-icon"></i><br />
                <h3 class="fp-mainbottom-title">85+</h3>
                <span class="fp-mainbottom-text"><span class="hidden-tablet">Module </span>Positions</span>         
            </div>
        </div>
        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <i class="fa fa-plane fp-mainbottom-icon"></i><br />
                <h3 class="fp-mainbottom-title">66</h3>
                <span class="fp-mainbottom-text">Module Suffixes</span>         
            </div>
        </div>
        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <i class="fa fa-camera-retro fp-mainbottom-icon"></i><br />
                <h3 class="fp-mainbottom-title">2.5-3.3</h3>
                <span class="fp-mainbottom-text">Compatible</span>          
            </div>
        </div>
        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <i class="fa fa-calendar fp-mainbottom-icon"></i><br />
                <h3 class="fp-mainbottom-title">02</h3>
                <span class="fp-mainbottom-text">Menu Options</span>            
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

| Option              | Setting         |
| :----------         | :----------     |
| Module Class Suffix | `fp-mainbottom` |

[demo]: assets/demo_7.jpeg
[demo2]: assets/demo_7a.jpeg
[demo3]: assets/demo_7b.jpeg
[demo4]: assets/demo_7c.jpeg
