---
title: Anacron: Recreating the Demo - FP Extension
description: Your Guide to Recreating Elements of the Anacron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Anacron:Anacron

---

FP Extension
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `FP Extension` |  
| Show Title | Hide           |  
| Position   | extension-a    |  
| Status     | Published      |  
| Access     | Public         |  
| Language   | All            |  
| Note       | Blank          |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-width-20 gantry-width-block">
    <div class="gantry-width-spacer">
        <p class="rt-center">
            <img src="images/rocketlauncher/frontpage/extension/img1.png" alt="image" />
        </p>
    </div>
</div>
<div class="gantry-width-20 gantry-width-block">
    <div class="gantry-width-spacer">
        <p class="rt-center">
            <img src="images/rocketlauncher/frontpage/extension/img2.png" alt="image" />
        </p>
    </div>
</div>
<div class="gantry-width-20 gantry-width-block">
    <div class="gantry-width-spacer">
        <p class="rt-center">
            <img src="images/rocketlauncher/frontpage/extension/img3.png" alt="image" />
        </p>
    </div>
</div>
<div class="gantry-width-20 gantry-width-block">
    <div class="gantry-width-spacer">
        <p class="rt-center">
            <img src="images/rocketlauncher/frontpage/extension/img4.png" alt="image" />
        </p>
    </div>
</div>
<div class="gantry-width-20 gantry-width-block">
    <div class="gantry-width-spacer">
        <p class="rt-center">
            <img src="images/rocketlauncher/frontpage/extension/img5.png" alt="image" />
        </p>
    </div>
</div>
<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                  |  
| :------------------ | :----------------------- |  
| Module Class Suffix | `fp-extension rt-center` |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/client_1.jpeg
[demo3]: assets/client_2.jpeg
[demo4]: assets/client_3.jpeg