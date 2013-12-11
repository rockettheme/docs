---
title: Hexeris: Recreating the Demo - Follow Us
description: Your Guide to Recreating Elements of the Hexeris Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hexeris:Hexeris

---

Follow Us
-----
![][demo]

We used a **mod_custom** module to make up the content in the **footer-a** position of the front page. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | Follow Us          |  
| Show Title        | Show               |  
| Position          | footer-b           |  
| Status            | Published          |  
| Access            | Public             |   
| Language          | All                |  
| Note              | Blank              |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-social-buttons">
  <a class="social-button rt-facebook-btn" href="http://www.facebook.com/RocketTheme"><span></span></a>
  <a class="social-button rt-twitter-btn" href="https://twitter.com/rockettheme"><span></span></a>
  <a class="social-button rt-google-btn" href="https://plus.google.com/114430407008695950828/posts"><span></span></a>
  <a class="social-button rt-rss-btn" href="http://www.rockettheme.com/blog?format=feed&amp;type=rss"><span></span></a>
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

| Option              | Setting                                              |  
| :------------------ | :--------------------------------------------------- |  
| Module Class Suffix | `title1 nomarginbottom nopaddingbottom hidden-phone` |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/follow_1.jpeg
[demo3]: assets/follow_2.jpeg
[demo4]: assets/follow_3.jpeg
