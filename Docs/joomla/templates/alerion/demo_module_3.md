---
title: Alerion: Recreating the Demo - Your Tickets Here
description: Your Guide to Recreating Elements of the Alerion Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

Your Tickets Here
-----
![][demo]

:   1. **mod_custom** [12%, 20%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present in the title field. See the main [Recreate the Demo][recreate] page for additional instructions.

### Details
![][demo2]

| Option            | Setting                                                                              |  
| :---------------- | :----------------------------------------------------------------------------------- |  
| Title             | [span class="icon-tags"][/span] Your Tickets[span class="hidden-tablet"] Here[/span] |  
| Show Title        | Hide                                                                                 |  
| Position          | floatingmodule-top                                                                   |  
| Status            | Published                                                                            |  
| Access            | Public                                                                               |  
| Language          | All                                                                                  |  
| Note              | Blank                                                                                |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-eventlist">
    <div class="gantry-width-70 gantry-width-block">
		<span><strong>Space Needle</strong></span><br>
		<span><em class="hidden-tablet">Brooklyn</em> <strong>FRI, FEB 29</strong>, 2013</span>
	</div>

	<div class="gantry-width-30 gantry-width-block">
		<div class="rt-floatright">
			<span class="rt-price"><span class="rt-currency">$</span>75</span>
		</div>	
	</div>

	<div class="clear"></div>
	<div class="rt-dotted-divider"></div>

	<div class="gantry-width-70 gantry-width-block">
		<span><strong>New York</strong></span><br>
		<span><em class="hidden-tablet">NY</em> <strong>MON, MAR 04</strong>, 2013</span>
	</div>

	<div class="gantry-width-30 gantry-width-block">
		<div class="rt-floatright">
			<span class="rt-price"><span class="rt-currency">$</span>85</span>
		</div>	
	</div>

	<div class="clear"></div>
	<div class="rt-dotted-divider"></div>

	<div class="gantry-width-70 gantry-width-block">
		<span><strong>Brooklyn</strong></span><br>
		<span><em class="hidden-tablet">Brooklyn</em> <strong>THU, MAR 21</strong>, 2013</span>
	</div>

	<div class="gantry-width-30 gantry-width-block">
		<div class="rt-floatright">
			<span class="rt-price"><span class="rt-currency">$</span>95</span>
		</div>	
	</div>

	<div class="clear"></div>
</div>

<div class="rt-order">
	<div class="gantry-width-50 gantry-width-block rt-center">
		<img alt="image" src="images/rocketlauncher/frontpage/showcase/cards.jpg" class="largemargintop">
	</div>

	<div class="gantry-width-50 gantry-width-block">
		<div class="rt-floatright">
			<script>
			window.addEvent('domready', function(){
			    var x = new Fx.Scroll(window, {
			        wheelStop: false, 
			        duration: 8000, 
			        transition: 'quad:in:out',
			        onComplete: function(){
			            if (window.getScroll().y > 0) x.start(0, 0);
			        }
			    });
			    $('rt-quicktour').addEvent('click', function(){
			        x.start(0, window.getScrollSize().y);
			    });
			});
			</script>			
			<a id="rt-quicktour" class="btn btn-large btn-primary rt-large-button" href="#"><span class="hidden-tablet">Quick </span>Tour</a>
		</div>		
	</div>

	<div class="clear"></div>
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

| Option              | Setting                              |  
| :------------------ | :----------------------------------- |  
| Module Class Suffix | `box1 title3 jagged fp-floating-top` |  

[demo]: assets/demo_3.jpeg
[demo2]: assets/tickets_1.jpeg
[demo3]: assets/tickets_2.jpeg
[demo4]: assets/tickets_3.jpeg
[recreate]: demo.md#rokcandy