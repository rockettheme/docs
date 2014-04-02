---
title: Lexicon: Recreating the Demo - Stay in Touch
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

Stay in Touch
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

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
            <a href="https://www.facebook.com/RocketTheme">Facebook</a>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="https://twitter.com/rockettheme">Twitter</a>
        </div>
    </div>
</div>
<div class="clear medmarginbottom">
    &nbsp;
</div>
<div class="gantry-row">
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="http://www.linkedin.com/in/rockettheme">LinkedIn</a>
        </div>
    </div>
    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <a href="http://www.pinterest.com/rockettheme/">Pinterest</a>
        </div>
    </div>
</div>
<div class="clear">
    &nbsp;
</div>
<p>&nbsp;</p>
<div class="gantry-row">
    <div class="gantry-width-100">
        <div class="gantry-width-spacer">
            <form action="http://feedburner.google.com/fb/a/mailverify" method=
            "post" target="popupwindow">
                <input alt="Your Email" class="inputbox" name="email"
                placeholder="Your Email" type="text"> <input name="uri" type=
                "hidden" value="rocketthemeblog"> <input name="loc" type=
                "hidden" value="en_US"> <input class="readon" name="Submit"
                type="submit" value="Join">
            </form>
        </div>
    </div>
</div>
<div class="clear">
    &nbsp;
</div>
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
