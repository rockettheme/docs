---
title: Alerion: Recreating the Demo - Module Style
description: Your Guide to Recreating Elements of the Alerion Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

Module Style
-----

![][demo]

:	1. **mod_custom** [40%, 68%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                                           |  
| :--------- | :------------------------------------------------ |  
| Title      | `Module[span class="hidden-tablet"] Style[/span]` |  
| Show Title | Show                                              |  
| Position   | extension-c                                       |  
| Status     | Published                                         |  
| Access     | Public                                            |  

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present in the **Title** field. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~ .html
<p>A wide assortment of module class suffixes are available, to diversify your modular content. Modify the style of the titles, backgrounds, layouts or varying combinations for each module.</p>

<a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=110">Read More</a>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                              |  
| :------------------ | :----------------------------------- |  
| Module Class Suffix | `title2 largemargintop hidden-phone` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/modstyle_1.jpeg
[demo3]: assets/modstyle_2.jpeg
[demo4]: assets/modstyle_3.jpeg