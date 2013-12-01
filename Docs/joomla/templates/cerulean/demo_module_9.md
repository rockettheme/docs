---
title: Cerulean: Recreating the Demo - Top Features
description: Your Guide to Recreating Elements of the Cerulean Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cerulean:Cerulean

---

Top Features
-----
![][demo]

:   1. **mod_custom** [20%, 40%, se]

We used a **mod_custom** module to make up the content in the **footer-b** position of the front page. You will find the settings used in our demo below.

### Details
![][demo2]

| Option     | Setting                                                           |  
| :--------- | :---------------------------------------------------------------- |  
| Title      | `Top Features. [span class="icon-chevron-down rt-teaser"][/span]` |  
| Show Title | Hide                                                              |  
| Position   | footer-b                                                          |  
| Status     | Published                                                         |  
| Access     | Public                                                            |  
| Language   | All                                                               |  
| Note       | Blank                                                             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="smallpaddingbottom">
    <span class="hidden-tablet"><strong>RokSprocket</strong> is a multi-purpose content module with <strong>integrated</strong> template styling.</span>
    <span class="visible-tablet">RokSprocket is a multi-purpose extension with integrated  styling.</span>
    <br class="hidden-tablet" />
    <small>26 Nov, 2012 17:07</small>
</p>

<p class="rt-dashed-divider"></p>

<p class="smallpaddingtop">    
    <span class="hidden-tablet">The <a href="#">dropdown menu</a> is an advanced CSS driven system with <strong>mobile</strong> support.</span>
	<span class="visible-tablet">The dropdown menu is an advanced CSS driven system.</span>
	<br class="hidden-tablet" />
	<small>23 Nov, 2012 12:46</small>
</p>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                                                                 |  
| :------------------ | :---------------------------------------------------------------------- |  
| Module Class Suffix | `nomarginbottom nopaddingbottom nomargintop medpaddingtop hidden-phone` |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/features_1.jpeg
[demo3]: assets/features_2.jpeg
[demo4]: assets/features_3.jpeg