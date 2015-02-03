---
title: Sirocco: Recreating the Demo - Present  
description: Your Guide to Recreating Elements of the Sirocco Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/sirocco:Sirocco

---

Present
-----

![](assets/demo_7.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_7a.jpeg)

|   Option   |   Setting    |
| :--------- | :----------- |
| Title      | `Present`    |
| Show Title | Show         |
| Position   | mainbottom-a |
| Status     | Published    |
| Access     | Public       |

### Custom Output

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <div class="rt-image-promo">
                    <div class="rt-image-overlay">
                        <img src="images/rocketlauncher/home/fp-mainbottom/img-01.jpg" alt="image" />
                    </div>
                    <div class="rt-image-content-wrapper">
                        <div class="rt-image-content">
                            <h2 class="title">Table Display with <div>Image Support</div></h2>
                            <span class="rt-title-tag">#tabulation</span>       
                            <span class="rt-image-alt"><img src="images/rocketlauncher/home/fp-mainbottom/img-03.jpg" alt="image"></span>               
                        </div>
                    </div>          
                </div>
            </div>
        </div>  
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <div class="rt-image-promo">
                    <div class="rt-image-overlay">
                        <img src="images/rocketlauncher/home/fp-mainbottom/img-02.jpg" alt="image" />
                    </div>
                    <div class="rt-image-content-wrapper">
                        <div class="rt-image-content">
                            <h2 class="title">Quote Balloons for <div>Testimonials</div></h2>
                            <span class="rt-title-tag">#citation</span>     
                            <span class="rt-image-alt"><img src="images/rocketlauncher/home/fp-mainbottom/img-04.jpg" alt="image"></span>                   
                        </div>
                    </div>          
                </div>
            </div>
        </div>          
    </div>
</div>
~~~

### Basic

![](assets/demo_7b.jpeg)

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_7c.jpeg)

|        Option       |              Setting               |
| :------------------ | :--------------------------------- |
| Module Class Suffix | `fp-mainbottom rt-title-uppercase` |
