---
title: Sirocco: Recreating the Demo - Interact
description: Your Guide to Recreating Elements of the Sirocco Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/sirocco:Sirocco

---

Interact
-----

![](assets/demo_6.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_6a.jpeg)

|   Option   |     Setting      |
| :--------- | :--------------- |
| Title      | `Interact`       |
| Show Title | Show             |
| Position   | expandedbottom-a |
| Status     | Published        |
| Access     | Public           |

### Custom Output

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <div class="gantry-width-20">
                    <img src="images/rocketlauncher/home/fp-expandedbottom/img-01.jpg" alt="image" />
                </div>
                <div class="gantry-width-80">
                    <div class="rt-box rt-box1">
                        <h2>Slideshow Layout for Large Images &amp; Featured Text</h2>
                        <span class="rt-title-tag">Feature Layout</span>
                        <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon">Read More</a>                        
                    </div>
                </div>
            </div>
        </div>  
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <div class="gantry-width-50">
                    <div class="rt-box rt-box4">
                        <h2>Accordion or Static List<span class="hidden-tablet"> Display Mode</span></h2>
                        <span class="rt-title-tag">Lists Layout</span>
                        <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon">Read More</a>                        
                    </div>
                </div>
                <div class="gantry-width-50">
                    <div class="rt-box rt-box2">
                        <h2><span>News Ticker for <span class="visible-large">Short </span><span class="hidden-tablet">Content</span> Snippets</span></h2>
                        <span class="rt-title-tag">Headlines Layout</span>
                        <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon">Read More</a>                        
                    </div>
                </div>
            </div>
        </div>          
    </div>
</div>
~~~

### Basic

![](assets/demo_6b.jpeg)

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_6c.jpeg)

|        Option       |                Setting                 |
| :------------------ | :------------------------------------- |
| Module Class Suffix | `fp-expandedbottom rt-title-uppercase` |
