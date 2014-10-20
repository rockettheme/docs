---
title: Chapelco: Recreating the Demo - Popular Templates
description: Your Guide to Recreating Elements of the Chapelco Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chapelco:Chapelco

---

Popular Templates
-----
![][demo]
We used a **mod_custom** module to make up the content in the **bottom-a** position of the front page. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                              |  
| :--------- | :--------------------------------------------------- |  
| Title      | Popular [span class="hidden-tablet"]Templates[/span] |  
| Show Title | Hide                                                 |  
| Position   | bottom-a                                             |  
| Status     | Published                                            |  
| Access     | Public                                               |  
| Language   | All                                                  |  
| Note       | Blank                                                |  

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="rt-image rt-center">
  <img class="fp-img-light rt-noborder" src="images/rocketlauncher/frontpage/bottom/img-light.jpg" alt="image">
  <img class="fp-img-dark rt-noborder" src="images/rocketlauncher/frontpage/bottom/img-dark.jpg" alt="image">
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

| Option              | Setting                              |  
| :------------------ | :----------------------------------- |  
| Module Class Suffix | `horiztitle fp-popular hidden-phone` |  

[demo]: assets/demo_7.jpeg
[demo2]: assets/templates_1.jpeg
[demo3]: assets/templates_2.jpeg
[demo4]: assets/templates_3.jpeg
