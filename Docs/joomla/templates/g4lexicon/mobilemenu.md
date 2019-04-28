---
title: Lexicon: Recreating the Demo - Mobile Sidemenu
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

Mobile Sidemenu
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

The module position **mobile-sidemenu** assigns the module to appear above the main menu on smartphones and other devices with thinner browser windows.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Options

![][demo7]

There are two layout options for the mobile menu available in Lexicon. You can choose either **Panel** or **Selectbox** as the **Responsive Menu** setting by navigating to **Administrator -> Extensions -> Template Manager -> Lexicon -> Menu**.

The image used at the top of this page is a **Panel** responsive menu. You will find the **Selectbox** menu below.

![][demo6]

Neither of these options require any changes in the module settings to function.

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
[demo6]: assets/mobilemenu_4.jpg
[demo7]: assets/mobilemenu_5.jpg
