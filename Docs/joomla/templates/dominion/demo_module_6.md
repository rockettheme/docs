---
title: Dominion: Recreating the Demo - Mainbody
description: Your Guide to Recreating Elements of the Dominion Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/dominion:Dominion

---

Mainbody
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Dominion -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Intro Articles** [46%, 72%, se]

In order to show a featured article on the front page, we placed a `3` in the **Intro Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Article Manager Order**.

Article Properties
-----

The **RTL Template Support** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody. It makes up the first of four articles that appear on the front page of our demo in the section.

Here is the **Article Text** we used:

~~~ .html
<p class="demo-img"><img src="images/stories/demo/frontpage/mb-2.jpg" alt="demo image" class="rt-image" /></p>

<h3>Template side RTL support from the Fusion menu to the Typography.</h3>

<p class="demo-title"><em class="bold">This is in conjunction with Gantry version 2.0's RTL support for the automatic flipping of the grid system.</em></p>
<div class="clear"></div>
<p>If Joomla is set to RTL mode, in its language settings, the Dominion template will automatically adjust to its RTL layout. The modules will invert inside a row, such as showcase-a and showcase-f being in alternate locations; the various template elements such as the breadcrumbs and typography will also flip; and also the menu will adjust accordingly (ensure you are using the latest version of RokNavMenu however).</p>

<p><a href="images/stories/demo/general/jan10-rtl-preview-full.jpg" rel="rokbox(fullscreen)" title="Preview of the Demo Frontpage in RTL mode"><span>Preview (Large Image 240KB)</span></a></p>

<hr id="system-readmore" />

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor. </p>
~~~

Here is the **Article Text** used on the second article, **Stunning Style Variations**.

~~~ .html
<p class="demo-img"><img src="images/stories/demo/frontpage/mb-1.jpg" alt="demo image" class="rt-image" /></p>

<h3>Bundled with an array of six uniquely designed and beautiful style variations.</h3>

<p class="demo-title"><em class="bold">A selection of light and dark variations are available, 3 of each, which broadens the range of use of Dominion.</em></p>
<div class="clear"></div>
<p>An important aspect of any Gantry driven RocketTheme template is the ability to change the <em>level</em> of the style variation, mainly the background and body levels. These come in combinations of <strong>High</strong>, <strong>Med</strong>, and <strong>Low</strong>; making Dominion suitable for both conservative and complex sites with just a flick of a switch.</p>
<p>Remember, you can combine different levels such as the high background level with the low body level if you wish. Although, it is best to keep the background and body settings to the same level</p>

<hr id="system-readmore" />

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor.</p>

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla facilisi. Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla iaculis, leo sit amet mollis luctus, sapien eros consectetur dolor, eu faucibus elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a, mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>

<p>Mauris lobortis. Aliquam lacinia purus. Pellentesque magna. Mauris euismod metus nec tortor. Phasellus elementum, quam a euismod imperdiet, ligula felis faucibus enim, eu malesuada nunc felis sed turpis. Morbi convallis luctus tortor. Integer bibendum lacinia velit. Suspendisse mi lorem, porttitor ut, interdum et, lobortis a, lectus. Phasellus vitae est at massa luctus iaculis. In tincidunt.</p>

<p>Integer fermentum elit in tellus. Integer ligula ipsum, gravida aliquet, fringilla non, interdum eget, ipsum. Praesent id dolor non erat viverra volutpat. Fusce tellus libero, luctus adipiscing, tincidunt vel, egestas vitae, eros. Vestibulum mollis, est id rhoncus volutpat, dolor velit tincidunt neque, vitae pellentesque ante sem eu nisl. Donec facilisis, magna eget elementum pellentesque, augue arcu aliquet eros, eget convallis mauris ante quis magna. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean et libero. Nam aliquam. Quisque vitae tortor id neque dignissim laoreet. Duis eu ante. Integer at sapien. Praesent sed nisl tempor est pulvinar tristique. Maecenas non lorem quis mi laoreet adipiscing. Sed ac arcu. Sed tincidunt libero eu dolor. Cras pharetra posuere eros. Donec ac eros id diam tempor faucibus. Fusce feugiat consequat nulla. Vestibulum tincidunt vulputate ipsum.</p>

<p>Nullam eget neque. Nullam imperdiet venenatis ligula. Integer a leo. Nunc consectetur. Maecenas sem. Proin vulputate, massa vel volutpat laoreet, purus erat pretium ligula, eget varius arcu nibh sed libero. Fusce ante. Nullam interdum aliquet metus. Ut ultrices vestibulum tellus. Praesent quis erat. Nam id turpis sit amet neque cursus luctus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque id tortor. In vitae sapien. Nunc quis tellus.</p>
~~~

Here is the **Article Text** used on the second article, **Advanced Menu System**.

~~~ .html
<p class="demo-img"><img src="images/stories/demo/frontpage/mb-3.jpg" alt="demo image" class="rt-image" /></p>

<h3>A multiplicity of menu options are available such as the mootools driven Fusion Menu.</h3>

<p class="demo-title"><em class="bold">Other menu options are available such as the versatile and reliable Splitmenu; and Suckerfish for Internet Explorer 6</em></p>
<div class="clear"></div>
<p>All menu options are controlled inside the Gantry interface located at <strong>Admin &rarr; Extensions &rarr; Template Manager &rarr; rt_dominion_j15 &rarr; Menu</strong>. Here you can specific which menu option you want such as Fusion Menu, and if applicable, various other options such as transition type.</p>
<p>You can also disable the menu in its entirety, or alternatively, you can change it to the module position <strong>navigation</strong> and published another module there if you so wish.</p>

<hr id="system-readmore" />

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor.</p>

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla facilisi. Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla iaculis, leo sit amet mollis luctus, sapien eros consectetur dolor, eu faucibus elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a, mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>

<p>Mauris lobortis. Aliquam lacinia purus. Pellentesque magna. Mauris euismod metus nec tortor. Phasellus elementum, quam a euismod imperdiet, ligula felis faucibus enim, eu malesuada nunc felis sed turpis. Morbi convallis luctus tortor. Integer bibendum lacinia velit. Suspendisse mi lorem, porttitor ut, interdum et, lobortis a, lectus. Phasellus vitae est at massa luctus iaculis. In tincidunt.</p>

<p>Integer fermentum elit in tellus. Integer ligula ipsum, gravida aliquet, fringilla non, interdum eget, ipsum. Praesent id dolor non erat viverra volutpat. Fusce tellus libero, luctus adipiscing, tincidunt vel, egestas vitae, eros. Vestibulum mollis, est id rhoncus volutpat, dolor velit tincidunt neque, vitae pellentesque ante sem eu nisl. Donec facilisis, magna eget elementum pellentesque, augue arcu aliquet eros, eget convallis mauris ante quis magna. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean et libero. Nam aliquam. Quisque vitae tortor id neque dignissim laoreet. Duis eu ante. Integer at sapien. Praesent sed nisl tempor est pulvinar tristique. Maecenas non lorem quis mi laoreet adipiscing. Sed ac arcu. Sed tincidunt libero eu dolor. Cras pharetra posuere eros. Donec ac eros id diam tempor faucibus. Fusce feugiat consequat nulla. Vestibulum tincidunt vulputate ipsum.</p>

<p>Nullam eget neque. Nullam imperdiet venenatis ligula. Integer a leo. Nunc consectetur. Maecenas sem. Proin vulputate, massa vel volutpat laoreet, purus erat pretium ligula, eget varius arcu nibh sed libero. Fusce ante. Nullam interdum aliquet metus. Ut ultrices vestibulum tellus. Praesent quis erat. Nam id turpis sit amet neque cursus luctus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque id tortor. In vitae sapien. Nunc quis tellus.</p>
~~~

Once this articles are created and set to **Featured**, they should appear on the front page.

[demo]: assets/demo_7.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg
