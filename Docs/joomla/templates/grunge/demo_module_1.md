---
title: Grunge: Recreating the Demo - Frontpage Showcase A
description: Your Guide to Recreating Elements of the Grunge Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/grunge:Grunge

---

Frontpage Showcase A
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                  |  
| :--------- | :----------------------- |  
| Title      | `RokStories Placeholder` |  
| Show Title | Hide                     |  
| Position   | showcase-a               |  
| Status     | Published                |  
| Access     | Public                   |  
| Language   | All                      |  
| Note       | Blank                    |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rokstories-layout2">
<div class="feature-block"><img class="floatleft rt-sample-rokstories" src="images/stories/demo/frontpage/showcase1.jpg" border="0" alt="image" /> <span class="feature-title">Grunge Free/GPL Template Release</span>
<p class="feature-desc"><strong>Grunge</strong>, the June 2010 Free GPL release, is the second free template to take advantage of the Gantry Framework, and is outfitted with a sophisticated, artistic and professional design, on top of the highly functional core.</p>
<div class="readon"><a href="#"><span>Read the Full Story</span></a></div>
</div>
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

[demo]: assets/demo_1.jpeg
[demo2]: assets/fpshowcase_1.jpeg
[demo3]: assets/fpshowcase_2.jpeg
[demo4]: assets/fpshowcase_3.jpeg