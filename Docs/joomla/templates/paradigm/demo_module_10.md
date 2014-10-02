---
title: Paradigm: Recreating the Demo - Join Our Newsletter
description: Your Guide to Recreating Elements of the Paradigm Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradigm:Paradigm

---

Join Our Newsletter
-----

![][demo]

:	1. **mod_custom** [30%, 6%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                                                               |  
| :--------- | :-------------------------------------------------------------------- |  
| Title      | `[span class="hidden-tablet hidden-phone"]Join Our [/span]Newsletter` |  
| Show Title | Show                                                                  |  
| Position   | footer-a                                                              |  
| Status     | Published                                                             |  
| Access     | Public                                                                |  
| Language   | All                                                                   |  
| Note       | Blank                                                                 |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p><span>Updates, upcoming themes, and <span class="visible-large">great </span>deals!</span></p>
<form class="fp-footer-form" action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
	<input type="text" placeholder="Your Email" alt="Your Email" class="inputbox" name="email">
	<input type="hidden" value="rocketthemeblog" name="uri" />
	<input type="hidden" name="loc" value="en_US" />
	<input type="submit" name="Submit" class="readon" value="Join" />
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

[demo]: assets/demo_9.jpeg
[demo2]: assets/join_1.jpeg
[demo3]: assets/join_2.jpeg
[demo4]: assets/join_3.jpeg