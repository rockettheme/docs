---
title: Ricochet: Recreating the Demo - FP Footer B
description: Your Guide to Recreating Elements of the Ricochet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ricochet:Ricochet

---

FP Footer B
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |    Setting    |
| :--------- | :------------ |
| Title      | `FP Footer B` |
| Show Title | Hide          |
| Position   | footer-b      |
| Status     | Published     |
| Access     | Public        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-container">
    <div class="gantry-width-25">
        <div class="rt-square-1">
            <div class="gantry-width-spacer">
                <h5>About</h5>
                <ul class="rt-noliststyle">
                    <li><a href="http://www.rockettheme.com/blog">Blog</a></li>
                    <li><a href="http://www.rockettheme.com/the-team">The Team</a></li>
                    <li><a href="http://www.rockettheme.com/promotions">Promotions</a></li>
                    <li><a href="http://www.shareasale.com/shareasale.cfm?merchantID=30300">Affiliate</a></li>
                </ul>   
                <h5 class="lmedmargintop largepaddingtop">Help</h5>
                <ul class="rt-noliststyle">
                    <li><a href="http://www.rockettheme.com/contact-us">Email</a></li>
                    <li><a href="http://www.rockettheme.com/purchase-premier-support">Premier Support</a></li>
                </ul>                       
            </div>
        </div>
    </div>
    <div class="gantry-width-25">
        <div class="rt-square-1">
            <div class="gantry-width-spacer">
                <h5>Features</h5>
                <ul class="rt-noliststyle">
                <li><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Overview</a></li>
                    <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=112">Module Positions</a></li>
                    <li><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=113">Module Variations</a></li>
                    <li><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114">Typography</a></li>
                    <li><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=115">Menu Options</a></li>
                </ul>       
            </div>
        </div>
    </div>
    <div class="gantry-width-25">
        <div class="rt-square-1">
            <div class="gantry-width-spacer">
                <h5>Pages</h5>
                <ul class="rt-noliststyle">
                    <li><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=118">Overview</a></li>
                    <li><a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=119">About Us</a></li>
                    <li><a href="index.php?option=com_content&amp;view=article&amp;id=9&amp;Itemid=121">Services</a></li>
                    <li><a href="index.php?option=com_content&amp;view=article&amp;id=11&amp;Itemid=123">Portfolio</a></li>
                    <li><a href="index.php?option=com_contact&amp;view=contact&amp;id=1&amp;Itemid=126">Contact Us</a></li>
                </ul>       
            </div>
        </div>
    </div>  
    <div class="gantry-width-25">
        <div class="rt-square-1">
            <div class="gantry-width-spacer">
                <h5>Social</h5>
                <ul class="rt-noliststyle">
                    <li><a href="https://www.facebook.com/RocketTheme">Facebook</a></li>
                    <li><a href="https://twitter.com/rockettheme">Twitter</a></li>
                    <li><a href="https://plus.google.com/+rockettheme/posts">Google+</a></li>
                    <li><a href="http://www.rockettheme.com/product-updates?rss">RSS</a></li>
                </ul>       
                <h5 class="lmedmargintop largepaddingtop">Extensions</h5>
                <ul class="rt-noliststyle">
                    <li><a href="http://www.rockettheme.com/joomla/extensions/roksprocket">RokSprocket</a></li>
                    <li><a href="http://www.rockettheme.com/joomla/extensions/rokbooster">RokBooster</a></li>
                </ul>   
            </div>
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

|        Option       |          Setting           |
| :------------------ | :------------------------- |
| Module Class Suffix | `fp-footer-b hidden-phone` |

[demo]: assets/demo_13.jpeg
[demo2]: assets/demo_13a.jpeg
[demo3]: assets/demo_13b.jpeg
[demo4]: assets/demo_13c.jpeg
