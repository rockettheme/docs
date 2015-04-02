---
title: Cygnet: Recreating the Demo - FP SideBar
description: Your Guide to Recreating Elements of the Cygnet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cygnet:Cygnet

---

FP SideBar
-----

![](assets/demo_13.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_14a.jpeg)

| Option     | Setting      |
| :--------- | :----------- |
| Title      | `FP SideBar` |
| Show Title | Hide         |
| Position   | sidebar-a    |
| Status     | Published    |
| Access     | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-effect-slide rt-effect-slide-top">
    <img alt="image" src="images/rocketlauncher/home/fp-sidebar/img-01.jpg">
    <div class="rt-effect-slide-content">
        <h2 class="rt-uppercase"><a class="fp-demo-url" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Responsive</a></h2>
        <p><a class="fp-demo-url" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Adapts to any devices</a></p>
    </div>          
</div>

<div class="rt-effect-slide rt-effect-slide-top">
    <img alt="image" src="images/rocketlauncher/home/fp-sidebar/img-02.jpg">
    <div class="rt-effect-slide-content">
        <h2 class="rt-uppercase"><a class="fp-demo-url" href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114">Typography</a></h2>
        <p><a class="fp-demo-url" href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114">Individualize <span class="hidden-tablet">your</span> content</a></p>
    </div>          
</div>

<div class="rt-effect-slide rt-effect-slide-top">
    <img alt="image" src="images/rocketlauncher/home/fp-sidebar/img-03.jpg">
    <div class="rt-effect-slide-content">
        <h2 class="rt-uppercase"><a class="fp-demo-url" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Presets</a></h2>
        <p><a class="fp-demo-url" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Six elegant styles</a></p>
    </div>          
</div>
~~~

### Basic

![](assets/demo_14b.jpeg)

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_14c.jpeg)

| Option              | Setting                           |
| :------------------ | :-------------------------------- |
| Module Class Suffix | `fp-sidebar wow fadeIn`           |
