---
title: Clarion: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Clarion Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/clarion:Clarion

---

Bottom Section
-----

![][demo1]

:   1. **Text 1** [20%, 6%, se]
    2. **Text 2** [20%, 29%, se]
    3. **Text 3** [20%, 50%, se]
    4. **Gantry Login Form** [20%, 75%, se]

Here is the widget breakdown for the Main Bottom section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text
* Gantry Divider
* Gantry Login Form

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="medmarginbottom"><strong>Clarion</strong>, RocketTheme's WordPress Theme release for September 2012.</p>

<span class="text-icon info normalfont">9876 North West Boulevard</span>
<br />
<span class="text-icon normalfont  medpaddingbottom">Milwaukee, WI, 00000, USA</span>
<br />
<span class="text-icon normalfont phone">T  1 (555) 555-555-5555</span>
<br />
<span class="text-icon normalfont medpaddingbottom">F  1 (555) 555-555-5556</span>
<br />
<span class="text-icon email normalfont"><a class="nobold" href="#">noreply@rockettheme.com</a></span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Contact Details`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="medmarginbottom">All demo content is for <strong>sample</strong> purposes only, intended to represent a live site. All content images are licensed from <a href="http://www.shutterstock.com/" target="_blank" class="nobold">shutterstock.com</a> for exclusive use on this demo only.</p>
<span>Please download the <strong>RocketLauncher</strong> pack to install a copy of the base demo.</span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Demo Information`.
* Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Connect with us via a selection of popular social media, networks and other platforms.</p>

<span class="text-icon facebook normalfont medpaddingbottom">/rockettheme</span>
<br />
<span class="text-icon twitter normalfont medpaddingbottom">@rockettheme</span>
<br />
<span class="text-icon rss normalfont medpaddingbottom">RSS Feed</span>
<br />
<span class="text-icon vimeo normalfont medpaddingbottom">Video Feed</span>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Network with Us`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Login Form

The login form located in this area of the page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option            | Setting                         |
| :----------       | :----------                     |
| Title             | `Member Access`                 |
| User Greeting     | Hi,                             |

[demo1]: assets/demo_8.jpeg
