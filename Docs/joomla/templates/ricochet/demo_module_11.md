---
title: Ricochet: Recreating the Demo - FP Bottom
description: Your Guide to Recreating Elements of the Ricochet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ricochet:Ricochet

---

FP Bottom
-----

![](assets/demo_11.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_11a.jpeg)

|   Option   |   Setting   |
| :--------- | :---------- |
| Title      | `FP Bottom` |
| Show Title | Hide        |
| Position   | bottom-a    |
| Status     | Published   |
| Access     | Public      |

### Custom Output

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="rt-image-promo">
                <div class="rt-image-overlay">
                    <img src="images/rocketlauncher/home/fp-bottom/img-01.jpg" alt="image" />
                </div>
                <div class="rt-image-content-wrapper">
                    <div class="rt-image-content">
                        <span class="rt-label">Anticipation</span>
                        <h2 class="title">Ricochet supports a simple Coming Soon page<span class="hidden-tablet"> with time counter</span></h2>
                        <ul class="rt-tags">
                            <li>Excitement</li>
                            <li>Suspense</li>
                        </ul>                       
                    </div>
                </div>          
            </div>
        </div>  
        <div class="gantry-width-50">
            <div class="rt-image-promo">
                <div class="rt-image-overlay">
                    <img src="images/rocketlauncher/home/fp-bottom/img-02.jpg" alt="image" />
                </div>
                <div class="rt-image-content-wrapper">
                    <div class="rt-image-content">
                        <span class="rt-label">Malfunction</span>
                        <h2 class="title">Custom 404 page for Ricochet when page is not found</h2>
                        <ul class="rt-tags">
                            <li>Error</li>
                            <li>Glitch</li>
                        </ul>                       
                    </div>
                </div>          
            </div>
        </div>          
    </div>
</div>
~~~

### Basic

![](assets/demo_11b.jpeg)

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![](assets/demo_11c.jpeg)

|        Option       |   Setting   |
| :------------------ | :---------- |
| Module Class Suffix | `fp-bottom` |
