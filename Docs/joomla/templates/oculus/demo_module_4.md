---
title: Oculus: Recreating the Demo - FP Showcase A
description: Your Guide to Recreating Elements of the Oculus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/oculus:Oculus

---

FP Showcase A
-----
![][showcase]
We used a **mod_custom** module to make up the content in the **showcase-a** position of the front page. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][showcase1]

| Option | Setting |
|:------|:-------|
| Title | FP Showcase A |
| Show Title | Hide |
| Position | showcase-a |
| Status | Published |
| Access | Public |
| Ordering | FP Showcase A |
| Start Publishing | 0000-00-00 00:00:0 |
| Finish Publishing | 0000-00-00 00:00:0 |
| Language | All |
| Note | Blank |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-33 gantry-width-block">
	<div class="gantry-width-25 gantry-width-block">
	  <div class="rt-image"><img src="images/rocketlauncher/frontpage/showcase/img1.jpg" alt="image"></div>
	</div>

	<div class="gantry-width-75 gantry-width-block">
	  <div class="largemarginleft medpaddingright">
	    <h5 class="nomargintop smallmarginbottom"><span class="hidden-tablet">Showcase</span><span class="visible-tablet">Features</span></h5>
		<small>Showcase layout type<span class="hidden-tablet"> for images / content</span>.</small>
	  </div>
	</div>
</div>	

<div class="gantry-width-33 gantry-width-block">
	<div class="gantry-width-25 gantry-width-block">
	  <div class="rt-image"><img src="images/rocketlauncher/frontpage/showcase/img2.jpg" alt="image"></div>
	</div>

	<div class="gantry-width-75 gantry-width-block">
	  <div class="largemarginleft medpaddingright">
	    <h5 class="nomargintop smallmarginbottom"><span class="hidden-tablet">Tabbed Items</span><span class="visible-tablet">Tabs</span></h5>
	    <small>Display your content in <span class="hidden-tablet">dynamic </span>tabs.</small>
	  </div>
	</div>
</div>	

<div class="gantry-width-33 gantry-width-block">
	<div class="gantry-width-25 gantry-width-block">
	  <div class="rt-image"><img src="images/rocketlauncher/frontpage/showcase/img3.jpg" alt="image"></div>
	</div>

	<div class="gantry-width-75 gantry-width-block">
	  <div class="largemarginleft medpaddingright">
	    <h5 class="nomargintop smallmarginbottom"><span class="hidden-tablet">Accordion</span><span class="visible-tablet">Lists</span></h5>
	    <small>Show content in<span class="hidden-tablet"> static or dynamic</span> lists.</small>
	  </div>
	</div>
</div>	

<div class="clear"></div>
~~~

### Basic
![][showcase2]

| Option | Setting |
|:------|:-------|
| Prepare Content | No |
| Select a Background Image | Blank |

### Advanced
![][showcase3]

| Option | Setting |
|:------|:-------|
| Alternative Layout | Default |
| Module Class Suffix | box2 nomarginleft fp-showcase-a hidden-phone |
| Caching | Use Global |
| Cache Time | 900 |

[showcase]: assets/demo_module_3.jpeg
[showcase1]: assets/fp_showcase_1.jpeg
[showcase2]: assets/fp_showcase_2.jpeg
[showcase3]: assets/fp_showcase_3.jpeg
[showcase4]: assets/fp_showcase_4.jpeg
