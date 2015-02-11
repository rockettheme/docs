---
title: Chapelco: Recreating the Demo - Template Overview
description: Your Guide to Recreating Elements of the Chapelco Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chapelco:Chapelco

---

Template Overview
-----

![Template Overview](assets/demo_12.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![Template Overview](assets/demo_12a.jpeg)

|   Option   |       Setting       |
| :--------- | :------------------ |
| Title      | `Template Overview` |
| Show Title | Show                |
| Position   | maintop-a           |
| Status     | Published           |
| Access     | Public              |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-block demo-width-100">
  <div class="gantry-width-33 gantry-width-block">
    <div class="gantry-width-spacer">
      <div class="gantry-width-30 gantry-width-block">
        <h5 class="title largemarginright"><span class="rt-bubble icon-tasks rt-big-bubble"></span></h5>
      </div>  
      <div class="gantry-width-70 gantry-width-block">
        <h3 class="nomarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">Gantry 4<span class="hidden-tablet"> Core</span></a></h3>
        <p>Gantry 4 Framework powering all standardized features and functions.</p>
      </div>  
    </div>
  </div>  
  <div class="gantry-width-33 gantry-width-block">
    <div class="gantry-width-spacer">
      <div class="gantry-width-30 gantry-width-block">
        <h5 class="title largemarginright"><span class="rt-bubble icon-list rt-big-bubble"></span></h5>
      </div>  
      <div class="gantry-width-70 gantry-width-block">
        <h3 class="nomarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=112">Dropdown<span class="hidden-tablet"> Menu</span></a></h3>
        <span>A CSS based dropdown menu with<span class="hidden-large"> advanced</span> options such as mutli-columns.</span>
      </div>  
    </div>
  </div>  
  <div class="gantry-width-33 gantry-width-block">
    <div class="gantry-width-spacer">
      <div class="gantry-width-30 gantry-width-block">
        <h5 class="title largemarginright"><span class="rt-bubble icon-medkit rt-big-bubble"></span></h5>
      </div>  
      <div class="gantry-width-70 gantry-width-block">
        <h3 class="nomarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">Extensions</a></h3>
        <p>Styled support for RokSprocket, RokAjaxSearch and K2 (3rd party).</p>
      </div>  
    </div>
  </div>   
</div>

<div class="clear"></div>

<div class="gantry-width-block demo-width-100">
  <div class="gantry-width-33 gantry-width-block">
    <div class="gantry-width-spacer">
      <div class="gantry-width-30 gantry-width-block">
        <h5 class="title largemarginright"><span class="rt-bubble icon-th rt-big-bubble"></span></h5>
      </div>  
      <div class="gantry-width-70 gantry-width-block">
        <h3 class="nomarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">Mosaic<span class="hidden-tablet"> Mode</span></a></h3>
        <span>Mosaic is a dynamic ajax content<span class="hidden-large"> display</span> mode, perfect for magazine layouts.</span>
      </div>  
    </div>
  </div>  
  <div class="gantry-width-33 gantry-width-block">
    <div class="gantry-width-spacer">
      <div class="gantry-width-30 gantry-width-block">
        <h5 class="title largemarginright"><span class="rt-bubble icon-picture rt-big-bubble"></span></h5>
      </div>  
      <div class="gantry-width-70 gantry-width-block">
        <h3 class="nomarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=117">Preset<span class="hidden-tablet"> Style</span>s</a></h3>
        <p>Eight preset style variations to choose, each with configurable options.</p>
      </div>  
    </div>
  </div>  
  <div class="gantry-width-33 gantry-width-block">
    <div class="gantry-width-spacer">
      <div class="gantry-width-30 gantry-width-block">
        <h5 class="title largemarginright"><span class="rt-bubble icon-random rt-big-bubble"></span></h5>
      </div>  
      <div class="gantry-width-70 gantry-width-block">
        <h3 class="nomarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=112">SplitMenu</a></h3>
        <p>Static horizontal menu with children placed in the sidebar, or as configured.</p>
      </div>  
    </div>
  </div>   
</div>

<div class="clear"></div>
~~~

### Basic

![Template Overview](assets/demo_12b.jpeg)

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![Template Overview](assets/demo_12c.jpeg)

|        Option       |                         Setting                         |
| :------------------ | :------------------------------------------------------ |
| Module Class Suffix | `title5 icon-star featuretitle fp-maintop hidden-phone` |
