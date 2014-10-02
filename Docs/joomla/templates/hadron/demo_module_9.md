---
title: Hadron: Recreating the Demo - FP Newsletter
description: Your Guide to Recreating Elements of the Hadron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hadron:Hadron

---

FP Newsletter
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting         |  
| :--------- | :-------------- |  
| Title      | `FP Newsletter` |  
| Show Title | Hide            |  
| Position   | footer-a        |  
| Status     | Published       |  
| Access     | Public          |  
| Language   | All             |  
| Note       | Blank           |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p class="rt-small-text">Hadron is available as part of the Club Subscription</p>
<form class="fp-newsletter-form" action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
    <input type="text" placeholder="Your email address here ..." class="inputbox" name="email">
    <input type="hidden" value="rocketthemeblog" name="uri" />
    <input type="hidden" name="loc" value="en_US" />
    <input type="submit" name="Submit" class="readon" value="Subscribe" />
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

| Option              | Setting                    |  
| :------------------ | :------------------------- |  
| Module Class Suffix | `fp-newsletter rt-center`  |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/newsletter_1.jpeg
[demo3]: assets/newsletter_2.jpeg
[demo4]: assets/newsletter_3.jpeg