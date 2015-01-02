---
title: Iridescent: Recreating the Demo - FP Utility A
description: Your Guide to Recreating Elements of the Iridescent Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/iridescent:Iridescent

---

FP Utility A
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |    Setting     |
| :--------- | :------------- |
| Title      | `FP Utility A` |
| Show Title | Hide           |
| Position   | utility-a      |
| Status     | Published      |
| Access     | Public         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-effect-border">
    <img src="images/rocketlauncher/home/fp-utility/img-01.jpg" alt="image"/>
    <div class="rt-effect-content">
        <h2><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="fp-demo-url"><span>RocketLauncher</span></a></h2>
        <p class="visible-desktop"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="fp-demo-url">Install Iridescent demo on your website or localhost<span class="visible-large"></span></a></p>
    </div>          
</div>
<div class="gantry-width-container">
    <div class="gantry-width-33">
        <a href="https://www.facebook.com/RocketTheme">
            <div class="rt-icon-1">
                <i class="fa fa-facebook fa-3x"></i>
            </div>
        </a>
    </div>
    <div class="gantry-width-33">
        <a href="https://twitter.com/rockettheme">
            <div class="rt-icon-2">
                <i class="fa fa-twitter fa-3x"></i>
            </div>
        </a>
    </div>
    <div class="gantry-width-33">
        <a href="https://plus.google.com/+rockettheme/posts">
            <div class="rt-icon-3">
                <i class="fa fa-google-plus fa-3x"></i>
            </div>
        </a>
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

|        Option       |    Setting     |
| :------------------ | :------------- |
| Module Class Suffix | `fp-utility-a` |

[demo]: assets/demo_7.jpeg
[demo2]: assets/demo_7a.jpeg
[demo3]: assets/demo_7b.jpeg
[demo4]: assets/demo_7c.jpeg