---
title: Lumiere: Recreating the Demo - Top News of the Week Title
description: Your Guide to Recreating Elements of the Lumiere Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lumiere:Lumiere

---

Top News of the Week Title
-----
![][demo]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                            |
| :--------- | :----------------------------------------------------------------- |
| Title      | `Top News of the Week Title`                                       |
| Show Title | Hide                                                               |
| Position   | utility-a                                                          |
| Status     | Published                                                          |
| Access     | Public                                                             |
| Language   | All                                                                |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-center">
	<p class="promo2 nomarginbottom">Top News of the Week.</p>
	<p class="promo3 nomarginbottom">Lumiere uses HTML5 video to create a dynamic and interactive user experience.</p>	
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

| Option              | Setting                          |  
| :------------------ | :------------------------------- |  
| Module Class Suffix | `nomarginbottom nopaddingbottom` |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/news_1.jpeg
[demo3]: assets/news_2.jpeg
[demo4]: assets/news_3.jpeg