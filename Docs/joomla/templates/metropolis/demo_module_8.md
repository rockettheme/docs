---
title: Metropolis: Recreating the Demo - Preset Styles
description: Your Guide to Recreating Elements of the Metropolis Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/metropolis:Metropolis

---

Preset Styles
-----
![][demo]

:   1. **mod_custom** [30%, 75%, se]

We used a **mod_custom** module to make up the content in the **footer-a** position of the front page. You'll find the settings used in our demo below.

### Details
![][demo2]

| Option     | Setting       |  
| :--------- | :------------ |  
| Title      | Preset Styles |  
| Show Title | Hide          |  
| Position   | sidebar-b     |  
| Status     | Published     |  
| Access     | Public        |  
| Language   | All           |  
| Note       | Blank         |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=117" class="rt-block-link"></a>
<div class="rt-center">
    <div class="module-title">
        <h2 class="title nomarginbottom visible-large">Preset Styles</h2>
        <h2 class="title nomarginbottom hidden-large">Styles</h2>
    </div>
</div>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                      |  
| :------------------ | :--------------------------- |  
| Module Class Suffix | `box3 icon-heart icon-large` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/preset_1.jpeg
[demo3]: assets/preset_2.jpeg
[demo4]: assets/preset_3.jpeg