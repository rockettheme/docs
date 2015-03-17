---
title: Sirocco: Recreating the Demo - Third Full Width
description: Your Guide to Recreating Elements of the Sirocco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/sirocco:Sirocco

---

Third Full Width Section
-----

![Third Full Width](assets/demo_9.jpeg)

Here is the widget breakdown for the Third Full Width section:

#### RokSprocket (Features)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Features** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option | Setting                                            |
| :----- | :-------------------------------------------       |
| Title  | `Build your website using our RocketLauncher demo` |
| Image  | Custom                                             |
| Link   | None                                               |

**Description**

~~~ .html
<span class="rt-sprocket-tag">maximum effectiveness</span><span>Start your new website using our Sirocco demo to customize and escalate development. RocketLauncher is available for all of our latest themes.</span>
~~~

Here is a look at the **Features Layout Options** for this widget.

| Option           | Setting        |
| :--------------- | :------------- |
| Display Limit    | ∞              |
| Theme            | Slideshow      |
| Article Titles   | Show           |
| Article Text     | Show           |
| Preview Length   | ∞              |
| Strip HTML Tags  | No             |
| Arrow Navigation | Show           |
| Pagination       | Show           |
| Animation        | Crossfade      |
| Autoplay         | Disable        |
| Autoplay Delay   | 5              |
| Image Resize     | Disable        |

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to return to the Widgets settings and fill them out as noted below:

| Option            | Setting                                          |
| :---------------- | :----------------------------------------------- |
| Choose Widget     | (Select the RokSprocket Widget You Just Created) |
| Custom Variations | `fp-roksprocket-fullwidth`                       |

Leaving everything else at its default setting, select **Save**.
