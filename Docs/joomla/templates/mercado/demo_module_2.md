---
title: Mercado: Recreating the Demo - Demo Cart
description: Your Guide to Recreating Elements of the Mercado Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/mercado:Mercado

---

Demo Cart
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting     |  
| :--------- | :---------- |  
| Title      | `Demo Cart` |  
| Show Title | Hide        |  
| Position   | top-d       |  
| Status     | Published   |  
| Access     | Public      |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="cart-badge">
<div class="cart-left"> </div>
<div class="cart-right">
<div class="cart-count">3</div>
<div class="cart-desc"><em class="bold">Shopping Addons</em><br /><a href="index.php?option=com_content&amp;view=article&amp;id=50&amp;Itemid=57">Info on integrated<br />eCommerce addons.</a></div>
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

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_2.jpeg
[demo2]: assets/demo_2a.jpeg
[demo3]: assets/demo_2b.jpeg
[demo4]: assets/demo_2c.jpeg
[demo5]: assets/demo_2d.jpeg
