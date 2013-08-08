---
title: Metropolis: Recreating the Demo - Inside Metropolis
description: Your Guide to Recreating Elements of the Metropolis Theme for Joomla
breadcrumb: /joomla:Joomla/templates:Templates/metropolis:Metropolis

---

Inside Metropolis
-----
![][demo]

:   1. **mod_custom** [20%, 41%, se]

We used a **mod_custom** module to make up the content in the **footer-b** position of the front page. You'll find the settings used in our demo below.

### Details
![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | Inside Metropolis |  
| Show Title | Show              |  
| Position   | footer-b          |  
| Status     | Published         |  
| Access     | Public            |  
| Language   | All               |  
| Note       | Blank             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<ul class="rt-demo-footer-menu">
  <li><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108">Features</a></li>
  <li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=109">Module Positions</a></li>
  <li><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=110">Module Variations</a></li>
  <li class="hidden-tablet"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">Extensions</a></li>
</ul>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |  

### Advanced
![][demo4]

| Option              | Setting        |  
| :------------------ | :------------- |  
| Module Class Suffix | `hidden-phone` |   

[demo]: assets/demo_7.jpeg
[demo2]: assets/info_1.jpeg
[demo3]: assets/info_2.jpeg
[demo4]: assets/info_3.jpeg