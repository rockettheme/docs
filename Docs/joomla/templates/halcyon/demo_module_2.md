---
title: Halcyon: Recreating the Demo - Sample Cart
description: Your Guide to Recreating Elements of the Halcyon Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/halcyon:Halcyon

---

Sample Cart
-----

![][demo]

:   1. **mod_custom** [19%, 79%, se]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting           |  
| :--------- | :---------------- |  
| Title      | `Sample Cart`     |  
| Show Title | Show              |  
| Position   | top-b             |  
| Status     | Published         |  
| Access     | Public            |  
| Language   | All               |  
| Note       | Blank             |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="cart-badge"><div class="cart-badge-inner">
        <div class="cart-count">0</div>
        <div class="cart-title">Shopping Cart</div>
        <div class="cart-desc"><a href="#">Info on Ecwid eCommerce.</a></div>
</div></div>
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

[demo]: assets/demo_1.jpeg
[demo2]: assets/samplecart_1.jpeg
[demo3]: assets/samplecart_2.jpeg
[demo4]: assets/samplecart_3.jpeg