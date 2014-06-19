---
title: Reaction: Recreating the Demo - Featured Articles
description: Your Guide to Recreating Elements of the Reaction Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/reaction:Reaction

---

Featured Articles
-----

![][demo]

This area of the front page is made of four featured articles. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Reaction -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [42%, 72%, se]

In order to show a featured article on the front page, we placed a `4` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Article Manager Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Latest Articles** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody. It makes up the first of four articles that appear on the front page of our demo in the section.

Here is the **Article Text** we used:

~~~ .html
<img src="images/stories/demo/frontpage/blog1.jpg" alt="Blog Image" class="rt-image"/>

<p><span class="rt-article-subline">Gantry: The Brand New, Powerful and Intricate Framework / Platform from the RocketTheme Team</span></p>
<p>The new <strong>Gantry Framework</strong> allows for a much more efficient, more powerful underlying system; that can transcend to other platforms with ease. The main features of Gantry are its 960 Grid system, and its advanced administrative control panel, with a vast assortment of other features ready to enhance your Joomla experience.</p>

<hr id="system-readmore" />

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor.</p>

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla facilisi. Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla iaculis, leo sit amet mollis luctus, sapien eros consectetur dolor, eu faucibus elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a, mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>

<p>Mauris lobortis. Aliquam lacinia purus. Pellentesque magna. Mauris euismod metus nec tortor. Phasellus elementum, quam a euismod imperdiet, ligula felis faucibus enim, eu malesuada nunc felis sed turpis. Morbi convallis luctus tortor. Integer bibendum lacinia velit. Suspendisse mi lorem, porttitor ut, interdum et, lobortis a, lectus. Phasellus vitae est at massa luctus iaculis. In tincidunt.</p>

<p>Integer fermentum elit in tellus. Integer ligula ipsum, gravida aliquet, fringilla non, interdum eget, ipsum. Praesent id dolor non erat viverra volutpat. Fusce tellus libero, luctus adipiscing, tincidunt vel, egestas vitae, eros. Vestibulum mollis, est id rhoncus volutpat, dolor velit tincidunt neque, vitae pellentesque ante sem eu nisl. Donec facilisis, magna eget elementum pellentesque, augue arcu aliquet eros, eget convallis mauris ante quis magna. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean et libero. Nam aliquam. Quisque vitae tortor id neque dignissim laoreet. Duis eu ante. Integer at sapien. Praesent sed nisl tempor est pulvinar tristique. Maecenas non lorem quis mi laoreet adipiscing. Sed ac arcu. Sed tincidunt libero eu dolor. Cras pharetra posuere eros. Donec ac eros id diam tempor faucibus. Fusce feugiat consequat nulla. Vestibulum tincidunt vulputate ipsum.</p>

<p>Nullam eget neque. Nullam imperdiet venenatis ligula. Integer a leo. Nunc consectetur. Maecenas sem. Proin vulputate, massa vel volutpat laoreet, purus erat pretium ligula, eget varius arcu nibh sed libero. Fusce ante. Nullam interdum aliquet metus. Ut ultrices vestibulum tellus. Praesent quis erat. Nam id turpis sit amet neque cursus luctus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque id tortor. In vitae sapien. Nunc quis tellus.</p>
~~~

Here is the **Article Text** used on the second article, **Design Focus**.

~~~ .html
<img src="images/stories/demo/frontpage/blog2.jpg" alt="Blog Image" class="rt-image"/>

<p><span class="rt-article-subline">Style Variations: 6 Excellent Styles, in 3 Background and Body Levels, High, Medium and Low Intensity.</span></p>
<p>Reaction has 6 preset styles / style variations and <strong>18</strong> combinations. Each preset style has 3 background levels: <strong>Low</strong>, <strong>Medium</strong> &amp; <strong>High</strong>, which represent different levels of detail, making Reaction both a graphically intense, but graphically reserved template. You can edit the combinations in your template as outlined on the <a href="index.php?option=com_content&amp;view=article&amp;id=60&amp;Itemid=167">Style Control</a> page.</p>

<hr id="system-readmore" />

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor.</p>

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla facilisi. Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla iaculis, leo sit amet mollis luctus, sapien eros consectetur dolor, eu faucibus elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a, mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>

<p>Mauris lobortis. Aliquam lacinia purus. Pellentesque magna. Mauris euismod metus nec tortor. Phasellus elementum, quam a euismod imperdiet, ligula felis faucibus enim, eu malesuada nunc felis sed turpis. Morbi convallis luctus tortor. Integer bibendum lacinia velit. Suspendisse mi lorem, porttitor ut, interdum et, lobortis a, lectus. Phasellus vitae est at massa luctus iaculis. In tincidunt.</p>

<p>Integer fermentum elit in tellus. Integer ligula ipsum, gravida aliquet, fringilla non, interdum eget, ipsum. Praesent id dolor non erat viverra volutpat. Fusce tellus libero, luctus adipiscing, tincidunt vel, egestas vitae, eros. Vestibulum mollis, est id rhoncus volutpat, dolor velit tincidunt neque, vitae pellentesque ante sem eu nisl. Donec facilisis, magna eget elementum pellentesque, augue arcu aliquet eros, eget convallis mauris ante quis magna. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean et libero. Nam aliquam. Quisque vitae tortor id neque dignissim laoreet. Duis eu ante. Integer at sapien. Praesent sed nisl tempor est pulvinar tristique. Maecenas non lorem quis mi laoreet adipiscing. Sed ac arcu. Sed tincidunt libero eu dolor. Cras pharetra posuere eros. Donec ac eros id diam tempor faucibus. Fusce feugiat consequat nulla. Vestibulum tincidunt vulputate ipsum.</p>

<p>Nullam eget neque. Nullam imperdiet venenatis ligula. Integer a leo. Nunc consectetur. Maecenas sem. Proin vulputate, massa vel volutpat laoreet, purus erat pretium ligula, eget varius arcu nibh sed libero. Fusce ante. Nullam interdum aliquet metus. Ut ultrices vestibulum tellus. Praesent quis erat. Nam id turpis sit amet neque cursus luctus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque id tortor. In vitae sapien. Nunc quis tellus.</p>
~~~

Here is the **Article Text** used on the third article, **Extendability**.

~~~ .html
<img src="images/stories/demo/frontpage/blog3.jpg" alt="Blog Image" class="rt-image"/>

<p><span class="rt-article-subline">Extensions: A Diverse and Functional Range of both Integrated RocketTheme Extensions and 3rd Party Addons.</span></p>
<p>Extensions are an integral part of any Joomla site, and template sided integration of popular addons is an important step on theme development. Therefore, as is tradition with our template releases, we have styled integration of many of our extensions such as <em>RokTabs</em>, in conjunction with a 3rd party component: <em>JComments</em> </p>

<hr id="system-readmore" />

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor.</p>

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla facilisi. Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla iaculis, leo sit amet mollis luctus, sapien eros consectetur dolor, eu faucibus elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a, mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>

<p>Mauris lobortis. Aliquam lacinia purus. Pellentesque magna. Mauris euismod metus nec tortor. Phasellus elementum, quam a euismod imperdiet, ligula felis faucibus enim, eu malesuada nunc felis sed turpis. Morbi convallis luctus tortor. Integer bibendum lacinia velit. Suspendisse mi lorem, porttitor ut, interdum et, lobortis a, lectus. Phasellus vitae est at massa luctus iaculis. In tincidunt.</p>

<p>Integer fermentum elit in tellus. Integer ligula ipsum, gravida aliquet, fringilla non, interdum eget, ipsum. Praesent id dolor non erat viverra volutpat. Fusce tellus libero, luctus adipiscing, tincidunt vel, egestas vitae, eros. Vestibulum mollis, est id rhoncus volutpat, dolor velit tincidunt neque, vitae pellentesque ante sem eu nisl. Donec facilisis, magna eget elementum pellentesque, augue arcu aliquet eros, eget convallis mauris ante quis magna. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean et libero. Nam aliquam. Quisque vitae tortor id neque dignissim laoreet. Duis eu ante. Integer at sapien. Praesent sed nisl tempor est pulvinar tristique. Maecenas non lorem quis mi laoreet adipiscing. Sed ac arcu. Sed tincidunt libero eu dolor. Cras pharetra posuere eros. Donec ac eros id diam tempor faucibus. Fusce feugiat consequat nulla. Vestibulum tincidunt vulputate ipsum.</p>

<p>Nullam eget neque. Nullam imperdiet venenatis ligula. Integer a leo. Nunc consectetur. Maecenas sem. Proin vulputate, massa vel volutpat laoreet, purus erat pretium ligula, eget varius arcu nibh sed libero. Fusce ante. Nullam interdum aliquet metus. Ut ultrices vestibulum tellus. Praesent quis erat. Nam id turpis sit amet neque cursus luctus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque id tortor. In vitae sapien. Nunc quis tellus.</p>
~~~

Here is the **Article Text** for the last article on this front page, **Menu Structure**.

~~~ .html 
<img src="images/stories/demo/frontpage/blog4.jpg" alt="Blog Image" class="rt-image"/>

<p><span class="rt-article-subline">Navigation: Setting the Standards for Joomla Menus, from the Advanced Fusion Menu to Traditional Alternatives.</span></p>
<p>Fusion, the default, but most powerful, menu is the central navigation system of Reaction. Javascript and advanced styles make it a complex, efficient and functional dropdown system. Other options are available such as Splitmenu, a non-js version of Fusion to a Suckerfish only mode for Internet Explorer 6.</p>

<hr id="system-readmore" />

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor.</p>

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla facilisi. Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla iaculis, leo sit amet mollis luctus, sapien eros consectetur dolor, eu faucibus elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a, mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>

<p>Mauris lobortis. Aliquam lacinia purus. Pellentesque magna. Mauris euismod metus nec tortor. Phasellus elementum, quam a euismod imperdiet, ligula felis faucibus enim, eu malesuada nunc felis sed turpis. Morbi convallis luctus tortor. Integer bibendum lacinia velit. Suspendisse mi lorem, porttitor ut, interdum et, lobortis a, lectus. Phasellus vitae est at massa luctus iaculis. In tincidunt.</p>

<p>Integer fermentum elit in tellus. Integer ligula ipsum, gravida aliquet, fringilla non, interdum eget, ipsum. Praesent id dolor non erat viverra volutpat. Fusce tellus libero, luctus adipiscing, tincidunt vel, egestas vitae, eros. Vestibulum mollis, est id rhoncus volutpat, dolor velit tincidunt neque, vitae pellentesque ante sem eu nisl. Donec facilisis, magna eget elementum pellentesque, augue arcu aliquet eros, eget convallis mauris ante quis magna. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean et libero. Nam aliquam. Quisque vitae tortor id neque dignissim laoreet. Duis eu ante. Integer at sapien. Praesent sed nisl tempor est pulvinar tristique. Maecenas non lorem quis mi laoreet adipiscing. Sed ac arcu. Sed tincidunt libero eu dolor. Cras pharetra posuere eros. Donec ac eros id diam tempor faucibus. Fusce feugiat consequat nulla. Vestibulum tincidunt vulputate ipsum.</p>

<p>Nullam eget neque. Nullam imperdiet venenatis ligula. Integer a leo. Nunc consectetur. Maecenas sem. Proin vulputate, massa vel volutpat laoreet, purus erat pretium ligula, eget varius arcu nibh sed libero. Fusce ante. Nullam interdum aliquet metus. Ut ultrices vestibulum tellus. Praesent quis erat. Nam id turpis sit amet neque cursus luctus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque id tortor. In vitae sapien. Nunc quis tellus.</p>
~~~

Once these articles are created and set to **Featured**, they should appear on the front page.

[demo]: assets/demo_4.jpg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpg
