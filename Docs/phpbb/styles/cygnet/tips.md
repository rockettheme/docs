---
title: Cygnet: Tips and Tricks
description: Your Guide to Using the cygnet Style for phpBB.
breadcrumb: /phpbb:phpBB/!styles:Styles/!cygnet:Cygnet/
tags: [Style, Template, Theme, Features, Description, Tutorials, rokBB 5]

---

Introduction
-----

The **Cygnet** design for phpBB comes with several features that set it apart from other phpBB styles. We have outlined some tips and tricks to help you make the most of the style below.

Modules
-----

Our demo of **Cygnet** features several modules which demonstrate what you can do with Cygnet in phpBB 3.1. If you would like to replicate these modules, we recommend downloading the **RocketLauncher** and installing it on a local test server. There, you will have access to the source files and settings for these modules so you can easily replicate them. Alternatively, you can build your site based on the RocketLauncher and modify these modules to meet your individual needs.

You can find the Twig files used to create the modules in the `phpbb_root/styles/your_style/template/modules` directory. For a specific module, you will want to find the Twig file with the same name of the module you wish to replicate. For example, the module titled `Contact Us` is loaded from `phpbb_root/styles/your_style/template/modules/contact.html.twig`.

If you would like more information on how these modules are assembled and installed in phpBB 3.1, check out our [RokBB user guide](../../start/user_guide.md).

Animated Header
-----

The animated header featured in the Cygnet style is controlled form two places in the administrator. First, you will need to navigate to **Admin > Customise** then select **Style Settings** from the **RocketTheme Styles** section of the sidebar.

![Style](header_1.png)

:   1. **Slideshow Type** [73%, 8%, se]

From here, you can control the animation from the **Style** tab at the line titled **Slideshow Type**. This line gives you the ability to switch between the following options:

| Option              | Description                                                                                                                         |
| :-----              | :-----                                                                                                                              |
| None                | Displays no background image or animation. It only displays the **Slideshow Textcolor** and **Slideshow Background** color options. |
| Particles Animation | Displays the Cygnet particles animation along with the background and text.                                                         |
| Particles Static    | Displays a static (still) version of the particles animation.                                                                       |
| Custom              | This option is used when you want to replace the particles animation with your own background image (set in the **Template** tab).  |

![Template](header_2.png)

:   1. **Slideshow Background Image** [50%, 8%, se]
    2. **Slideshow Height** [55%, 8%, se]

If you want to set your own background image, you can do so via the **Template** tab at the line titled **Slideshow Background Image**. You can also set the **Slideshow Height** from this tab, which enables you to fine-tune the look of your site.

Animation
-----

![Animation](animation_1.png)

The animated elements that trigger as you scroll down the page are handled via classes applied to HTML elements, icons etc. You can access **Cygnet's** main settings area by navigating to **Admin > Styles > Cygnet**. From here, you will want to select the **Imageset Editor** tab where you can find the **Forum Icons** settings. In these fields, you can enter the tag of the animation(s) you wish to use. You can find a list (as well as visual examples) of these [animation classes here](http://daneden.github.io/animate.css/).

In our demo, we used the following in the three **Forum Icons** field.

| Option       | Setting                          |
| :----------  | :----------                      |
| Forum        | `fa fa-folder-open-o wow zoomIn` |
| Forum Linked | `fa fa-unlink wow zoomIn`        |
| Forum Locked | `fa fa-folder-o wow zoomIn`      |

The class name `wow zoomIn` sets the animation of each component to zoom in. The `wow` portion is the prefix, and `zoomIn` is the name of the animation. The `fa fa-(name)` classes set the **Font Awesome** icon used for each component.
