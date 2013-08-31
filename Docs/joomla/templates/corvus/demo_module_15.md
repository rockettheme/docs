---
title: Corvus: Recreating the Demo - Scroll Triggered Expanded Module
description: Your Guide to Recreating Elements of the Corvus Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

Scroll Triggered Expanded Module
----
![][demo]
This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

The effect that makes the module expand as you scroll down is the result of the module class suffix used to in the **Advanced Options** area of the module's settings.

### Details
![][demo2]

| Option     | Setting                            |  
| :--------- | :--------------------------------- |  
| Title      | `Scroll Triggered Expanded Module` |  
| Show Title | Show                               |  
| Position   | showcase-a                         |  
| Status     | Published                          |  
| Language   | All                                |  
| Note       | Blank                              |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>A feature of Corvus is the <strong>expanded</strong> module. Any module that has the <strong>expanded</strong> module class suffix applied to it, will expand based on window <strong>scroll</strong>. The feature is best applied in the <strong>showcase</strong> position, with a full width module, as demoed currently. The <strong>overlap</strong> effect below, is via CSS and can be customized through the <a href="http://www.gantry-framework.org/documentation/joomla/tutorials/custom_stylesheet.md">custom stylesheet process</a>, depending on your content needs.</p>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting              |  
| :------------------ | :------------------- |  
| Module Class Suffix | `expanded rt-center` |  

[demo]: assets/demo_2.jpeg
[demo2]: assets/scroll_1.jpeg
[demo3]: assets/scroll_2.jpeg
[demo4]: assets/scroll_3.jpeg