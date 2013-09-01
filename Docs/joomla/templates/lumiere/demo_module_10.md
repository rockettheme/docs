---
title: Lumiere: Recreating the Demo - Follow Us
description: Your Guide to Recreating Elements of the Lumiere Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lumiere:Lumiere

---

Follow Us
----
![][demo]

:   1. **Menu** [62%, 71%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting     |  
| :--------- | :---------- |  
| Title      | `Follow Us` |  
| Show Title | Hide        |  
| Position   | copyright-c |  
| Status     | Published   |  
| Language   | All         |  
| Note       | Blank       |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-social-buttons">
	<span class="boldfont largepaddingright">Follow Us</span>
	<a href="http://www.facebook.com/RocketTheme" class="social-button rt-facebook-btn"><span></span></a>
	<a href="https://twitter.com/rockettheme" class="social-button rt-twitter-btn"><span></span></a>
	<a href="https://plus.google.com/114430407008695950828/posts" class="social-button rt-google-btn"><span></span></a>
	<a href="http://www.rockettheme.com/blog?format=feed&amp;type=rss" class="social-button rt-rss-btn"><span></span></a>
	<div class="clear"></div>
</div>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/follow_1.jpeg
[demo3]: assets/follow_2.jpeg
[demo4]: assets/follow_3.jpeg