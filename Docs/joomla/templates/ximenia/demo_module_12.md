---
title: Ximenia: Recreating the Demo - Advertisement
description: Your Guide to Recreating Elements of the Ximenia Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ximenia:Ximenia

---

Advertisement
----
![][demo]
This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting         |  
| :--------- | :-------------- |  
| Title      | `Advertisement` |  
| Show Title | Show            |  
| Position   | sidebar-a       |  
| Status     | Published       |  
| Access     | Public          |  
| Language   | All             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<a href="http://www.rockettheme.com/" target="_blank">
  <span class="rt-image rt-floatleft smallmargintop">
    <img width="190" height="150" alt="RocketTheme" src="images/rocketlauncher/frontpage/general/rockettheme.jpg" />
  </span>
</a>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting  |  
| :------------------ | :------- |  
| Module Class Suffix | `title1` |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/ad_1.jpeg
[demo3]: assets/ad_2.jpeg
[demo4]: assets/ad_3.jpeg