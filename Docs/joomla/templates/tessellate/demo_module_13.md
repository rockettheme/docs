---
title: Tessellate: Recreating the Demo - FP MainTop B
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

FP MainTop B
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `FP MainTop B` |
| Show Title  | Show           |
| Position    | maintop-b      |
| Status      | Published      |
| Access      | Public         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-container">
    <div class="gantry-width-50 fp-maintop-col1">
        <img src="images/rocketlauncher/home/fp-maintop/img-02.jpg" alt="image" />
        <div class="fp-maintop-img-desc">
            <h6 class="nomargintop smallmarginbottom">Information</h6>
            <p><span>RokSprocket is a content extension <span class="hidden-tablet">for Joomla and Wordpress, </span>by RocketTheme<span class="hidden-tablet">, that offers multiple layouts and themes</span>.</span></p>
        </div>
    </div>
    <div class="gantry-width-50 fp-maintop-col2">
        <div class="gantry-width-spacer">
            <h3>RokSprocket <span class="hidden-tablet">Content </span>Extension</h3>

            <p>RokSprocket has its own, unique, custom administrative interface with intuitive controls and ajax loading to make content setup quick and easy.</p>
            <p class="hidden-tablet">RokSprocket has multiple layouts to choose from with varying themes, such as Features : Showcase.</p>
            
            <p class="visible-large"> Others include Tabs, Headlines, Mosaic, Strips and Lists. RokSprocket also benefits from multiple content providers, such as Joomla, K2 and its own, Simple.</p>

            <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon4">Read More</a>
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
| Module Class Suffix | `fp-maintop-b box3 nopaddingall` |

[demo]: assets/demo_13.jpeg
[demo2]: assets/demo_13a.jpeg
[demo3]: assets/demo_13b.jpeg
[demo4]: assets/demo_13c.jpeg
