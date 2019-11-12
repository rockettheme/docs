---
title: Audacity: Recreating the Demo - Connect
description: Your Guide to Recreating Elements of the Audacity Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/g4audacity:Audacity

---

Connect
-----

![](assets/demo_18.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_18a.jpeg)

| Option     | Setting   |
| :-----     | :-----    |
| Title      | `Connect` |
| Show Title | Show      |
| Position   | footer-f  |
| Status     | Published |
| Access     | Public    |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-social-buttons">
    <a href="#" class="social-button">
        <span class="fa fa-twitter"></span>
    </a>        
    <a href="#" class="social-button">
        <span class="fa fa-facebook"></span>
    </a>        
    <a href="#" class="social-button">
        <span class="fa fa-google-plus"></span>
    </a>        
    <a href="#" class="social-button">
        <span class="fa fa-pinterest"></span>
    </a>
    <a href="#" class="social-button">
        <span class="fa fa-linkedin"></span>
    </a>        
    <a href="#" class="social-button">
        <span class="fa fa-tumblr"></span>
    </a>        
    <a href="#" class="social-button">
        <span class="fa fa-instagram"></span>
    </a>        
    <a href="#" class="social-button">
        <span class="fa fa-flickr"></span>
    </a>        
    <div class="clear"></div>
</div>
~~~

### Basic

![](assets/demo_18b.jpeg)

| Option                    | Setting |
| :-----                    | :-----  |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_18c.jpeg)

| Option              | Setting       |
| :-----              | :-----        |
| Module Class Suffix | `fp-footer-f` |
