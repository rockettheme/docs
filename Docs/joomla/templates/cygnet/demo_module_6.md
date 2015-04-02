---
title: Cygnet: Recreating the Demo - FP Feature
description: Your Guide to Recreating Elements of the Cygnet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cygnet:Cygnet

---

FP Feature
-----

![Custom HTML](assets/demo_5.jpeg)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![Details](assets/demo_6a.jpeg)

| Option      | Setting      |
| :---------- | :----------  |
| Title       | `FP Feature` |
| Show Title  | Hide         |
| Position    | feature-a    |
| Status      | Published    |
| Access      | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <div class="rt-block-feature">
                    <div class="rt-feature-icon">
                        <i class="fa fa-fw fa-history"></i>
                    </div>
                    <div class="rt-feature-content">
                        <h3>Feature Focus</h3>  
                        <p><span>The Features layout, offers Slideshow and Showcase options, for easy to configure content presentation</span></p>
                    </div>
                    <div class="clear"></div>
                </div>
                <div class="rt-block-feature">
                    <div class="rt-feature-icon">
                        <i class="fa fa-fw fa-shopping-cart"></i>
                    </div>
                    <div class="rt-feature-content">
                        <h3>Tabbed Content</h3> 
                        <p><span>RokSprocket features the Tabs layout, with configurable tab positions and titles with icons or text</span></p>
                    </div>
                    <div class="clear"></div>
                </div>              
            </div>
        </div>  
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <div class="rt-block-feature">
                    <div class="rt-feature-icon">
                        <i class="fa fa-fw fa-institution"></i>
                    </div>
                    <div class="rt-feature-content">
                        <h3>Data Comparison</h3>    
                        <p><span>Utilize the tables layout to present columns of data, such as price comparisons, for your various products</span></p>
                    </div>
                    <div class="clear"></div>
                </div>
                <div class="rt-block-feature">
                    <div class="rt-feature-icon">
                        <i class="fa fa-fw fa-camera-retro"></i>
                    </div>
                    <div class="rt-feature-content">
                        <h3>Photo Integration</h3>  
                        <p><span>In the administrator, there is support for the Media Manager, RokGallery, and custom URL/Path input</span></p>
                    </div>
                    <div class="clear"></div>
                </div>              
            </div>
        </div>                                      
    </div>
</div>

<div class="rt-center rt-feature-promo">
    <p class="rt-text-medium">RokSprocket's custom administrator benefits from compounding filters, intuitive per item controls, and a rich UI to make configuration as user friendly as possible. <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon3">Learn More</a></p>
    <a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Get Started</a>
</div>
~~~

### Basic

![Basic](assets/demo_6b.jpeg)

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![Advanced](assets/demo_6c.jpeg)

| Option              | Setting                    |
| :----------         | :----------                |
| Module Class Suffix | `fp-feature wow slideInUp` |