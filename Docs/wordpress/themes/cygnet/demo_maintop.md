---
title: Cygnet: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Cygnet Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cygnet:Cygnet

---

Main Top Section
-----

![Feature](assets/demo_6.jpeg)

Here is the widget breakdown for the Main Top section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="gantry-row rt-center">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <div class="rt-block-maintop">
                    <h3>Themes</h3>
                    <hr />
                    <div class="rt-super-large-text rt-odometer-1 odometer" data-odometer-value="81">1</div>
                    <p>An extensive collection of premium WordPress themes available to you.</p>
                </div>
            </div>
        </div>
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <div class="rt-block-maintop">
                    <h3>RocketTheme</h3>
                    <hr />
                    <div class="rt-super-large-text wow tada" data-wow-duration="2s"><i class="fa fa-rocket"></i></div>
                    <p>Producing best WordPress themes for over 7 years!</p>
                </div>
            </div>
        </div>
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <div class="rt-block-maintop">
                    <h3>Plugins</h3>
                    <hr />
                    <div class="rt-super-large-text rt-odometer-2 odometer" data-odometer-value="8">1</div>             
                    <p>Extend the functionality of your WordPress website with a variety of plugins.</p>
                </div>
            </div>
        </div>
    </div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

| Option            | Setting      |
| :---------------- | :---------   |
| Custom Variations | `fp-maintop` |

>> NOTE: You will need to make sure that the **Odometer** setting is set to **On** in order for this widget to behave the way it does in the demo. You can find this setting in Cygnet Settings under the **Advanced** tab.

![](assets/setadvanced.jpeg)

Leaving everything else at its default setting, select **Save**.
