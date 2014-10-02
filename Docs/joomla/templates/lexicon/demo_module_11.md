---
title: Lexicon: Recreating the Demo - Stay in Touch
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

Stay in Touch
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `Stay in Touch`    |  
| Show Title | Show               |  
| Position   | footer-c           |  
| Status     | Published          |  
| Access     | Public             |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="https://www.facebook.com/RocketTheme"><span class="icon-facebook-sign"></span> <span>Facebook</span></a>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="https://twitter.com/rockettheme"><span class="icon-twitter-sign"></span> <span>Twitter</span></a>
        </div>
    </div>
</div>

<div class="clear medmarginbottom"></div>

<div class="gantry-row">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="http://www.linkedin.com/in/rockettheme"><span class="icon-linkedin-sign"></span> <span>LinkedIn</span></a>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="http://www.pinterest.com/rockettheme/"><span class="icon-pinterest-sign"></span> <span>Pinterest</span></a>
        </div>
    </div>
</div>

<div class="clear"></div> <br />

<div class="gantry-row">
    <div class="gantry-width-100">
        <div class="gantry-width-spacer">
            <form action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
                <input type="text" placeholder="Your Email" alt="Your Email" class="inputbox" name="email">
                <input type="hidden" value="rocketthemeblog" name="uri" />
                <input type="hidden" name="loc" value="en_US" />
                <input type="submit" name="Submit" class="readon" value="Join" />
            </form>
        </div>
    </div>
</div>
<div class="clear"></div>       
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                    |  
| :------------------ | :------------------------- |  
| Module Class Suffix | `fp-footer-c hidden-phone` |  

[demo]: assets/demo_11.jpeg
[demo2]: assets/demo_11a.jpeg
[demo3]: assets/demo_11b.jpeg
[demo4]: assets/demo_11c.jpeg
