---
title: Metropolis: Recreating the Demo - RocketLauncher
description: Your Guide to Recreating Elements of the Metropolis Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/metropolis:Metropolis

---

RocketLauncher
-----
![][demo]

:   1. **mod_custom** [55%, 75%, se]

We used a **mod_custom** module to make up the content in the **footer-a** position of the front page. You will find the settings used in our demo below.

### Details
![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | RocketLauncher |  
| Show Title | Hide           |  
| Position   | sidebar-b      |  
| Status     | Published      |  
| Access     | Public         |  
| Language   | All            |  
| Note       | Blank          |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-center">
    <div class="module-title">
      <h2 class="title visible-large">RocketLauncher</h2>
      <h2 class="title hidden-large smallmarginbottom">Replica</h2>
    </div>
</div>

<span class="visible-tablet">A full Joomla installation that installs a editied version of the demo.</span>
<span class="hidden-tablet">A full Joomla installation that installs a editied version of the demo onto your server.</span>
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
| Module Class Suffix | `box2 icon-magic icon-large` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/launcher_1.jpeg
[demo3]: assets/launcher_2.jpeg
[demo4]: assets/launcher_3.jpeg