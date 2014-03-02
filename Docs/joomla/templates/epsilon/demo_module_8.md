---
title: Epsilon: Recreating the Demo - Join Our Newsletter
description: Your Guide to Recreating Elements of the Epsilon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/epsilon:Epsilon

---

Join Our Newsletter
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting               |  
| :--------- | :-------------------- |  
| Title      | `Join Our Newsletter` |  
| Show Title | Show                  |  
| Position   | footer-a              |  
| Status     | Published             |  
| Access     | Public                |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p class="rt-small-text">Sign up to receive information about updates, upcoming themes, and great deals!</p>
<form onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify" class="fp-newsletter-form">
    <input type="text" name="email" class="inputbox" placeholder="your@email.com" />
    <input type="hidden" name="uri" value="rocketthemeblog" />
    <input type="hidden" value="en_US" name="loc" />
    <input type="submit" value="Join" class="button" name="Submit" />
</form>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/demo_8a.jpeg
[demo3]: assets/demo_8b.jpeg
[demo4]: assets/demo_8c.jpeg
