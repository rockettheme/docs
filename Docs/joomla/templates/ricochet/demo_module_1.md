---
title: Ricochet: Recreating the Demo - Showcase
description: Your Guide to Recreating Elements of the Ricochet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ricochet:Ricochet

---

![](assets/demo_1.jpeg)

## Three Triangles

The three triangles represented in this area of the page are created using CSS. You can find the CSS source used to create them in the `ROOT/templates/rt_ricochet/less/demo.less` file. The written content in this area is managed using RokSprocket. Details about this are found in the sections below.

## FP RokSprocket Features - Showcase

The **RokSprocket Features** module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest.

### Details

![](assets/demo_1a.jpeg)

|      Option      |               Setting                |
| :--------------- | :----------------------------------- |
| Title            | `FP RokSprocket Features - Showcase` |
| Show Title       | Hide                                 |
| Access           | Public                               |
| Position         | showcase-a                           |
| Status           | Published                            |
| Content Provider | Simple                               |
| Type             | Features                             |

### Filtered Article List

We utilized the **Simple** Content Provider, allowing us to create custom content independent of full articles. The **Title**, **Description**, and **Link** fields in each article have been altered. A few examples of these article changes can be found below.

#### Article 1

**Title**

~~~ .html
An Explosion of Possibilities to Showcase your Data.
~~~

**Description**

~~~ .html
<div class="gantry-width-container">
    <div class="rt-sprocket-text">
        <div class="gantry-width-70 hidden-tablet">
            <p>Ricochet combines an elegant and corporate design with rich
            content visuals to professionally present masses of data.</p>
        </div>

        <div class="gantry-width-60 visible-tablet">
            <p>Ricochet combines an elegant and corporate design with rich
            content visuals to professionally present masses of data.</p>
        </div>
    </div>

    <div class="gantry-width-30">
        <div class="gantry-width-spacer">
            <div class="rt-triangle-set">
                <div class="rt-triangle-1"></div>

                <div class="rt-triangle-2"></div>

                <div class="rt-triangle-3"></div>
            </div>
        </div>
    </div>
</div>
~~~

#### Article 2

**Title**

~~~
An Array of Template Specific Styling for RokSprocket.
~~~

**Description**

~~~ .html
<div class="gantry-width-container">
    <div class="rt-sprocket-text">
        <div class="gantry-width-70 hidden-tablet">
            <p>RokSprocket benefits from a wide range of different layout
            modes, several themes, and many configuration options.</p>
        </div>

        <div class="gantry-width-60 visible-tablet">
            <p>RokSprocket benefits from a wide range of different layout
            modes, several themes, and many configuration options.</p>
        </div>
    </div>

    <div class="gantry-width-30">
        <div class="gantry-width-spacer">
            <div class="rt-triangle-set">
                <div class="rt-triangle-1"></div>

                <div class="rt-triangle-2"></div>

                <div class="rt-triangle-3"></div>
            </div>
        </div>
    </div>
</div>
~~~

#### Article 3

**Title**

~~~ .html
A Fixed or Sliding Position aside the Full Height of the Page.
~~~

**Description**

~~~ .html
<div class="gantry-width-container">
    <div class="rt-sprocket-text">
        <div class="gantry-width-70 hidden-tablet">
            <p>A side module position existing outside of the main wrapper,
            configurable to be either permanently fixed, or via a slider.</p>
        </div>

        <div class="gantry-width-60 visible-tablet">
            <p>A side module position existing outside of the main wrapper,
            configurable to be either permanently fixed, or via a slider.</p>
        </div>
    </div>

    <div class="gantry-width-30">
        <div class="gantry-width-spacer">
            <div class="rt-triangle-set">
                <div class="rt-triangle-1"></div>

                <div class="rt-triangle-2"></div>

                <div class="rt-triangle-3"></div>
            </div>
        </div>
    </div>
</div>
~~~

### Layout Options

![](assets/demo_1b.jpeg)

|         Option        |        Setting        |
| :-------------------- | :-------------------- |
| Display Limit         | `∞`                   |
| Theme                 | Showcase              |
| Article Titles        | Show                  |
| Article Text          | Show                  |
| Preview Length        | `∞`                   |
| Strip HTML Tags       | No                    |
| Arrow Navigation      | Show on Hover         |
| Pagination            | Show                  |
| Animation             | Bottom to Top         |
| Autoplay              | Disable               |
| Autoplay Delay        | `5`                   |
| Image Resize          | Disable               |
| Default Title         | Default Article Title |
| Default Article Text  | Default Article Text  |
| Default Article Image | Default Article Image |
| Default Link          | Default Article Link  |

### Advanced

![](assets/demo_1c.jpeg)

|        Option       |              Setting               |
| :------------------ | :--------------------------------- |
| Module Class Suffix | `fp-roksprocket-features-showcase` |
