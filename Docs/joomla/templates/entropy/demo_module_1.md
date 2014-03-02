---
title: Entropy: Recreating the Demo - HomePage Text
description: Your Guide to Recreating Elements of the Entropy Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/entropy:Entropy

---

HomePage Text
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `HomePage Text`      |  
| Show Title | Hide                 |  
| Position   | header-b             |  
| Status     | Published            |  
| Access     | Public               |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-header">
  <span class="headline">Hyperactive
    <span class="subline">March <strong>15-17</strong>, Brooklyn, NY, USA</span>
  </span>
  
  
  <div class="rt-demo-counts">
    <div class="rt-demo-count">
      <span>38</span>
      <em class="text-accent">Sessions</em>
    </div>
    <div class="rt-demo-count">
      <span>03</span>
      <em class="text-accent">Days</em>
    </div>
    <div class="rt-demo-count">
      <span>12</span>
      <em class="text-accent">Speakers</em>
    </div>
    <div class="rt-demo-count">
      <span>06</span>
      <em class="text-accent">Parties</em>
    </div>  
  </div>
  <div class="rt-demo-button">
    <div>
      <a href="#" class="readon"><span>Find out More</span></a>
    </div>
    <div>
      <a href="#" class="readon"><span>Register to Attend</span></a>
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

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
