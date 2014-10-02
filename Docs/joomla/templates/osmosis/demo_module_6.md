---
title: Osmosis: Recreating the Demo - FP Content Bottom
description: Your Guide to Recreating Elements of the Osmosis Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/osmosis:Osmosis

---

FP Content Bottom
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting             |
| :---------- | :----------         |
| Title       | `FP Content Bottom` |
| Show Title  | Hide                |
| Position    | content-bottom-a    |
| Status      | Published           |
| Access      | Public              |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-container">
	<div class="gantry-width-50">
		<div class="gantry-width-spacer largepaddingtop largemargintop medpaddingleft">
			<h2>Additional Materials</h2>
			<p>Use a selection of included extras to help setup and modify Osmosis.</p>
			<hr class="clear" />

			<h4 class="nomarginbottom"><span class="rt-icon-left fa fa-picture-o"></span> <a href="#">Image Sources</a></h4>
			<p class="rt-text-small">Adobe Fireworks&reg; <span class="hidden-tablet">Layered </span>PNG Sources.</p>
			<hr class="clear hidden-tablet" />

			<h4 class="nomarginbottom hidden-tablet"><span class="rt-icon-left fa fa-file-text-o"></span> <a href="#">RocketLaunchers</a></h4>
			<p class="rt-text-small hidden-tablet">Install a near equivalent of the demo.</p>
			<hr class="clear visible-large" />

			<h4 class="nomarginbottom visible-large"><span class="rt-icon-left fa fa-sitemap"></span> <a href="#">Documentation</a></h4>
			<p class="rt-text-small visible-large">A wide selection of free, online guides.</p>
		</div>
	</div>
	<div class="gantry-width-50">
		<div class="fp-content-bottom-animate">
			<div class="gantry-width-container">
				<div class="gantry-width-50 fp-content-bottom-block">
					<div class="fp-content-bottom-image-block">
						<img class="fp-content-bottom-image-01" src="images/rocketlauncher/home/fp-content-bottom/img-01.jpg" alt="image" />
						<div class="rt-desc-overlay">
							<h3>Icons</h3>
							<p class="rt-text-small smallmarginbottom hidden-tablet">Powered by Font Awesome<span><span class="visible-large">, with 350+ icons</span></span></p>
							<a class="rt-text-small" href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=114"><span class="fa fa-arrow-circle-right"></span> Learn More</a>
						</div>
					</div>
				</div>
				<div class="gantry-width-50 fp-content-bottom-block">
					<div class="fp-content-bottom-image-block">
						<img class="fp-content-bottom-image-02" src="images/rocketlauncher/home/fp-content-bottom/img-02.jpg" alt="image" />
						<div class="rt-desc-overlay">
							<h3>Offline</h3>
							<p class="rt-text-small smallmarginbottom hidden-tablet">Unique Coming Soon Page<span><span class="visible-large">, with countdown</span></span></p>
							<a class="rt-text-small" href="/?tmpl=comingsoon"><span class="fa fa-arrow-circle-right"></span> Learn More</a>
						</div>
					</div>
				</div>
				<div class="gantry-width-50 fp-content-bottom-block">
					<div class="fp-content-bottom-image-block">
						<img class="fp-content-bottom-image-03" src="images/rocketlauncher/home/fp-content-bottom/img-03.jpg" alt="image" />
						<div class="rt-desc-overlay">
							<h3>ChartJS</h3>
							<p class="rt-text-small smallmarginbottom hidden-tablet">Create exquisite charts<span><span class="visible-large"> using HTML5 canvas</span></span></p>
							<a class="rt-text-small" href="index.php?option=com_content&amp;view=article&amp;id=9&amp;Itemid=121"><span class="fa fa-arrow-circle-right"></span> Learn More</a>
						</div>
					</div>
				</div>
				<div class="gantry-width-50 fp-content-bottom-block">
					<div class="fp-content-bottom-image-block">
						<img class="fp-content-bottom-image-04" src="images/rocketlauncher/home/fp-content-bottom/img-04.jpg" alt="image" />
						<div class="rt-desc-overlay">
							<h3>Pages</h3>
							<p class="rt-text-small smallmarginbottom hidden-tablet">Several layout examples <span><span class="visible-large">to demo versatility</span></span></p>
							<a class="rt-text-small" href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=118"><span class="fa fa-arrow-circle-right"></span> Learn More</a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting             |
| :----------         | :----------         |
| Module Class Suffix | `fp-content-bottom` |

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg
