---
title: Somaxiom: Recreating the Demo - Featured Article
description: Your Guide to Recreating Elements of the Somaxiom Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/somaxiom:Somaxiom

---

Featured Article
-----

![][demo]

This area of the front page is an article. Articles appear within the **MainBody** area of the front page.

Turning on MainBody Content
-----

This content appears on the front page because the **Display MainBody** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Somaxiom -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [32%, 25%, se]

In order to show two featured articles on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Powered by Gantry v3** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<img alt="image" src="images/stories/demo/frontpage/fp-iphone2.png" title="image" class="floatright"  width="208" height="385" />

<p><strong>Somaxiom</strong> is the first template to be driven by <strong>Gantry v3.0</strong>. There are several major features in this Gantry release, ranging from <strong>iPhone</strong> support, to <strong>Google Web Fonts</strong>, to <strong>Smart Loading</strong>, several bug fixes and much more.</p>

<h3>iPhone Platform Theme</h3>

<p>This version of <strong>Gantry</strong> expands its browser portfolio to <strong>iPhone</strong>'s Safari, producing a <strong>mobile</strong> version of the <strong>Somaxiom</strong> template for all visitors using the popular smartphone.</p>

<ul class="bullet-1">
  <li><strong>iPhone Theme:</strong> An iPhone specific layout, combining pre-existing template elements with mobile specific styling.</li>
  <li><strong>Aliases:</strong> Assign current module positions to mobile equivalents such as <em>mobile-header &rarr; header-a</em></li>
</ul>

<h3>Google Web Fonts</h3>

<p><strong>Google</strong> have launched their new <strong>font directory</strong> service, which offers a <strong>Font API</strong> for web developers to load <strong>Custom Fonts</strong> straight from their servers.</p>

<ul class="bullet-1">
  <li>Preview all available Google fonts from the Google Font Directory located <a href="http://code.google.com/webfonts" target="_blank">here</a></li>
</ul>

[readon2 url="index.php?option=com_content&view=article&id=2&Itemid=116"]More Gantry v3 Information[/readon2]
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_7.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg