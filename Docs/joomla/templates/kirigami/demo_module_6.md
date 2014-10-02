---
title: Kirigami: Recreating the Demo - Demo Replica
description: Your Guide to Recreating Elements of the Kirigami Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/kirigami:Kirigami

---

Demo Replica
-----
![][demo]

:   1. **mod_custom** [52%, 74%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `Demo Replica` |  
| Show Title | Show           |  
| Position   | sidebar-a      |  
| Status     | Published      |  
| Access     | Public         |  
| Language   | All            |  
| Note       | Blank          |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="medmarginbottom hidden-tablet"><strong>RocketLauncher</strong> is a customized <strong>Joomla</strong> install, that installs a <strong>replica</strong> of the <strong>demo</strong>.</p>

<p>All sample content images, shown in this demo, will be replaced with blanks in the <a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=109"><strong>Kirigami RocketLauncher</strong></a> package to avoid any copyright issue.</p>

<a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=109"><span>Download</span></a>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                        |  
| :------------------ | :----------------------------- |  
| Module Class Suffix | `basictitle box1 hidden-phone` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/replica_1.jpeg
[demo3]: assets/replica_2.jpeg
[demo4]: assets/replica_3.jpeg