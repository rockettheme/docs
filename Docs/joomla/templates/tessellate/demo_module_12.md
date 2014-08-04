---
title: Tessellate: Recreating the Demo - FP MainTop A
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

FP MainTop A
-----

![][demo]

We used a **Custom HTML** module to create this area of the front page. You will find the settings used in our demo below.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `FP MainTop A` |
| Show Title  | Hide           |
| Position    | maintop-a      |
| Status      | Published      |
| Access      | Public         |

### Custom Output

~~~ .html
<div class="gantry-width-container">
    <div class="gantry-width-50 fp-maintop-col1">
        <img src="images/rocketlauncher/home/fp-maintop/img-01.jpg" alt="image" />
        <div class="fp-maintop-img-desc">
            <h6 class="nomargintop smallmarginbottom">Information</h6>
            <p>Gantry is a template framework for Joomla and Wordpress<span class="hidden-tablet">, by RocketTheme, providing a standardized product core</span>.</p>
        </div>
    </div>
    <div class="gantry-width-50 fp-maintop-col2">
        <div class="gantry-width-spacer">
            <h3>The <span class="hidden-tablet">Free/GPL </span>Gantry Framework</h3>

            <p>The most noticeable visual feature of Gantry is its custom administrator, providing a user friendly <span class="hidden-tablet">and rich </span>console for template configuration.</p>
            <p class="hidden-tablet">The framework has many features, such as module grid controls, that come as standard on all templates.</p>
            
            <p class="visible-large">Other features include overridable layouts for modules, positions and mainbody output; several features such as font-sizer; as well as powering the LESS infrastructure.</p>

            <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon5">Read More</a>
        </div>
    </div>
</div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                          |
| :----------         | :----------                      |
| Module Class Suffix | `fp-maintop-a box3 nopaddingall` |

[demo]: assets/demo_12.jpeg
[demo2]: assets/demo_12a.jpeg
[demo3]: assets/demo_12b.jpeg
[demo4]: assets/demo_12c.jpeg
