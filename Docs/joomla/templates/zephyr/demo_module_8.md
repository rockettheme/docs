---
title: Zephyr: Recreating the Demo - Featured Article
description: Your Guide to Recreating Elements of the Zephyr Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/zephyr:Zephyr

---

Featured Article
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** and **Display Mainbody** options have been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Zephyr -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [42%, 72%, se]
    2. **Article Order** [68%, 72%, se]

In order to show a featured article on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Ultimate Style Control** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<p><strong>Transparency</strong> lays at the heart of the Zephyr template, with the entire theme being developed around it. Every structural image is transparent to allow <strong>background colors</strong> to bleed through seamlessly.</p>          
            
In unison is the <strong>Color Chooser</strong>, providing extension controls, in a user friendly interface, over all style in the template, ranging from <strong>background, text or link colors</strong> to the overlay styles.

<hr id="system-readmore" />

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit amet nibh. Vivamus non arcu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dapibus, tellus ac ornare aliquam, massa diam tristique urna, id faucibus lectus erat ut pede. Maecenas varius neque nec libero laoreet faucibus. Phasellus sodales, lectus sed vulputate rutrum, ipsum nulla lacinia magna, sed imperdiet ligula nisi eu ipsum. Donec nunc magna, posuere eget, aliquam in, vulputate in, lacus. Sed venenatis. Donec nec dolor vitae mauris dapibus ullamcorper. Etiam iaculis mollis tortor.</p>

<p>In erat. Pellentesque erat. Mauris vehicula vestibulum justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla pulvinar est. Integer urna. Pellentesque pulvinar dui a magna. Nulla facilisi. Proin imperdiet. Aliquam ornare, metus vitae gravida dignissim, nisi nisl ultricies felis, ac tristique enim pede eget elit. Integer non erat nec turpis sollicitudin malesuada. Vestibulum dapibus. Nulla facilisi. Nulla iaculis, leo sit amet mollis luctus, sapien eros consectetur dolor, eu faucibus elit nibh eu nibh. Maecenas lacus pede, lobortis non, rhoncus id, tristique a, mi. Cras auctor libero vitae sem vestibulum euismod. Nunc fermentum.</p>

<p>Mauris lobortis. Aliquam lacinia purus. Pellentesque magna. Mauris euismod metus nec tortor. Phasellus elementum, quam a euismod imperdiet, ligula felis faucibus enim, eu malesuada nunc felis sed turpis. Morbi convallis luctus tortor. Integer bibendum lacinia velit. Suspendisse mi lorem, porttitor ut, interdum et, lobortis a, lectus. Phasellus vitae est at massa luctus iaculis. In tincidunt.</p>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_8.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg
