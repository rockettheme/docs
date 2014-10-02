---
title: Omnicron: Recreating the Demo - Product Blog
description: Your Guide to Recreating Elements of the Omnicron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/omnicron:Omnicron

---

Product Blog
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting             |  
| :--------- | :------------------ |  
| Title      | `Product Blog`      |  
| Show Title | Show                |  
| Position   | bottom-c            |  
| Status     | Published           |  
| Access     | Public              |  

### Custom Output

~~~ .html
<ul class="bullet-latest">
  <li>
    <span class="list-time">
      <span class="list-date">05</span>
      <span class="list-month">Sep</span>
      <span class="list-year">2010</span>
    </span>
    <a href="#">MAINTENANCE: We will be performing a scheduled maintenance of all our servers on 14 Sep 2010 at 00.00 EST.</a>
  </li>
  <li>
    <span class="list-time">
      <span class="list-date">31</span>
      <span class="list-month">Aug</span>
      <span class="list-year">2010</span>
    </span>
    <a href="#">BLOG: Net Neutrality is a popular political topic at present, and we stand by its main aims, to ensure freedom is maintained.</a>
  </li>
  <li>
    <span class="list-time">
      <span class="list-date">27</span>
      <span class="list-month">Aug</span>
      <span class="list-year">2010</span>
    </span>
    <a href="#">PRODUCT: We are pleased to offer a new spam protection system for all our clients, with a 30% off introductory offer.</a>
  </li>
</ul>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting  |  
| :------------------ | :------- |  
| Module Class Suffix | `box4`   |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg
