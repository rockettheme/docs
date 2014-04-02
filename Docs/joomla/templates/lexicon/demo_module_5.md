---
title: Lexicon: Recreating the Demo - FP Content Top 02
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

FP Content Top 02
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting             |  
| :--------- | :------------------ |  
| Title      | `FP Content Top 02` |  
| Show Title | Hide                |  
| Position   | content-top-a       |  
| Status     | Published           |  
| Access     | Public              |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-33">
    <img alt="image" src=
    "images/rocketlauncher/home/fp-content-top-02/img-01.jpg">

    <div class="gantry-width-spacer">
        <h4 class="medpaddingtop">Preset Styles</h4>

        <p>An assortment of six default but editable preset style
        variations.</p>

        <p><a href="#">Learn More</a></p>
    </div>
</div>

<div class="gantry-width-33">
    <img alt="image" src=
    "images/rocketlauncher/home/fp-content-top-02/img-02.jpg">

    <div class="gantry-width-spacer">
        <h4 class="medpaddingtop">Module Classes</h4>

        <p>Individualize modular content from the eight stylistic suffixes.</p>

        <p><a href=
        "index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=113">
        Learn More</a></p>
    </div>
</div>

<div class="gantry-width-33">
    <img alt="image" src=
    "images/rocketlauncher/home/fp-content-top-02/img-03.jpg">

    <div class="gantry-width-spacer">
        <h4 class="medpaddingtop">Typography</h4>

        <p>Extensive typographical options to diversify your content.</p>

        <p><a href=
        "index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114">
        Learn More</a></p>
    </div>
</div>

<div class="clear">
    &nbsp;
</div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting             |  
| :------------------ | :------------------ |  
| Module Class Suffix | `fp-content-top-02` |   

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg
