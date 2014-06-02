---
title: Osmosis: Recreating the Demo - Featured Article
description: Your Guide to Recreating Elements of the Osmosis Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/osmosis:Osmosis

---

Featured Article
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** and **Display Mainbody** options have been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Osmosis -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

In order to show a featured article on the front page, we placed a `2` in the **Intro Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. As there is only one featured article, only one appears on the front page.

Article Properties
-----

The **Featured Article** is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

>> NOTE: Any articles are best handled using either RokPad or no editor as other editors (especially WYSIWYG) can cause unwanted code stripping.

Here is the **Article Text** we used:

~~~ .html
<div class="box5">
	<div class="gantry-width-container">
	<div class="gantry-width-50">
		<div class="fp-featured-content-animate">
				<div class="gantry-width-container">
			<div class="gantry-width-50 fp-featured-content-block">
				<div class="fp-featured-content-image-block">
					<img class="fp-featured-image-01" src="images/rocketlauncher/home/featured-content/img-01.jpg" alt="image" />
					<div class="rt-desc-overlay">
						<div class="rt-icon-badge"><a href="#"><span class="fa fa-search"></span></a></div>
					</div>
				</div>
			</div>
			<div class="gantry-width-50 fp-featured-content-block">
				<div class="fp-featured-content-image-block">
					<img class="fp-featured-image-02" src="images/rocketlauncher/home/featured-content/img-02.jpg" alt="image" />
					<div class="rt-desc-overlay">
						<div class="rt-icon-badge"><a href="#"><span class="fa fa-video-camera"></span></a></div>
					</div>
				</div>
			</div>
			<div class="clear"></div>
			<div class="gantry-width-50 fp-featured-content-block">
				<div class="fp-featured-content-image-block">
					<img class="fp-featured-image-03" src="images/rocketlauncher/home/featured-content/img-03.jpg" alt="image" />
					<div class="rt-desc-overlay">
						<div class="rt-icon-badge"><a href="#"><span class="fa fa-camera"></span></a></div>
					</div>
				</div>
			</div>
			<div class="gantry-width-50 fp-featured-content-block">
				<div class="fp-featured-content-image-block">
					<img class="fp-featured-image-04" src="images/rocketlauncher/home/featured-content/img-04.jpg" alt="image" />
					<div class="rt-desc-overlay">
						<div class="rt-icon-badge"><a href="#"><span class="fa fa-comment"></span></a></div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<div class="gantry-width-50">
		<div class="gantry-width-spacer largepaddingtop largemargintop">
			<p class="rt-text-small nomarginbottom">RokSprocket Extension</p>
			<h2 class="rt-text-large rt-text-white nomarginleft nomarginright">Multiple Layouts &amp; A Custom Administrator</h2>
			<p class="rt-text-white hidden-tablet"><span>RokSprocket is a revolutionary content extension<span class="hidden-large"> with great flexibility</span><span class="visible-large">, offering an extremely flexible and versatile approach to presenting content</span>.</span></p>
			<p class="rt-text-small"><span>The custom interface is intuitive and extensive, allowing you to quickly setup your content in varying ways<span class="hidden-tablet">, with drag n drop, ajax and dynamic filters</span>.</span></p>
			<a href="#" class="readon">Read More</a>
		</div>
	</div>
	</div>
	<div class="clear"></div>
</div>
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

[demo]: assets/demo_5.jpeg
[advanced]: assets/setadvanced.jpeg
[menu]: assets/menu.jpeg
