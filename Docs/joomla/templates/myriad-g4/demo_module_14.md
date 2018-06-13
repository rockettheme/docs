---
title: Myriad: Recreating the Demo - Stay Connected
description: Your Guide to Recreating Elements of the Myriad Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

Stay Connected
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |     Setting      |
| :--------- | :--------------- |
| Title      | `Stay Connected` |
| Show Title | Show             |
| Position   | bottom-c         |
| Status     | Published        |
| Access     | Public           |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <a href="https://www.facebook.com/RocketTheme"><i class="fa fa-facebook fa-fw"></i> <span>Facebook</span></a>
            </div>
        </div>
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <a href="https://twitter.com/rockettheme"><i class="fa fa-twitter fa-fw"></i> <span>Twitter</span></a>
            </div>
        </div>      
    </div>
</div>

<div class="clear"></div>

<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <a href="https://plus.google.com/+rockettheme"><i class="fa fa-google-plus fa-fw"></i> <span>Google+</span></a>
            </div>
        </div>
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <a href="http://www.rockettheme.com/product-updates?rss"><i class="fa fa-rss fa-fw"></i> <span>RSS</span></a>
            </div>
        </div>      
    </div>
</div>

<div class="clear"></div>

<form class="fp-bottom-form" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify">
    <input type="text" name="email" class="inputbox" placeholder="Your Email" />
    <input type="hidden" name="uri" value="rocketthemeblog" />
    <input type="hidden" value="en_US" name="loc" />
    <input type="submit" value="Join" class="readon" name="Submit" />
</form>
~~~

### Basic

![][demo3]

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

|        Option       |                             Setting                             |
| :------------------ | :-------------------------------------------------------------- |
| Module Class Suffix | `fp-bottom-c rt-modtitle-uppercase hidden-phone wow fadeInDown` |

[demo]: assets/demo_15.jpeg
[demo2]: assets/demo_14a.jpeg
[demo3]: assets/demo_14b.jpeg
[demo4]: assets/demo_14c.jpeg
