---
title: Osmosis: Recreating the Demo - FP Footer C
description: Your Guide to Recreating Elements of the Osmosis Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/osmosis:Osmosis

---

FP Footer C
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting       |
| :---------- | :----------   |
| Title       | `FP Footer C` |
| Show Title  | Hide          |
| Position    | footer-c      |
| Status      | Published     |
| Access      | Public        |

### Custom Output

~~~ .html
<div class="gantry-row smallmargintop">
	<div class="gantry-width-container">
		<div class="gantry-width-50">
			<div class="gantry-width-spacer smallmarginleft">
				<h5 class="medmarginall"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Features</a></h5>
				<h5 class="medmarginall"><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=113">Modules</a></h5>
				<h5 class="medmarginall"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=118">Pages</a></h5>
				<h5 class="medmarginall hidden-tablet"><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114">Typography</a></h5>
			</div>
		</div>

		<div class="gantry-width-50">
			<div class="gantry-width-spacer smallmarginleft">
				<h5 class="medmarginall"><a href="http://www.rockettheme.com/docs/joomla/templates/osmosis">Tutorial</a></h5>
				<h5 class="medmarginall"><a href="http://www.rockettheme.com/forum/joomla-template-osmosis">Forum</a></h5>
				<h5 class="medmarginall hidden-tablet"><a href="http://www.rockettheme.com/joomla/templates/osmosis">Download</a></h5>
				<h5 class="medmarginall"><a href="http://www.rockettheme.com/joomla/templates/osmosis">Buy</a></h5>
			</div>
		</div>
	</div>
</div>

<div class="clear smallmarginbottom"></div>

<p class="rt-text-small">&copy; <span class="hidden-tablet">Designed </span>by <a href="http://www.rockettheme.com/">RocketTheme</a>.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting            |
| :----------         | :----------        |
| Module Class Suffix | `fp-footer-c box3` |

[demo]: assets/demo_9.jpeg
[demo2]: assets/demo_9a.jpeg
[demo3]: assets/demo_9b.jpeg
[demo4]: assets/demo_9c.jpeg
