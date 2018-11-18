---
title: Chimera: Recreating the Demo - FP RokSprocket Strips
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

FP RokSprocket Strips
-----


![][demo]

We used a **RokSprocket** module with the **Strips** layout to make up this area of the front page. You will find the settings used in our demo below.

>> NOTE: If you are using the v1.1 RocketLauncher, there are some special instructions concerning the handling of the preset images for this module. If you notice your images aren't changing as expected, or if you would like more information on how this was set up, you can find it [here](demo.md#roksprocket-and-rocketlauncher-settings).

### Details

![][demo2]

| Option           | Setting                 |  
| :--------------- | :---------------------- |  
| Title            | `FP RokSprocket Strips` |  
| Show Title       | Hide                    |  
| Access           | Public                  |  
| Position         | mainbottom-a            |  
| Status           | Published               |  
| Content Provider | Simple                  |  
| Type             | Strips                  |  

### Simple Item Example

| Option | Setting |  
| :----- | :------ |  
| Title  | None    |  
| Image  | Custom  |  
| Link   | None    |  

#### Description

~~~ .html
<div class="wow zoomIn">
    <div class="rt-floatleft">
        <div class="rt-grey-box fa fa-tachometer" style="font-style: italic"></div>
    </div>

    <div class="rt-strips-desc">
        <h6><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Replicate the demo <span class="hidden-tablet">with the RocketLauncher</span></a></h6><small>Full Joomla Install</small>
    </div>
</div>
~~~

### Layout Options

![][demo3]

| Option            | Setting      |  
| :---------------- | :----------- |  
| Theme             | Default      |  
| Display Limit     | `∞`          |  
| Preview Length    | `∞`          |  
| Strip HTML Tags   | No           |  
| Previews Per Page | `3`          |  
| Items Per Row     | `3`          |  
| Arrow Navigation  | Show         |  
| Pagination        | Show         |  
| Animation         | Fade Delayed |  
| Autoplay          | Disable      |  
| Autoplay Delay    | 5            |  
| Image Resize      | Disable      |  

### Advanced

![][demo4]

| Option              | Setting                 |  
| :------------------ | :---------------------- |  
| Module Class Suffix | `fp-roksprocket-strips` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/demo_8a.jpeg
[demo3]: assets/demo_8b.jpeg
[demo4]: assets/demo_8c.jpeg
