---
title: Paradigm: Recreating the Demo - Mobile Ready
description: Your Guide to Recreating Elements of the Paradigm Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradigm:Paradigm

---

Mobile Ready
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below. Due to the `visible-phone` Module Class Suffix setting, this module will only appear once the width of the browser has dropped to 480 pixels and below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting             |  
| :--------- | :------------------ |  
| Title      | `Mobile Ready`      |  
| Show Title | Hide                |  
| Position   | feature-a           |  
| Status     | Published           |  
| Access     | Public              |  
| Language   | All                 |  
| Note       | Blank               |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="module-title">
  <h2 class="title">Mobile Ready<span class="rt-title-tag">The responsive layout allows the site to adapt to mobile layout.</span></h2>
</div>

<img src="images/rocketlauncher/frontpage/feature/img1.png" alt="image" />
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                                           |  
| :------------------ | :------------------------------------------------ |  
| Module Class Suffix | `fp-feature rt-big-title rt-center visible-phone` |  

[demo]: assets/demo_10.jpeg
[demo2]: assets/template_1.jpeg
[demo3]: assets/template_2.jpeg
[demo4]: assets/template_3.jpeg