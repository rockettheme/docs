---
title: Vermilion: Recreating the Demo - FP Feature
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

FP Feature
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting      |
| :---------- | :----------  |
| Title       | `FP Feature` |
| Show Title  | Hide         |
| Position    | feature-a    |
| Status      | Published    |
| Access      | Public       |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-25 fp-feature-block">
    <div class="fp-feature-image-block">
        <img alt="image" src=
        "images/rocketlauncher/home/fp-feature/img-01.jpg">
        <div class="rt-desc-overlay fp-feature-animate-1">
            <h3>Advanced &amp; adaptable CSS <span class=
            "hidden-tablet">dropdown</span> menu</h3>
            <p class="rt-text-small">Two Menu Options</p>
        </div>
    </div>
    <div class="gantry-width-spacer">
        <div class="rt-icon-badge">
            &nbsp;
        </div>
        <h5 class="medpaddingtop">Multiple Configurable Navigation Systems</h5>
        <p>Choose between our CSS-based dropdown menu with advanced features
        such as inline modules, or SplitMenu.</p>
    </div>
</div>
<div class="gantry-width-25 fp-feature-block">
    <div class="fp-feature-image-block">
        <img alt="image" src=
        "images/rocketlauncher/home/fp-feature/img-02.jpg">
        <div class="rt-desc-overlay fp-feature-animate-2">
            <h3>Integrated styling for RokSprocket <span class=
            "visible-large">layout modes</span></h3>
            <p class="rt-text-small">Content Module</p>
        </div>
    </div>
    <div class="gantry-width-spacer">
        <div class="rt-icon-badge">
            &nbsp;
        </div>
        <h5 class="medpaddingtop">Versatile Content Switchblade Extension</h5>
        <p>Multiple default layout modes to choose from, and an advanced &amp;
        powerful custom administrative interface.</p>
    </div>
</div>
<div class="gantry-width-25 fp-feature-block">
    <div class="fp-feature-image-block">
        <img alt="image" src=
        "images/rocketlauncher/home/fp-feature/img-03.jpg">
        <div class="rt-desc-overlay fp-feature-animate-3">
            <h3>Powerful and free core framework <span class=
            "visible-large">for Joomla</span></h3>
            <p class="rt-text-small">Gantry Framework</p>
        </div>
    </div>
    <div class="gantry-width-spacer">
        <div class="rt-icon-badge">
            &nbsp;
        </div>
        <h5 class="medpaddingtop">Extensive Array of Standard Features</h5>
        <p>Gantry is the powerful core framework that sits at the core of
        Vermilion, providing a rich feature set.</p>
    </div>
</div>
<div class="gantry-width-25 fp-feature-block">
    <div class="fp-feature-image-block">
        <img alt="image" src=
        "images/rocketlauncher/home/fp-feature/img-04.jpg">
        <div class="rt-desc-overlay fp-feature-animate-4">
            <h3><span class="visible-tablet">Several</span><span class=
            "hidden-tablet">Eight stylistics and</span> <span class=
            "hidden-large hidden-tablet">other</span><span class=
            "visible-large">several structural</span> module suffixes</h3>
            <p class="rt-text-small">Customization</p>
        </div>
    </div>
    <div class="gantry-width-spacer">
        <div class="rt-icon-badge">
            &nbsp;
        </div>
        <h5 class="medpaddingtop">Quick and Easy Module Individualization</h5>
        <p>A diverse selection of configurable module class suffixes, either
        stylistics or structural in function.</p>
    </div>
</div>
<div class="clear">
    &nbsp;
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

| Option              | Setting                   |
| :----------         | :----------               |
| Module Class Suffix | `fp-feature-01 rt-center` |

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_4a.jpeg
[demo3]: assets/demo_4b.jpeg
[demo4]: assets/demo_4c.jpeg
