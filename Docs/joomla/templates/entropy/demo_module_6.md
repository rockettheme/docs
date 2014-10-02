---
title: Entropy: Recreating the Demo - HomePage Location
description: Your Guide to Recreating Elements of the Entropy Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/entropy:Entropy

---

HomePage Location
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `HomePage Location`  |  
| Show Title | Hide                 |  
| Position   | mainbottom-a         |  
| Status     | Published            |  
| Access     | Public               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-map box2">
  <div class="rt-block">
    <img src="images/stories/demo/frontpage/frontpage-map.png" alt="Location Map" width="423" height="347" />
  </div>
</div>
<div class="rt-demo-location">
  <h3 class="fancy-text">Location:</h3>
  <div class="rt-demo-title">
    The Brooklyn<br />
    Conference Center
  </div>
  <div class="rt-demo-address">
    East 27 Street and Campus Road,<br />
    Brooklyn, NY 11210
  </div>
  <div class="rt-demo-phone">
    Phone: 555.951.5528  
  </div>
  <p>
    Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem .
  </p>
</div>
<div class="clear"></div>
<div class="rt-demo-prices">
  <h3 class="fancy-text">Tickets &amp; Prices</h3>
  <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem .</p>
  <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem .</p>
</div>
<div class="rt-demo-register">
  <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem .</p>
  
  <p class="rt-demo-buttons">
    <span class="rt-demo-price text-accent">$299</span>
    <a class="readon"><span>Register Now</span></a>
  </p>
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

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_6.jpeg
[demo2]: assets/demo_6a.jpeg
[demo3]: assets/demo_6b.jpeg
[demo4]: assets/demo_6c.jpeg