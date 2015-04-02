---
title: Cygnet: Recreating the Demo - FP MainTop
description: Your Guide to Recreating Elements of the Cygnet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cygnet:Cygnet

---

FP MainTop
-----

![](assets/demo_6.jpeg)

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![](assets/demo_7a.jpeg)

| Option     | Setting      |
| :--------- | :----------- |
| Title      | `FP MainTop` |
| Show Title | Hide         |
| Position   | maintop-a    |
| Status     | Published    |
| Access     | Public       |

### Custom Output

~~~ .html
<div class="gantry-row rt-center">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <div class="rt-block-maintop">
                    <h3>Templates</h3>
                    <hr />
                    <div class="rt-super-large-text rt-odometer-1 odometer" data-odometer-value="88">1</div>
                    <p>An extensive collection of premium Joomla templates available to you.</p>
                </div>
            </div>
        </div>
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <div class="rt-block-maintop">
                    <h3>RocketTheme</h3>
                    <hr />
                    <div class="rt-super-large-text wow tada" data-wow-duration="2s"><i class="fa fa-rocket"></i></div>
                    <p>The longest running Joomla template provider, producing templates for over 8 years.</p>
                </div>
            </div>
        </div>
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <div class="rt-block-maintop">
                    <h3>Extensions</h3>
                    <hr />
                    <div class="rt-super-large-text rt-odometer-2 odometer" data-odometer-value="15">1</div>                
                    <p>Extend the functionality of your Joomla website with a variety of extensions.</p>
                </div>
            </div>
        </div>
    </div>
</div>
~~~

### Basic

![](assets/demo_7b.jpeg)

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

![](assets/demo_7c.jpeg)

| Option              | Setting      |
| :-----              | :-----       |
| Module Class Suffix | `fp-maintop` |
