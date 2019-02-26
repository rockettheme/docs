---
title: Vermilion: Recreating the Demo - FP Showcase
description: Your Guide to Recreating Elements of the Vermilion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/vermilion:Vermilion

---

FP Showcase
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting       |
| :---------- | :----------   |
| Title       | `FP Showcase` |
| Show Title  | Hide          |
| Position    | showcase-a    |
| Status      | Published     |
| Access      | Public        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="fp-showcase-content">
    <div class="fp-showcase-title">
        <p class="promo1">About <strong>Vermilion</strong></p>
    </div>
    <div class="fp-showcase-info">
        <p class="hidden-phone">Vermilion adopts a business or commercial centric visual model, with corporate background shades interwoven with configurable, vibrant or brand colors, allowing for an equilibrium between professionalism and artistic allure.</p>
        <span class="readon-row">
            <a href="http://www.rockettheme.com/joomla/templates/vermilion" class="readon">Purchase Vermilion</a>
            <a href="http://www.rockettheme.com/docs/joomla/templates/vermilion" class="readon2">View Documentation</a>
        </span>
    </div>
</div>
~~~

### Options

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                                     |
| :----------         | :----------                                 |
| Module Class Suffix | `fp-showcase fp-showcase-animate rt-center` |

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
