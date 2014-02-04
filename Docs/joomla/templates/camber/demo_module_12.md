---
title: Camber: Recreating the Demo - Featured Article
description: Your Guide to Recreating Elements of the Camber Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Camber:Camber

---

Featured Article
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Mainbody Enabled** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Camber -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Intro Articles** [35%, 72%, se]
    2. **Article Order** [51%, 72%, se]

In order to show two featured articles on the front page, we placed a `1` in the **Intro Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Popular Features** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<img class="rt-image floatleft smallmarginbottom" src="images/stories/demo/frontpage/fp-article.jpg" width="125" height="100" alt="RocketTheme" />

<p>The Camber template is built for both the Joomla <strong>1.5.x</strong> and <strong>1.7.x</strong> platforms, with full support for both. This includes the template, the RocketTheme Extensions demoed, the Gantry Framework, version specific PDF tutorials, in addition to <strong>RocketLaunchers</strong> for both versions. All products are available from a consolidated Joomla Download area for Camber.</p>

<p>The template is based on the <strong>Gantry Framework</strong>, therefore, standard features such as the 960 Grid System, <strong>iPhone/Android</strong> viewing support. Layered on top is an intricate array of design elements, textures, patterns and backgrounds providing an elegant but complex appearance.</p>

<hr id="system-readmore" />

<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>

<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_12.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg