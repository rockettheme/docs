---
title: Grunge: Recreating the Demo - RokStories Info
description: Your Guide to Recreating Elements of the Grunge Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/grunge:Grunge

---

RokStories Info
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                |  
| :--------- | :--------------------- |  
| Title      | `RokStories Info`      |  
| Show Title | Show                   |  
| Position   | sidebar-a              |  
| Status     | Published              |  
| Access     | Public                 |  
| Language   | All                    |  
| Note       | Blank                  |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p><span class="article-title2">RokStories: Only available to RocketTheme club members.</span></p>
<p>You can replicate the exact demo construction if you have RokStories, simply:</p>
<ol>
<li>Disable the <strong>RokStories Placeholder</strong> module</li>
<li>Install RokStories</li>
<li>Setup with the following settings</li>
</ol>
<div class="readon"><a href="images/stories/demo/frontpage/rokstories-settings.png"><span>Preview Settings</span></a></div>
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

[demo]: assets/demo_2.jpeg
[demo2]: assets/info_1.jpeg
[demo3]: assets/info_2.jpeg
[demo4]: assets/info_3.jpeg