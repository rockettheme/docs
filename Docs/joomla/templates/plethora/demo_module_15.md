---
title: Plethora: Recreating the Demo - More Info
description: Your Guide to Recreating Elements of the Plethora Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/plethora:Plethora

---

More Info
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `More Info` |
| Show Title  | Show        |
| Position    | footer-c    |
| Status      | Published   |
| Access      | Public      |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>Enter your email address below and subscribe to our newsletter. We hate spam as much as you do.</p>
<form class="rt-form-horizontal" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify">
    <input type="text" name="email" class="inputbox" placeholder="Your Email" />
    <input type="hidden" name="uri" value="rocketthemeblog" />
    <input type="hidden" value="en_US" name="loc" />
    <input type="submit" value="Join" class="readon" name="Submit" />
</form>

<div class="gantry-width-container">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer nomarginleft">
            <div class="module-title largemargintop">
                <h2 class="title"><span>Quick Links</span></h2>
            </div>
            <ul class="rt-footer-menu list-group">
                <li><i class="fa fa-star fa-fw"></i><a href="#"> About</a></li>
                <li><i class="fa fa-edit fa-fw"></i><a href="#"> Docs</a></li>
                <li><i class="fa fa-cog fa-fw"></i><a href="#"> Help</a></li>
                <li><i class="fa fa-comment fa-fw"></i><a href="#"> Contact</a></li>
            </ul>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <div class="module-title largemargintop">
                <h2 class="title"><span>Elsewhere</span></h2>
            </div>
            <ul class="rt-footer-menu list-group">
                <li><i class="fa fa-twitter fa-fw"></i><a href="#"> Twitter</a></li>
                <li><i class="fa fa-facebook fa-fw"></i><a href="#"> Facebook</a></li>
                <li><i class="fa fa-google-plus fa-fw"></i><a href="#"> Google Plus</a></li>
                <li><i class="fa fa-rss fa-fw"></i><a href="#"> RSS</a></li>
            </ul>
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
| Module Class Suffix | `title1 fp-footer-c` |

[demo]: assets/demo_15.jpeg
[demo2]: assets/demo_15a.jpeg
[demo3]: assets/demo_15b.jpeg
[demo4]: assets/demo_15c.jpeg
