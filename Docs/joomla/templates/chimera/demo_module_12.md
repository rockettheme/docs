---
title: Chimera: Recreating the Demo - Learn More About Chimera
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

Learn More About Chimera
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                    |  
| :--------- | :------------------------- |  
| Title      | `Learn More About Chimera` |  
| Show Title | Show                       |  
| Position   | bottom-a                   |  
| Status     | Published                  |  
| Access     | Public                     |  

### Custom Output

~~~ .html
<div class="gantry-width-container">
  <div class="gantry-width-75 wow fadeInLeft">
    <div class="rt-float-left largemarginright">
      <div class="gantry-width-75">
        <p>Get more information about this incredible theme, its features, and discover all the ways that it can help you with your future projects.</p>
      </div>
    </div>
  </div>
  <div class="gantry-width-25 wow fadeInRight" data-wow-delay="1s">
    <div class="rt-floatright">
      <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111" class="readon wow pulse" data-wow-delay="2s">Learn More</a>
    </div>
  </div>  
  <div class="clear"></div>
</div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                                         |  
| :------------------ | :---------------------------------------------- |  
| Module Class Suffix | `wow fadeIn largepaddingtop largepaddingbottom` |  

[demo]: assets/demo_12.jpeg
[demo2]: assets/demo_12a.jpeg
[demo3]: assets/demo_12b.jpeg
[demo4]: assets/demo_12c.jpeg
