---
title: Diametric: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Diametric Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/diametric:Diametric

---

Footer Section
-----
![][demo1]

:   1. **Text** [20%, 17%, se]
    2. **Text** [20%, 39%, se]
    3. **Gantry Login Form** [20%, 63%, se]

Here's the widget breakdown for the Footer section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Gantry Login Form

#### Text
The first Text widget in the section is made a lot like the others. You'll need to enter the following in the main text field.

~~~
<p>All demo content is for <strong>sample</strong> purposes only, intended to represent a live site. All content images are licensed from <a target="_blank" href="http://www.shutterstock.com/">shutterstock.com</a> for exclusive use on this demo only.</p>

<span>Note: <strong>RokSprocket</strong> requires a RokCommon plugin version 3.1&#43;. RokSprocket can be downloaded <a href="http://www.rockettheme.com/wordpress-downloads/plugins/club/3166-roksprocket">here</a>.</span>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Demo Information`.
* Enter `nomargintop nomarginbottom nopaddingbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text
The second Text widget in the section is made a lot like the others. You'll need to enter the following in the main text field.

~~~
<img src="http://demo.rockettheme.com/wordpress/wp_diametric/wp-content/rockettheme/rt_diametric_wp/frontpage/map.png" width="308" height="183" alt="Our Location" />
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Set the **Title** to `Our Location`.
* Enter `nomargintop nomarginbottom nopaddingbottom nopaddingleft nomarginleft` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Login Form
The login form located on the top-right of the front page is actually a **Gantry Login Form** widget. 

| Option | Setting |
|:-------|------:|
| Title | Member Access |
| User Greeting | Hi, |
| Pre-text | Blank |
| Post-text | Blank |
| Custom Variations | `nomargintop nomarginbottom nopaddingbottom` |

[demo1]: assets/demo_6.jpeg