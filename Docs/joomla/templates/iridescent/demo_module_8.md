---
title: Iridescent: Recreating the Demo - FP Utility B
description: Your Guide to Recreating Elements of the Iridescent Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/iridescent:Iridescent

---

FP Utility B
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |    Setting     |
| :--------- | :------------- |
| Title      | `FP Utility B` |
| Show Title | Hide           |
| Position   | utility-b      |
| Status     | Published      |
| Access     | Public         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-container">
    <div class="gantry-width-50">
        <div class="rt-effect-slide rt-effect-slide-top">
            <img src="images/rocketlauncher/home/fp-utility/img-02.jpg" alt="image"/>
            <div class="rt-effect-slide-content">
                <h2 class="rt-uppercase"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="fp-demo-url">Responsive<br /> Design</a></h2>
                <p><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="fp-demo-url">Adapts to any device</a></p>
            </div>          
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="rt-effect-slide rt-effect-slide-top">
            <img src="images/rocketlauncher/home/fp-utility/img-03.jpg" alt="image"/>
            <div class="rt-effect-slide-content">
                <h2 class="rt-uppercase"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="fp-demo-url">Presets</a></h2>
                <p><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="fp-demo-url">Six elegant styles</a></p>
            </div>          
        </div>
        <div class="rt-effect-slide rt-effect-slide-top">
            <img src="images/rocketlauncher/home/fp-utility/img-04.jpg" alt="image"/>
            <div class="rt-effect-slide-content">
                <h2 class="rt-uppercase"><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114" class="fp-demo-url">Typography</a></h2>
                <p><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114" class="fp-demo-url">Individualize <span class="hidden-tablet">your</span> content</a></p>
            </div>          
        </div>      
    </div>      
</div>
~~~

### Basic

![][demo3]

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

|        Option       |    Setting     |
| :------------------ | :------------- |
| Module Class Suffix | `fp-utility-b` |

[demo]: assets/demo_8.jpeg
[demo2]: assets/demo_8a.jpeg
[demo3]: assets/demo_8b.jpeg
[demo4]: assets/demo_8c.jpeg