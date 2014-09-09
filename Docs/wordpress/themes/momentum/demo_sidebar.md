---
title: Momentum: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Momentum Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/momentum:Momentum

---

Sidebar Section
-----

![][demo1]

: 1. **RokNewsPager** [7%, 15%, se]
  2. **Text** [30%, 15%, se]
  3. **Text** [52%, 15%, se]
  4. **Text** [67%, 15%, se]

Here is the widget breakdown for the Sidebar section:

* RokNewsPager
* Gantry Login Form
* Text
* Text

#### RokNewsPager

This area of the demo is a RokNewsPager widget. RokNewsPager is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Gantry Login Form

The login form located on the top-right of the front page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option            | Setting                         |
| :---------------- | :------------------------------ |
| Title             | Login Form                      |
| User Greeting     | Hi,                             |
| Pre-Text          | Blank                           |
| Post-text         | Blank                           |
| Box Variations    | Basic                           |

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><a href="http://demo.rockettheme.com/live/wordpress/momentum/preset-styles/">Customize</a> the theme's <strong>color scheme</strong> via the Gantry administrator. Control various style elements such as <strong>link, text and background color</strong>, of the current or new <strong>presets</strong>.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Color Chooser Controls`.
* Switch the **Title Variation** option to **Title 2**.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div>
    <p class="dropcap2">1</p>
    <a href="http://demo.rockettheme.com/live/wordpress/momentum/tutorials/installation/"><span class="heading1 nomargintop nomarginbottom">Essential Downloads</span></a>
    <span>Download the theme and peripheral files from RocketTheme.com.</span>
</div>

<div>
    <p class="dropcap2">2</p>
    <a href="http://demo.rockettheme.com/live/wordpress/momentum/preset-styles/"><span class="heading1 nomargintop nomarginbottom">Style Configuration</span></a>
    <span>Customize the existing presets to your only personal preference and save.</span>
</div>

<div>
    <p class="dropcap2">3</p>
    <a href="http://demo.rockettheme.com/live/wordpress/momentum/tutorials/rocketlauncher/"><span class="heading1 nomargintop nomarginbottom">Launcher Assist</span></a>
    <span>Learn the intricacies of the theme faster with the RocketLauncher.</span>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Initial Theme Setup`.
* Switch the **Box Variation** option to **Box 1**.
* Leaving everything else at its default setting, select **Save**.

[demo1]: assets/demo_7.jpeg
[roksprocket]: ../../plugins/roksprocket/