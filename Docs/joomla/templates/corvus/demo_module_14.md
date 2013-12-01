---
title: Corvus: Recreating the Demo - FP Footer Social Button
description: Your Guide to Recreating Elements of the Corvus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

FP Footer Social Button
----
![][demo]

:   1. **mod_custom** [69%, 17%, se]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                |  
| :--------- | :----------------------------------------------------- |  
| Title      | `Popular [span class="hidden-tablet"]Templates[/span]` |  
| Show Title | Hide                                                   |  
| Position   | footer-c                                            |  
| Status     | Published                                              |  
| Language   | All                                                    |  
| Note       | Blank                                                  |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-social-buttons">
  <a href="http://www.facebook.com/RocketTheme" class="social-button rt-social-button-1">
    <span class="icon-facebook"></span>
    <span class="social-button-text">Facebook</span>
  </a>
  
  <a href="https://twitter.com/rockettheme" class="social-button rt-social-button-2">
    <span class="icon-twitter"></span>
    <span class="social-button-text">Twitter</span>
  </a>
  
  <a href="https://plus.google.com/114430407008695950828/posts" class="social-button rt-social-button-3">
    <span class="icon-google-plus"></span>
    <span class="social-button-text">gPlus</span>
  </a>
  
  <a href="http://www.rockettheme.com/blog?format=feed&amp;type=rss" class="social-button rt-social-button-4">
    <span class="icon-rss"></span>
    <span class="social-button-text">rss</span>
  </a>
  <div class="clear"></div>
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
| Module Class Suffix | `fp-footer-social-buttons` |  

[demo]: assets/demo_13.jpeg
[demo2]: assets/social_1.jpeg
[demo3]: assets/social_2.jpeg
[demo4]: assets/social_3.jpeg