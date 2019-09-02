---
title: Epsilon: Recreating the Demo - New Products
description: Your Guide to Recreating Elements of the Epsilon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/epsilon:Epsilon

---

New Products
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `New Products` |  
| Show Title | Show           |  
| Position   | extension-a    |  
| Status     | Published      |  
| Access     | Public         |  
| Language   | All            |  
| Note       | Blank          |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-width-80">An overview of the latest Joomla template offerings from RocketTheme, available for individual purchase or part of a club subscription.</div>

<div class="gantry-width-25 gantry-width-block">
    <div class="gantry-width-spacer">
        <svg class="rt-hexagon-svg" width="250px" height="250px" viewBox = "0 0 200 200" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1">
            <g>
               <clipPath id="rt-hexagon-mask-7">
                  <polygon points="99.9999999999999,196 16.8615612366939,148 16.8615612366939,52 100,4 183.138438763306,52 183.138438763306,148" />
               </clipPath>
            </g> 
            <a xlink:href="#">
             <image clip-path="url(#rt-hexagon-mask-7)" height="100%" width="100%" xlink:href="images/rocketlauncher/frontpage/extension/img1.jpg" />
            </a>
        </svg> 

        <h5 class="rt-uppercase nomarginbottom rt-regular-text">Anacron</h5>
        <h5 class="rt-small-text nomargintop">Responsive</h5>
        <div class="rt-divider"></div>
        <div class="rt-price rt-light-text">$49</div>
        <p class="rt-small-text">Anacron is a vibrant, highly adaptable and engaging template, ideal for many sites, from community to business.</p>
    </div>
</div>

<div class="gantry-width-25 gantry-width-block">
    <div class="gantry-width-spacer">
        <svg class="rt-hexagon-svg" width="250px" height="250px" viewBox = "0 0 200 200" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1">
            <g>
               <clipPath id="rt-hexagon-mask-8">
                  <polygon points="99.9999999999999,196 16.8615612366939,148 16.8615612366939,52 100,4 183.138438763306,52 183.138438763306,148" />
               </clipPath>
            </g> 
            <a xlink:href="#">
             <image clip-path="url(#rt-hexagon-mask-8)" height="100%" width="100%" xlink:href="images/rocketlauncher/frontpage/extension/img2.jpg" />
            </a>
        </svg> 

        <h5 class="rt-uppercase nomarginbottom rt-regular-text">Hadron</h5>
        <h5 class="rt-small-text nomargintop">Color Chooser</h5>
        <div class="rt-divider"></div>
        <div class="rt-price rt-light-text">$49</div>
        <p class="rt-small-text">Hadron is a contemporary, conservative and flat design direction with new and rich animations.</p>
    </div>
</div>

<div class="gantry-width-25 gantry-width-block">
    <div class="gantry-width-spacer">
        <svg class="rt-hexagon-svg" width="250px" height="250px" viewBox = "0 0 200 200" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1">
            <g>
               <clipPath id="rt-hexagon-mask-9">
                  <polygon points="99.9999999999999,196 16.8615612366939,148 16.8615612366939,52 100,4 183.138438763306,52 183.138438763306,148" />
               </clipPath>
            </g> 
            <a xlink:href="#">
             <image clip-path="url(#rt-hexagon-mask-9)" height="100%" width="100%" xlink:href="images/rocketlauncher/frontpage/extension/img3.jpg" />
            </a>
        </svg> 

        <h5 class="rt-uppercase nomarginbottom rt-regular-text">Paradigm</h5>
        <h5 class="rt-small-text nomargintop">Icon Driven</h5>
        <div class="rt-divider"></div>
        <div class="rt-price rt-light-text">$49</div>
        <p class="rt-small-text">Paradigm is a rich infusion of elegant transparency with a modern frame, to create an invigorating site.</p>
    </div>
</div>

<div class="gantry-width-25 gantry-width-block">
    <div class="gantry-width-spacer">
        <svg class="rt-hexagon-svg" width="250px" height="250px" viewBox = "0 0 200 200" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1">
            <g>
               <clipPath id="rt-hexagon-mask-10">
                  <polygon points="99.9999999999999,196 16.8615612366939,148 16.8615612366939,52 100,4 183.138438763306,52 183.138438763306,148" />
               </clipPath>
            </g> 
            <a xlink:href="#">
             <image clip-path="url(#rt-hexagon-mask-10)" height="100%" width="100%" xlink:href="images/rocketlauncher/frontpage/extension/img4.jpg" />
            </a>
        </svg> 
        
        <h5 class="rt-uppercase nomarginbottom rt-regular-text">Spectral</h5>
        <h5 class="rt-small-text nomargintop">Header Images</h5>
        <div class="rt-divider"></div>
        <div class="rt-price rt-light-text">$49</div>
        <p class="rt-small-text">Spectral echoes modern approaches to create an elegant frame, focusing on content and excellence.</p>
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

[demo]: assets/demo_7.jpeg
[demo2]: assets/demo_7a.jpeg
[demo3]: assets/demo_7b.jpeg
[demo4]: assets/demo_7c.jpeg
