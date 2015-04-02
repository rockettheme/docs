---
title: Cygnet: Recreating the Demo - Extendability
description: Your Guide to Recreating Elements of the Cygnet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cygnet:Cygnet

---

Extendability
-----

![Custom HTML](assets/demo_10.jpeg)

This area of the page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![Details](assets/demo_11a.jpeg)

| Option      | Setting          |
| :---------- | :----------      |
| Title       | `Extendability`  |
| Show Title  | Show             |
| Position    | expandedbottom-a |
| Status      | Published        |
| Access      | Public           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p class="rt-text-medium">RokBooster is a plugin that maximizes your site performance by compressing and consolidating CSS, JavaScript, Fonts, as well as background and inline images, reducing HTTP requests and overall size. <a class="readon3" href="#">Learn More</a></p>

<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50 wow slideInLeft">
            <div class="gantry-width-spacer">
                <div class="rt-image-promo">
                    <div class="rt-image-overlay">
                        <img src="images/rocketlauncher/home/fp-expandedbottom/img-01.jpg" alt="image" />
                    </div>
                    <div class="rt-image-content-wrapper">
                        <div class="rt-label">RokAjaxSearch</div>
                        <div class="rt-image-content rt-image-content-bottom">
                            <h2 class="title">Return real-time site search results<span class="hidden-tablet"> with the AJAX powered module</span></h2>
                            <p>Pageable results appear dynamically in a popup directly below the search box</p>                     
                        </div>
                    </div>          
                </div>              
            </div>
        </div>  
        <div class="gantry-width-50 wow slideInRight">
            <div class="gantry-width-spacer">
                <div class="rt-image-promo">
                    <div class="rt-image-overlay">
                        <img src="images/rocketlauncher/home/fp-expandedbottom/img-02.jpg" alt="image" />
                    </div>
                    <div class="rt-image-content-wrapper">
                        <div class="rt-label">RokBox</div>
                        <div class="rt-image-content rt-image-content-bottom">
                            <h2 class="title">Versatile popup plugin<span class="hidden-tablet"> for displaying images, videos and other HTML elements</span></h2>
                            <p>RokBox benefits from album and auto thumbnail generation support networks</p>                        
                        </div>
                    </div>          
                </div>
            </div>
        </div>          
    </div>
</div>
~~~

### Basic

![Basic](assets/demo_11b.jpeg)

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![Advanced](assets/demo_11c.jpeg)

| Option              | Setting                          |
| :----------         | :----------                      |
| Module Class Suffix | `fp-expandedbottom rt-big-title` |
