---
title: Chimera: Recreating the Demo - Subtle Features
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

Subtle Features
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                                                     |  
| :--------- | :---------------------------------------------------------- |  
| Title      | `[div class="wow pulse"]Subtle [span]Features[/span][/div]` |  
| Show Title | Show                                                        |  
| Position   | feature-a                                                   |  
| Status     | Published                                                   |  
| Access     | Public                                                      |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<h4>Incredibly useful and functional features and extensions create a palette of possibilities for your content</h4>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                                                 |  
| :------------------ | :------------------------------------------------------ |  
| Module Class Suffix | `fp-feature rt-heading-title rt-center nopaddingbottom` |  

[demo]: assets/demo_2.jpg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/demo_2c.jpeg
