---
title: Praxis: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Praxis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/praxis:Praxis

---

Copyright Section
-----

![][demo]

:	1. **Gantry Social Buttons** [35%, 5%, se]
	2. **Gantry Text** [35%, 75%, se]

Here is the widget breakdown for the Copyright section:

* Gantry Social Buttons
* Gantry Divider
* Gantry Text

The Copyright section remains the same for all areas of the site. Because of this, it is preserved as a Default widget override.

#### Gantry Social Buttons

The Gantry Social Buttons widget creates a set of social buttons on the top of the page. Filling this out is fairly straightforward. Once you have clicked and dragged the **Gantry Social Buttons** widget in place, you will want to add your various social URLs to their respective fields. Once this is done, simply hit **Save** and check the site. 

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.


#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~
<a href="http://www.rockettheme.com/" title="rockettheme.com" id="rocket"></a>
		<div class="fp-copyright">&copy; Copyright 2013. Powered by <a href="http://www.rockettheme.com">RocketTheme</a>
</div>
~~~

Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_9.jpeg