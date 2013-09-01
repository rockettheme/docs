---
title: Cerulean: Recreating the Demo - Contact Us
description: Your Guide to Recreating Elements of the Cerulean Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cerulean:Cerulean

---

Contact Us
----
![][demo]

:   1. **mod_custom** [20%, 73%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                          |  
| :--------- | :--------------------------------------------------------------- |  
| Title      | `Contact Us.  [span class="icon-chevron-down rt-teaser"][/span]` |  
| Show Title | Show                                                             |  
| Position   | footer-c                                                         |  
| Status     | Published                                                        |  
| Language   | All                                                              |  
| Note       | Blank                                                            |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-10 gantry-width-block largemarginright">
    <h4 class="smallmargintop"><span class="icon-phone"></span></h4>
</div>
<div class="gantry-width-80 gantry-width-block">
    <strong>+1 (555) 555-555-5555</strong><br />
    <small>+1 (555) 555-555-5556</small>
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block largemarginright">
    <h4 class="smallmargintop"><span class="icon-home"></span></h4>
</div>
<div class="gantry-width-80 gantry-width-block">
    <span>123 Joomla! Boulevard</span><br />
      <small>Seattle, WA 00000, USA</small> 
</div>

<div class="clear medmarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block largemarginright">
    <span class="icon-envelope-alt"></span>
</div>
<div class="gantry-width-80 gantry-width-block">
    <span>noreply/@domain.com</span>
</div>

<div class="clear largemarginbottom">&nbsp;</div>

<div class="gantry-width-10 gantry-width-block largemarginright">
    <h4 class="smallmargintop"><span class="icon-random"></span></h4>
</div>
<div class="gantry-width-80 gantry-width-block">

    <div class="rt-social-buttons">
        <a class="social-button rt-facebook-btn" href="http://www.facebook.com/RocketTheme"><span></span></a>
        <a class="social-button rt-twitter-btn" href="https://twitter.com/rockettheme"><span></span></a>
    	<a class="social-button rt-google-btn" href="https://plus.google.com/114430407008695950828/posts"><span></span></a>
		<a class="social-button rt-rss-btn" href="http://www.rockettheme.com/blog?format=feed&amp;type=rss"><span></span></a>
	</div>
</div>	

<div class="clear"></div>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                                                                 |  
| :------------------ | :---------------------------------------------------------------------- |  
| Module Class Suffix | `nomarginbottom nopaddingbottom nomargintop medpaddingtop hidden-phone` |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/contact_1.jpeg
[demo3]: assets/contact_2.jpeg
[demo4]: assets/contact_3.jpeg