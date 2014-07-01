---
title: Plethora: Recreating the Demo - Sample Pages
description: Your Guide to Recreating Elements of the Plethora Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/plethora:Plethora

---

Sample Pages
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `Sample Pages` |
| Show Title  | Show           |
| Position    | footer-b       |
| Status      | Published      |
| Access      | Public         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-container rt-center">
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=119" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-star"></i></span><br />
                <span>About</span>              
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=120" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-users"></i></span><br />
                <span>Team</span>               
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="index.php?option=com_content&amp;view=article&amp;id=9&amp;Itemid=121" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-briefcase"></i></span><br />
                <span>Service</span>                
            </a>
        </div>
    </div>

    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=122" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-list-alt"></i></span><br />
                <span>Pricing</span>                
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="index.php?option=com_content&amp;view=article&amp;id=11&amp;Itemid=123" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-cogs"></i></span><br />
                <span>Work</span>               
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="index.php?option=com_content&amp;view=category&amp;layout=blog&amp;id=13&amp;Itemid=124" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-file-text"></i></span><br />
                <span>Blog</span>               
            </a>
        </div>
    </div>

    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="index.php?option=com_content&amp;view=article&amp;id=12&amp;Itemid=125" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-comments"></i></span><br />
                <span>FAQ</span>                
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="index.php?option=com_contact&amp;view=contact&amp;id=1&amp;Itemid=126" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-ticket"></i></span><br />
                <span>Contact</span>                
            </a>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <a href="index.php?Itemid=404-error" class="rt-icon-item">
                <span class="rt-icon-large"><i class="fa fa-chain-broken"></i></span><br />
                <span>Error</span>              
            </a>
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

| Option              | Setting              |
| :----------         | :----------          |
| Module Class Suffix | `title1 fp-footer-b` |

[demo]: assets/demo_14.jpeg
[demo2]: assets/demo_14a.jpeg
[demo3]: assets/demo_14b.jpeg
[demo4]: assets/demo_14c.jpeg
