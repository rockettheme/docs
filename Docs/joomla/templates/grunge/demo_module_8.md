---
title: Grunge: Recreating the Demo - Grunge Free/GPL Template
description: Your Guide to Recreating Elements of the Grunge Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/grunge:Grunge

---

Grunge Free/GPL Template
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Grunge -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:	1. **Leading Articles** [41%, 40%, se]
	2. **Article Order** [67%, 40%, se]

In order to show two featured articles on the front page, we placed a `3` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Article Manager Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Grunge Free/GPL Template** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<p><img alt="frontpage" border="0" class="floatleft" height="255" src=
"images/stories/demo/frontpage/painttruck.jpg" width="300"> <span class=
"article-title1">“Free, GPL Template from RocketTheme, available to download
and install today.”</span> <span class="article-title2">The second free
template release by RocketTheme in 2010.</span></p>

<p>Free templates offer a perfect opportunity to try out a RocketTheme template
without a club subscription. The same techniques and many core features are
present in free, as well as club templates.</p>
<hr id="system-readmore">

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis
natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla
facilisi. Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi
nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec
turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla
iaculis, leo sit amet mollis luctus, sapien eros consectetur dolor, eu faucibus
elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a,
mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>

<p>Mauris lobortis. Aliquam lacinia purus. Pellentesque magna. Mauris euismod
metus nec tortor. Phasellus elementum, quam a euismod imperdiet, ligula felis
faucibus enim, eu malesuada nunc felis sed turpis. Morbi convallis luctus
tortor. Integer bibendum lacinia velit. Suspendisse mi lorem, porttitor ut,
interdum et, lobortis a, lectus. Phasellus vitae est at massa luctus iaculis.
In tincidunt.</p>

<p>Integer fermentum elit in tellus. Integer ligula ipsum, gravida aliquet,
fringilla non, interdum eget, ipsum. Praesent id dolor non erat viverra
volutpat. Fusce tellus libero, luctus adipiscing, tincidunt vel, egestas vitae,
eros. Vestibulum mollis, est id rhoncus volutpat, dolor velit tincidunt neque,
vitae pellentesque ante sem eu nisl. Donec facilisis, magna eget elementum
pellentesque, augue arcu aliquet eros, eget convallis mauris ante quis magna.
Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac
turpis egestas. Aenean et libero. Nam aliquam. Quisque vitae tortor id neque
dignissim laoreet. Duis eu ante. Integer at sapien. Praesent sed nisl tempor
est pulvinar tristique. Maecenas non lorem quis mi laoreet adipiscing. Sed ac
arcu. Sed tincidunt libero eu dolor. Cras pharetra posuere eros. Donec ac eros
id diam tempor faucibus. Fusce feugiat consequat nulla. Vestibulum tincidunt
vulputate ipsum.</p>

<p>Nullam eget neque. Nullam imperdiet venenatis ligula. Integer a leo. Nunc
consectetur. Maecenas sem. Proin vulputate, massa vel volutpat laoreet, purus
erat pretium ligula, eget varius arcu nibh sed libero. Fusce ante. Nullam
interdum aliquet metus. Ut ultrices vestibulum tellus. Praesent quis erat. Nam
id turpis sit amet neque cursus luctus. Cum sociis natoque penatibus et magnis
dis parturient montes, nascetur ridiculus mus. Quisque id tortor. In vitae
sapien. Nunc quis tellus.</p>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_12.jpeg
[demo2]: assets/rokajaxsearch_1.jpeg
[demo3]: assets/rokajaxsearch_2.jpeg
[demo4]: assets/rokajaxsearch_3.jpeg
[advanced]: assets/advanced.jpg
[menu]: assets/menu.jpg