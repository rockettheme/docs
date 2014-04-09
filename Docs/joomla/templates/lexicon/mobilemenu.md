---
title: Lexicon: Recreating the Demo - Mobile Sidemenu
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

Mobile Sidemenu
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

The module position **mobile-sidemenu** assigns the module to appear above the main menu on smartphones and other devices with thinner browser windows.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting          |  
| :--------- | :--------------- |  
| Title      | `About Lexicon`  |  
| Show Title | Show             |  
| Position   | mobile-sidemenu  |  
| Status     | Published        |  
| Access     | Public           |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>A feature rich and highly configurable, professional Joomla template.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix | `box1`  |  

[demo]: assets/mobilemenu.jpeg
[demo2]: assets/mobilemenu_1.jpeg
[demo3]: assets/mobilemenu_2.jpeg
[demo4]: assets/mobilemenu_3.jpeg
