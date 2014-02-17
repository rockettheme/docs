---
title: Modulus: Recreating the Demo - RokGallery Features
description: Your Guide to Recreating Elements of the Modulus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/modulus:Modulus

---

RokGallery Features
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Mainbody Enabled** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Modulus -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [32%, 71%, se]
    2. **Article Order** [50%, 71%, se]

In order to show two featured articles on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. The **Intro Articles** and **Columns** settings are both at **2** allowing the other two featured articles to display as **Intro** articles below the primary one.

Article Properties
-----

The **RokSprocket Layouts** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<img src="images/stories/demo/frontpage/fp-main1.jpg" alt="image" width="193" height="157" class="rt-image floatleft" />

<p><strong>Modulus</strong> has integrated styling for <strong>12</strong> RocketTheme Extensions, that are compatible with both Joomla <strong>1.5.x</strong> and Joomla <strong>1.6.x</strong>, as well as supporting a further 4 utility extensions, as available in the RocketLauncher.</p>

<p>Examples of styled extensions used on this page include <em>RokTabs</em> and <em>RokTwittie</em>, with all others demoed under the <a href="index.php?option=com_content&amp;view=article&amp;id=50&amp;Itemid=57">Extensions</a> menu tab above, with documentation on their use and download information.</p>
<hr id="system-readmore" />
<div class="clear"></div>
<span>The above comments are powered by <a href="http://intensedebate.com/" target="_blank">IntenseDebate</a></span>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_6.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg