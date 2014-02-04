---
title: Hexeris: Recreating the Demo - Popular Addons
description: Your Guide to Recreating Elements of the Hexeris Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hexeris:Hexeris

---

Popular Addons
----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                            |
| :--------- | :----------------------------------------------------------------- |
| Title      | `Image Gallery [span class="rt-subtitle"]RocketTheme Fonts[/span]` |
| Show Title | Show                                                               |
| Position   | footer-c                                                           |
| Status     | Published                                                          |
| Access     | Public                                                             |
| Language   | All                                                                |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-25 gantry-width-block rt-center">
  <div class="gantry-width-spacer">
    <a href="#">
		<span class="box1 rt-med-icon">
			<span class="rokicon-cloud"></span>
		</span>
    </a>
  </div>
</div>

<div class="gantry-width-25 gantry-width-block rt-center">
  <div class="gantry-width-spacer">
    <a href="#">
		<span class="box2 rt-med-icon">
			<span class="rokicon-car"></span>
		</span>
    </a>
  </div>
</div>

<div class="gantry-width-25 gantry-width-block rt-center">
  <div class="gantry-width-spacer">
    <a href="#">
		<span class="box3 rt-med-icon">
			<span class="rokicon-image1"></span>
		</span>
    </a>
  </div>
</div>

<div class="gantry-width-25 gantry-width-block rt-center">
  <div class="gantry-width-spacer">
    <a href="#">
		<span class="box4 rt-med-icon">
			<span class="rokicon-bug"></span>
		</span>
    </a>
  </div>
</div>

<div class="clear"></div>

<div class="gantry-width-25 gantry-width-block rt-center">
  <div class="gantry-width-spacer">
    <a href="#">
		<span class="box4 rt-med-icon">
			<span class="rokicon-like"></span>
		</span>
    </a>
  </div>
</div>

<div class="gantry-width-25 gantry-width-block rt-center">
  <div class="gantry-width-spacer">
    <a href="#">
		<span class="box3 rt-med-icon">
			<span class="rokicon-smile1"></span>
		</span>
    </a>
  </div>
</div>

<div class="gantry-width-25 gantry-width-block rt-center">
  <div class="gantry-width-spacer">
    <a href="#">
		<span class="box2 rt-med-icon">
			<span class="rokicon-star2"></span>
		</span>
    </a>
  </div>
</div>

<div class="gantry-width-25 gantry-width-block rt-center">
  <div class="gantry-width-spacer">
    <a href="#">
		<span class="box1 rt-med-icon">
			<span class="rokicon-gift"></span>
		</span>
    </a>
  </div>
</div>

<div class="clear"></div>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                       |  
| :------------------ | :---------------------------- |  
| Module Class Suffix | `fp-footer-icon hidden-phone` |    

[demo]: assets/demo_10.jpeg
[demo2]: assets/gallery_1.jpeg
[demo3]: assets/gallery_2.jpeg
[demo4]: assets/gallery_3.jpeg