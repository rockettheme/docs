---
title: Omnicron: Recreating the Demo - Featured Articles
description: Your Guide to Recreating Elements of the Omnicron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/omnicron:Omnicron

---

Featured Articles
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** and **Display Mainbody** options have been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Omnicron -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Intro Articles** [46%, 72%, se]
    2. **Article Order** [68%, 72%, se]

In order to show a featured article on the front page, we placed a `1` in the **Intro Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Frequently Asked Questions** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<div class="rt-demo-grid-4">
  <ul class="bullet-notes">
    <li><em class="bold">What is RokFeatureTable?</em></li>
  </ul>
  <div class="rt-block">
    <p><strong>RokFeatureTable</strong> is designed to show tabular <strong>data</strong>, offering a user friendly <strong>interface</strong> and integrated styling.</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=11&amp;Itemid=110" class="readon"><span>More Details</span></a>
  </div>
</div>
<div class="rt-demo-grid-4">
  <ul class="bullet-calendar">
    <li><em class="bold">What is Fusion with MegaMenu?</em></li>
  </ul>
  <div class="rt-block">
    <p><strong>MegaMenu</strong> describes a series of advanced features, such as <strong>grouped items</strong> and <strong>inline modules</strong>, to the <strong>Fusion</strong> dropdown menu.</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=22&amp;Itemid=118" class="readon"><span>More Details</span></a>
  </div>
</div>
<div class="clear"></div>

<div class="rt-demo-grid-4">
  <ul class="bullet-monitor">
    <li><em class="bold">What are the CSS 3 Features?</em></li>
  </ul>
  <div class="rt-block">
    <p><strong>Border radiuses</strong> for rounded corners, <strong>color transitions</strong> on hover, box shadows and CSS <strong>rotation</strong> are all included.</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=107" class="readon"><span>More Details</span></a>
  </div>
</div>
<div class="rt-demo-grid-4">
  <ul class="bullet-briefcase">
    <li><em class="bold">What is the Gantry Framework?</em></li>
  </ul>
  <div class="rt-block">
    <p><strong>Gantry</strong> is an advanced <strong>framework</strong> that powers our latest templates, offering an excellent <strong>foundation</strong>, full of <strong>features</strong>.</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=133" class="readon"><span>More Details</span></a>
  </div>
</div>
<div class="clear"></div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_6.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg
