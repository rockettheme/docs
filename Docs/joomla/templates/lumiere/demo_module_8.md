---
title: Lumiere: Recreating the Demo - Popular Templates
description: Your Guide to Recreating Elements of the Lumiere Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lumiere:Lumiere

---

Popular Templates
-----
![][demo]

We used a **mod_custom** module to make up the content in the **bottom-a** position of the front page. You will find the settings used in our demo below.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | Popular Templates  |  
| Show Title        | Hide               |  
| Position          | bottom-a           |  
| Status            | Published          |  
| Access            | Public             |   
| Language          | All                |  
| Note              | Blank              |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="gantry-width-block demo-width-100 nomarginbottom">
  <div class="gantry-width-30 gantry-width-block">
  	<div class="gantry-width-spacer">
  		<p class="promo-title title fp-popular-template">Popular Templates</p>
	</div>   	 	
  </div>
  <div class="gantry-width-70 gantry-width-block">
  	<div class="gantry-width-spacer">
		<p class="rt-image">
		  <img class="fp-img-light rt-noborder" src="images/rocketlauncher/frontpage/bottom/img-light.jpg" alt="image">
		  <img class="fp-img-dark rt-noborder" src="images/rocketlauncher/frontpage/bottom/img-dark.jpg" alt="image">
		</p>
	</div>
  </div>
</div>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                               |  
| :------------------ | :------------------------------------ |  
| Module Class Suffix | nomarginleft nomargintop nopaddingtop |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/popular_1.jpeg
[demo3]: assets/popular_2.jpeg
[demo4]: assets/popular_3.jpeg