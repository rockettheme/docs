---
title: Corvus: Recreating the Demo - Inside Corvus
description: Your Guide to Recreating Elements of the Corvus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/corvus:Corvus

---

Inside Corvus
----
![][demo]
This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting         |  
| :--------- | :-------------- |  
| Title      | `Inside Corvus` |  
| Show Title | Show            |  
| Position   | footer-b        |  
| Status     | Published       |  
| Language   | All             |  
| Note       | Blank           |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="largemargintop largepaddingtop largemarginbottom largepaddingbottom">
    <div class="gantry-width-50 gantry-width-block">
        <ul class="fp-footer-menu rt-uppercase">
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=108">Features</a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=2&amp;Itemid=109">Positions</a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=3&amp;Itemid=110">Variations</a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=4&amp;Itemid=111">Typography</a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=112">Menu<span class="hidden-tablet"> Options</span></a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113">Extensions</a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=114">Tutorials</a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=115">Installation</a></li>		
		</ul>
	</div>

	<div class="gantry-width-50 gantry-width-block">
		<ul class="fp-footer-menu rt-uppercase">
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=9&amp;Itemid=116">Logo <span class="hidden-tablet">Editing</span></a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=114"><span class="hidden-tablet">Forum</span> Guides</a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=114">Gantry</a></li>						
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=117">Preset Styles</a></li>
			<li><a href="index.php?option=com_content&amp;view=article&amp;id=11&amp;Itemid=118">J! Stuff</a></li>
			<li><a href="index.php?option=com_users&amp;view=login&amp;Itemid=123"><span class="hidden-tablet">Member</span> Access</a></li>
			<li><a href="index.php?option=com_content&amp;view=category&amp;layout=blog&amp;id=12&amp;Itemid=124"><span class="hidden-tablet">Category</span> Blog</a></li>
			<li><a href="index.php?option=com_weblinks&amp;view=category&amp;id=16&amp;Itemid=125">Web Links</a></li>
		</ul>
	</div>
	
	<div class="clear"></div>
</div>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                         |  
| :------------------ | :------------------------------ |  
| Module Class Suffix | `fp-footer-b box6 hidden-phone` |  

[demo]: assets/demo_12.jpeg
[demo2]: assets/inside_1.jpeg
[demo3]: assets/inside_2.jpeg
[demo4]: assets/inside_3.jpeg