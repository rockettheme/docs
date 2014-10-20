---
title: Cerulean: Recreating the Demo - Recent News
description: Your Guide to Recreating Elements of the Cerulean Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cerulean:Cerulean

---

Recent News
-----
![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                          |  
| :--------- | :----------------------------------------------- |  
| Title      | `Recent [span class="hidden-tablet"]News[/span]` |  
| Show Title | Hide                                             |  
| Position   | sidebar-a                                        |  
| Status     | Published                                        |  
| Access     | Public                                           |  
| Language   | All                                              |  
| Note       | Blank                                            |  

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="box2 largepaddingall">
<h4 class="nomargintop medmarginbottom"><a href="#">Flexible Layouts.</a></h4>
<p class="rt-image hidden-large">
<img alt="image" src="images/rocketlauncher/frontpage/sidebar-a/img1.jpg" />
</p>
<p class="rt-image visible-large">
<img alt="image" src="images/rocketlauncher/frontpage/sidebar-a/img1-large.jpg" />
</p>
<div class="rt-teaser">Responsive Modes</div>
<span>Adaptable layout for mobile<span class="visible-large"> (portrait / landscape)</span>, tablet and desktop displays.</span>
</div>

<div class="box2 largepaddingall">
<h4 class="nomargintop medmarginbottom"><a href="#">Gantry 4 Core.</a></h4>
<p class="rt-image hidden-large">
<img alt="image" src="images/rocketlauncher/frontpage/sidebar-a/img2.jpg" />
</p>
<p class="rt-image visible-large">
<img alt="image" src="images/rocketlauncher/frontpage/sidebar-a/img2-large.jpg" />
</p><div class="rt-teaser">Advanced Features</div>
<span>Configure an array of features with the Gantry Framework<span class="visible-large">'s custom interface</span>.</span>
</div>

<div class="box2 largepaddingall">
<h4 class="nomargintop medmarginbottom"><a href="#">Multiple Styles</a></h4>
<p class="rt-image hidden-large">
<img alt="image" src="images/rocketlauncher/frontpage/sidebar-a/img3.jpg" />
</p>
<p class="rt-image visible-large">
<img alt="image" src="images/rocketlauncher/frontpage/sidebar-a/img3-large.jpg" />
</p><div class="rt-teaser">Configurable Presets</div>
<span>A wide selection of preset<span class="visible-large"> style</span>s and module <span class="visible-large">variations</span><span class="hidden-large">suffixes</span> are available.</span>
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

| Option              | Setting                                                                |  
| :------------------ | :--------------------------------------------------------------------- |  
| Module Class Suffix | `title1 title3 rt-box2-stack nopaddingall nomarginleft nomarginbottom` |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/news_1.jpeg
[demo3]: assets/news_2.jpeg
[demo4]: assets/news_3.jpeg