---
title: Lexicon: Recreating the Demo - FP Content Bottom 01
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

FP Content Bottom 01
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                |  
| :--------- | :--------------------- |  
| Title      | `FP Content Bottom 01` |  
| Show Title | Hide                   |  
| Position   | content-bottom-a       |  
| Status     | Published              |  
| Access     | Public                 |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p class="rt-text-medium"><em>Lexicon is centered around a flat design approach, spruced by professional and engaging color schemes to create presence for site content without distracting from it. <span class="hidden-tablet">Ideal for showcasing product details in a vibrant but elegant fashion.</span></em></p>

<br />

<div class="gantry-row">
    <div class="gantry-width-10 hidden-tablet">
        <div class="gantry-width-spacer">
            <img class="rt-rounded" src="images/rocketlauncher/home/fp-content-bottom-01/img-01.jpg" alt="image" />
        </div>
    </div>

    <div class="gantry-width-50">
        <div class="gantry-width-spacer">
            <h4 class="smallmarginbottom">Responsive Layout</h4>
            <p><em>Automatic adaptation<span class="hidden-tablet">  to varying devices</span></em></p>
        </div>
    </div>

    <div class="gantry-width-40">
        <div class="gantry-width-spacer gantry-right">
            <p class="medmargintop"><a class="readon" href="http://www.rockettheme.com/joomla/templates/lexicon">Download<span class="hidden-tablet"> Lexicon</span></a></p>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                |  
| :------------------ | :--------------------- |  
| Module Class Suffix | `fp-content-bottom-01` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/demo_8a.jpeg
[demo3]: assets/demo_8b.jpeg
[demo4]: assets/demo_8c.jpeg
