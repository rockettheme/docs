---
title: Omnicron: Recreating the Demo - Demo Information
description: Your Guide to Recreating Elements of the Omnicron Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/omnicron:Omnicron

---

Demo Information
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Sliding Panel

![][demo5]

This particular module is part of a sliding module position enabled via the template settings. To enable a sliding panel, navigate to **Admin -> Template Manager -> Omnicron -> Features** and set either the **Feature Panel** or **Lower Panel** settings. 

Since this particular module is in a **lowerpanel** position, the sliding panel can be toggled using the **Lower Panel** option.

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `Demo Information` |  
| Show Title | Show               |  
| Position   | lowerpanel-a       |  
| Status     | Published          |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p class="nomarginbottom">All demo content is for demonstrative <strong>purposes</strong> only, intended to show a representative example of a <strong>live site</strong>. All images and materials are the copyright of their respective owners. Additionally, this demo, in a modified form, is available for download in the <strong>RocketLauncher</strong> format.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting      |  
| :------------------ | :----------- |  
| Module Class Suffix | `title1`     |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/demo_7a.jpeg
[demo3]: assets/demo_7b.jpeg
[demo4]: assets/demo_7c.jpeg
[demo5]: assets/demo_1d.jpeg
