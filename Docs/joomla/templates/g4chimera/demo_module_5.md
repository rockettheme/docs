---
title: Chimera: Recreating the Demo - FP RokSprocket Tabs
description: Your Guide to Recreating Elements of the Chimera Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

FP RokSprocket Tabs
-----


![][demo]

This area of the page is a **RokSprocket** module utilizing the **Simple** content provider and the **Tabs** layout.

The settings used in our demo are listed below.

### Details

![][demo2]

| Option           | Setting               |  
| :--------------- | :-------------------- |  
| Title            | `FP RokSprocket Tabs` |  
| Show Title       | Hide                  |  
| Access           | Public                |  
| Position         | expandedtop-a         |  
| Status           | Published             |  
| Content Provider | Simple                |  
| Layout Mode      | Grids                 |  

### Simple Content Provider

The **Tab Label** and **Description** fields in each item have been altered. A few examples of these article changes can be found below.

#### Article 1

**Tab Label**

~~~ .html
Navigation<span class="hidden-tablet"> Options</span>
~~~

**Description**

~~~ .html
<p class="wow zoomIn">Two menu options are available with Chimera, Dropdown Menu and SplitMenu, each with a dedicated responsive mobile menu for full mobile compatibility.</p>

<div class="gantry-row rt-center">
    <div class="gantry-width-container">
        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle wow bounceInUp">
                    <i class="fa fa-file-text-o"></i> <span>Subtext</span>
                </div>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle wow bounceInUp">
                    <i class="fa fa-sitemap"></i> <span>Columns</span>
                </div>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle wow bounceInUp">
                    <i class="fa fa-code"></i> <span>Modules</span>
                </div>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle wow bounceInUp">
                    <i class="fa fa-upload"></i> <span>Icons</span>
                </div>
            </div>
        </div>
    </div>
</div>
~~~

#### Article 2

**Tab Label**

~~~
RokSprocket<span class="hidden-tablet"> Module</span>
~~~

**Description**

~~~ .html
<p>RokSprocket is a powerful content switchblade extension, with custom layouts, themes, an extensive custom UI, multiple content providers and responsive support.</p>

<div class="gantry-row rt-center">
    <div class="gantry-width-container">
        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle">
                    <i class="fa fa-th-list"></i> <span>Themes</span>
                </div>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle">
                    <i class="fa fa-puzzle-piece"></i> <span>Simple</span>
                </div>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle">
                    <i class="fa fa-cog"></i> <span>Control</span>
                </div>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle">
                    <i class="fa fa-arrows-alt"></i> <span>Mobile</span>
                </div>
            </div>
        </div>
    </div>
</div>
~~~

#### Article 3

The third item has a custom image in the **Image** field. This enables the grid item to show up as an image with the **Description** appearing as you move your mouse cursor over it.

**Tab Label**

~~~ .html
Gantry Framework
~~~

**Description**

~~~ .html
<p>Gantry is a powerful core framework that sits at the heart of the Chimera template, providing the base for all features and functions, as well as a rich, user friendly UI.</p>

<div class="gantry-row rt-center">
    <div class="gantry-width-container">
        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle">
                    <i class="fa fa-exchange"></i> <span>Admin</span>
                </div>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle">
                    <i class="fa fa-tasks"></i> <span>Features</span>
                </div>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle">
                    <i class="fa fa-fighter-jet"></i> <span>Fast</span>
                </div>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <div class="rt-icon-circle">
                    <i class="fa fa-spinner"></i> <span>Updates</span>
                </div>
            </div>
        </div>
    </div>
</div>
~~~

### Layout Options

![][demo3]

| Option                | Setting               |  
| :-------------------- | :-------------------- |  
| Theme                 | Default               |  
| Display Limit         | `∞`                   |  
| Tabs Position         | Top                   |  
| Animation             | Slide and Fade        |  
| Autoplay              | Disable               |  
| Autoplay Delay        | `5`                   |  
| Image Resize          | Disable               |  
| Preview Length        | `0`                   |  
| Strip HTML Tags       | No                    |  
| Default Title         | Default Article Title |  
| Default Article Text  | Default Article Text  |  
| Default Article Image | Default Article Image |  
| Default Link          | Default Article Link  |  

### Advanced

![][demo4]

| Option              | Setting               |  
| :------------------ | :-------------------- |  
| Module Class Suffix | `fp-roksprocket-tabs` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg
