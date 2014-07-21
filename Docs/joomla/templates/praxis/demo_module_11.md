---
title: Praxis: Recreating the Demo - Footer Social Buttons
description: Your Guide to Recreating Elements of the Praxis Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/praxis:Praxis

---

Footer Social Buttons
-----
![][demo]

We used a **mod_custom** module to make up the content in the **footer-a** position of the front page. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option            | Setting                 |
| :---------------- | :-----------------      |
| Title             | `Footer Social Buttons` |
| Show Title        | Hide                    |
| Position          | copyright-a             |
| Status            | Published               |
| Access            | Public                  |
| Language          | All                     |
| Note              | Blank                   |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-social-buttons fp-sidenav-spacing">
    <a href="http://www.facebook.com/RocketTheme" class="social-button rt-social-button-1"><span class="icon-facebook"></span></a>
    <a href="https://twitter.com/rockettheme" class="social-button rt-social-button-2"><span class="icon-twitter"></span></a>
    <a href="https://plus.google.com/114430407008695950828/posts" class="social-button rt-social-button-4"><span class="icon-google-plus"></span></a>
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

| Option              | Setting                                       |
| :------------------ | :---------------                              |
| Module Class Suffix | `fp-sidenav-spacing nomarginall nopaddingall` |

[demo]: assets/demo_social.jpeg
[demo2]: assets/social_1.jpeg
[demo3]: assets/social_2.jpeg
[demo4]: assets/social_3.jpeg
