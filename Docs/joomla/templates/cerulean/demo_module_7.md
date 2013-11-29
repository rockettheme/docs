---
title: Cerulean: Recreating the Demo - Cerulean Demo
description: Your Guide to Recreating Elements of the Cerulean Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cerulean:Cerulean

---

Cerulean Demo
-----
![][demo]

We used a **mod_custom** module to make up the content in the **sidebar-b** position of the front page. You will find the settings used in our demo below.

### Details
![][demo2]

| Option     | Setting                                                                                                |  
| :--------- | :----------------------------------------------------------------------------------------------------- |  
| Title      | `Cerulean[span class="hidden-tablet"] Demo[/span].  [span class="icon-chevron-down rt-teaser"][/span]` |  
| Show Title | Hide                                                                                                   |  
| Position   | sidebar-b                                                                                              |  
| Status     | Published                                                                                              |  
| Access     | Public                                                                                                 |  
| Language   | All                                                                                                    |  
| Note       | Blank                                                                                                  |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>RocketLauncher is a customized Joomla install, that installs a replica of the demo.</p>

<p class="hidden-tablet">All sample content images, shown in this demo, will be replaced with blanks in the RocketLauncher for copyright reasons.</p>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting               |  
| :------------------ | :-------------------- |  
| Module Class Suffix | `box3 nomarginbottom` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/cdemo_1.jpeg
[demo3]: assets/cdemo_2.jpeg
[demo4]: assets/cdemo_3.jpeg