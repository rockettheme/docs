---
title: Plethora: Recreating the Demo - Top Galleries
description: Your Guide to Recreating Elements of the Plethora Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/plethora:Plethora

---

Top Galleries
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting         |
| :---------- | :----------     |
| Title       | `Top Galleries` |
| Show Title  | Show            |
| Position    | maintop-b       |
| Status      | Published       |
| Access      | Public          |

### Custom Output

~~~ .html
<div class="rt-image-group">
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="images/rocketlauncher/home/fp-maintop-b/img-01.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Error</span>
        </div>
        <div class="rt-image-content">
            <p class="smallmarginbottom">Custom 404 error page override</p>
            <span class="rt-text-small"><em>error.php</em></span>
        </div>      
    </div>
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="images/rocketlauncher/home/fp-maintop-b/img-02.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Offline</span>
        </div>      
        <div class="rt-image-content">
            <p class="smallmarginbottom">Custom offline page override</p>   
            <span class="rt-text-small"><em>offline.php</em></span>
        </div>      
    </div>
    <div class="rt-image-block">
        <div class="rt-image-item">
            <img src="images/rocketlauncher/home/fp-maintop-b/img-03.jpg" alt="image" />
        </div>
        <div class="rt-image-tag">
            <span>Coming Soon</span>
        </div>          
        <div class="rt-image-content">
            <p class="smallmarginbottom">Unique coming soon offline page</p>
            <span class="rt-text-small"><em>comingsoon.php</em></span>  
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

| Option              | Setting               |
| :----------         | :----------           |
| Module Class Suffix | `title1 fp-maintop-b` |

[demo]: assets/demo_10.jpeg
[demo2]: assets/demo_10a.jpeg
[demo3]: assets/demo_10b.jpeg
[demo4]: assets/demo_10c.jpeg
