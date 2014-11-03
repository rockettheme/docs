---
title: Ricochet: Recreating the Demo - FP Feature
description: Your Guide to Recreating Elements of the Ricochet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ricochet:Ricochet

---

FP Feature
-----

![](assets/demo_2.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_2a.jpeg)

|   Option   |   Setting    |
| :--------- | :----------- |
| Title      | `FP Feature` |
| Show Title | Hide         |
| Position   | feature-a    |
| Status     | Published    |
| Access     | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-square-set">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="rt-square-1">
                <div class="gantry-width-spacer">
                    <h2>A Slider or Fixed Side Position for <span class="hidden-tablet">Displaying </span>Extra Content</h2>
                    <ul class="rt-tags">
                        <li>Fixed</li>
                        <li>Dynamic</li>
                    </ul>
                    <p class="smallmarginbottom">An extra module position, outside of the main structure, configurable to be either fixed or dynamically toggled.</p>
                    <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon2">Read More</a>               
                </div>
            </div>
            <div class="rt-image">
                <img src="images/rocketlauncher/home/fp-feature/img-01.jpg" alt="image" />
            </div>
        </div>
        <div class="gantry-width-33">
            <div class="rt-square-2">
                <div class="gantry-width-spacer">
                    <h2>Powered by the Versatile Gantry Framework</h2>
                    <ul class="rt-tags">
                        <li>Power</li>
                        <li>Adaptable</li>
                    </ul>                   
                    <p class="smallmarginbottom">As a core framework, Gantry sits at the center of Ricochet, providing a range of standardized features and capabilities.</p>
                    <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon2">Read More</a>   
                </div>  
            </div>
            <div class="rt-image">
                <img src="images/rocketlauncher/home/fp-feature/img-02.jpg" alt="image" />
            </div>
        </div>
        <div class="gantry-width-33">
            <div class="rt-square-3">
                <div class="gantry-width-spacer">
                    <h2>A Sophisticated CSS Dropdown Menu<span class="hidden-tablet"> with Advanced Features</span></h2>
                    <ul class="rt-tags">
                        <li>Columns</li>
                        <li>Positions</li>
                    </ul>                   
                    <p class="smallmarginbottom">The menu has support for inline modules and positions, inline icons and subtext, alongside many other configurable options.</p>
                    <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=115" class="readon2">Read More</a>
                </div>  
            </div>
            <div class="rt-image">
                <img src="images/rocketlauncher/home/fp-feature/img-03.jpg" alt="image" />
            </div>
        </div>      
    </div>  
</div>
~~~

### Basic

![](assets/demo_2b.jpeg)

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![](assets/demo_2c.jpeg)

|        Option       |   Setting    |
| :------------------ | :----------- |
| Module Class Suffix | `fp-feature` |

[demo]: assets/demo_2.jpg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/
