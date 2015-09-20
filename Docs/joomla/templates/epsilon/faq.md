---
title: Epsilon: FAQ
description: Your Guide to Using the Epsilon Template for Joomla
breadcrumb: /joomla:Joomla/!themes:Themes/epsilon:Epsilon

---

What are Epsilon template features?
-----

Please check our [Template Info page][features] for all Epsilon features in one complete list.

## Can I Change the Hexagons to Something Else?

The hexigon shapes used in the Epsilon template are created with a blend of techniques and are largely considered a part of the core of the theme, rather than a feature intended for ready changing.

In most cases found in our demo, these are squares with pseudo-elements `:before` and `:after` applied. You will also find them scattered throughout the theme. For example, the hexigon elements at the bottom of the **FP Expanded Bottom** module are SVG masks created with the following custom code in the simple provider window:

~~~ .html
<span class="rt-testimonial-item">
<span class="icon-quote-left"></span>  
A beautiful and rich selection of typography, based on Bootstrap, to emphasise <span class="hidden-tablet">and embellish </span>content. 
<span class="icon-quote-right"></span>
<span class="rt-arrow-bottom"></span>
</span><span class="rt-testimonial-img">
<svg class="rt-hexagon-svg" width="150px" height="150px" viewBox = "0 0 200 200" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1">
<g><clipPath id="rt-hexagon-mask-1">
<polygon points="99.9999999999999,196 16.8615612366939,148 16.8615612366939,52 100,4 183.138438763306,52 183.138438763306,148" />          </clipPath></g>      
<a xlink:href="#">       
<image clip-path="url(#rt-hexagon-mask-1)" height="100%" width="100%" xlink:href="images/rocketlauncher/frontpage/expandedbottom/img1.jpg" />
</a>
</svg>
</span><span class="rt-testimonial-author">Leo Parry</span>
<span class="rt-testimonial-position">CEO of Hexeris</span>
~~~ 

The best way to determine how specific areas of the theme are set up, we recommend downloading a RocketLauncher version of the theme, and using your browser's inspector to find specific CSS sources and other resources to help you address them one-by-one.

Is Epsilon compatible for Joomla 1.5?
-----

No, Epsilon is only compatible with Joomla 2.5 and Joomla 3.x. Joomla 1.5 support was discontinued in September 2012 by Joomla.

What is RokSprocket?
-----

[RokSprocket][roksprocket] is a powerful content display extension for Joomla 2.5 and above. It was designed as the successor to our legacy content extensions: RokStories, RokTabs, RokNewsPager, RokNewsflash, RokMicronews, and basically any module in the RT arsenal that manipulates and displays articles.

What is Gantry?
-----

[Gantry][gantry] is, as a basic definition, a framework used for assembling, building and maintaining a RocketTheme template. It is an advanced platform for dramatically extending the capabilities of the entire theming system of Joomla.

What is DropDown Menu?
-----

[DropDown Menu][dropdown] is a menu theme of the RokNavMenu extension, the addon that drives many RocketTheme template menus. It is primarily a CSS enhanced dropdown menu, with subtext line, multi-columns, icons and more.

What is Splitmenu?
-----

A static menu system that displays 1st level items in the main horizontal menu and further children in the Sidebar.

What extensions are integrated with the template?
-----

A few of our RocketTheme extensions have been given individual styling by the template, these are RokAjaxSearch, RokNavMenu, RokSprocket, and Third party extension K2.

Can I install RocketLauncher onto an existing Joomla! website?
-----

No. RocketLauncher will install both Joomla and the demo sample content and images, so you will need a fresh Joomla! installation.

I installed Epsilon RocketLauncher but the images are different with the demo site.
-----

To avoid image license copyright issues, all sample content images shown in our demo site will be replaced with blank versions in the RocketLauncher version.

[gantry]: http://gantry.org/
[features]: http://demo.rockettheme.com/joomla-templates/epsilon/features
[font]: http://www.fontsquirrel.com/fonts/Raleway
[forum]: http://www.rockettheme.com/forum/joomla-template-epsilon
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[dropdown]: http://demo.rockettheme.com/joomla-templates/epsilon/features/menu-options
[splitmenu]: http://demo.rockettheme.com/joomla-templates/epsilon/features/menu-options
