---
title: Entropy: Recreating the Demo - Featured Articles
description: Your Guide to Recreating Elements of the Entropy Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/entropy:Entropy

---

Featured Articles
-----

![][demo]

This area of the front page is made up of articles. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Mainbody Enabled** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Entropy -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Intro Articles** [35%, 72%, se]
    2. **Article Order** [51%, 72%, se]

In order to show two featured articles on the front page, we placed a `3` in the **Intro Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Popular Features** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used for one of these articles:

~~~ .html
<p><strong>Fusion</strong> is a javascript enhanced CSS dropdown menu system, that is fully <em>crawlable</em> by search engines. Mootools adds <a href="#">transitions and animations</a> to the dropdown, providing a smooth and dynamic interface for the navigational structure. <strong>MegaMenu</strong> features include a vast assortment, such as <a href="#">multiple columns</a>, grouped child items, <strong>dropdown widths</strong> and item distribution. These provide for <a href="#">individual control</a> over each specific dropdown menu item or column.</p>

<hr id="system-readmore" />

<div class="notice"><div class="typo-icon">For more information on the Fusion with MegaMenu feature, please refer to the <a href="index.php?option=com_content&amp;view=article&amp;id=53&amp;Itemid=60">Menu Options Tutorial Page</a>.</div></div>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor.</p>

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla facilisi. Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla iaculis, leo sit amet mollis luctus, sapien eros consectetur dolor, eu faucibus elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a, mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>

<p>Integer fermentum elit in tellus. Integer ligula ipsum, gravida aliquet, fringilla non, interdum eget, ipsum. Praesent id dolor non erat viverra volutpat. Fusce tellus libero, luctus adipiscing, tincidunt vel, egestas vitae, eros. Vestibulum mollis, est id rhoncus volutpat, dolor velit tincidunt neque, vitae pellentesque ante sem eu nisl. Donec facilisis, magna eget elementum pellentesque, augue arcu aliquet eros, eget convallis mauris ante quis magna. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean et libero. Nam aliquam. Quisque vitae tortor id neque dignissim laoreet. Duis eu ante. Integer at sapien. Praesent sed nisl tempor est pulvinar tristique. Maecenas non lorem quis mi laoreet adipiscing. Sed ac arcu. Sed tincidunt libero eu dolor. Cras pharetra posuere eros. Donec ac eros id diam tempor faucibus. Fusce feugiat consequat nulla. Vestibulum tincidunt vulputate ipsum.</p>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_5.jpeg
[advanced]: assets/advanced.jpg
[menu]: assets/menu.jpeg