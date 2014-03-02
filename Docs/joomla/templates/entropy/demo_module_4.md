---
title: Entropy: Recreating the Demo - HomePage Speaker 1
description: Your Guide to Recreating Elements of the Entropy Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/entropy:Entropy

---

HomePage Speaker 1
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting              |  
| :--------- | :------------------- |  
| Title      | `HomePage Speaker 1` |  
| Show Title | Hide                 |  
| Position   | maintop-a            |  
| Status     | Published            |  
| Access     | Public               |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-speakers">
  <div class="rt-demo-speaker">
    <div class="rt-demo-avatar box2">
      <div class="rt-block">
        <img src="images/stories/demo/frontpage/frontpage-face1.jpg" class="image-rounded" alt="Speaker 1" />
        <a class="readon" href="#"><span>Full Bio</span></a>
      </div>
    </div>
    <div class="rt-demo-bio">
      <h3><a href="#">Jeremiah Shawcross</a></h3>
      <h4>CEO &amp; Founder<br />SCDesign</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec in imperdiet dui. Cum sociis natoque penatibus et magnis dis parturient montes, <a href="#">nascetur ridiculus</a> mus. Aenean scelerisque justo odio. Cras a lectus in nunc varius aliquet.</p>
      
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

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_4a.jpeg
[demo3]: assets/demo_4b.jpeg
[demo4]: assets/demo_4c.jpeg