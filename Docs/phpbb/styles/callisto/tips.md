---
title: Callisto: Tips and Tricks
description: Your Guide to Using the callisto Style for phpBB.
breadcrumb: /phpbb:phpBB/!styles:Styles/!callisto:Callisto/
tags: [Style, Template, Theme, Features, Description, Tutorials, rokBB 5]

---

## Introduction

The **Callisto** design for phpBB comes with several features that set it apart from other phpBB styles. We have outlined some tips and tricks to help you make the most of the style below.

## Modules

Our demo of **Callisto** features several modules which demonstrate what you can do with Callisto in phpBB 3.1. If you would like to replicate these modules, we recommend downloading the **RocketLauncher** and installing it on a local test server. There, you will have access to the source files and settings for these modules so you can easily replicate them. Alternatively, you can build your site based on the RocketLauncher and modify these modules to meet your individual needs.

You can find the Twig files used to create the modules in the `phpbb_root/styles/your_style/template/modules` directory. For a specific module, you will want to find the Twig file with the same name of the module you wish to replicate. For example, the module titled `Contact Us` is loaded from `phpbb_root/styles/your_style/template/modules/contact.html.twig`.

If you would like more information on how these modules are assembled and installed in phpBB 3.1, check out our [RokBB user guide](../../start/user_guide.md).

## Colors for Rounded Avatar Containers

Callisto contains improved main forum layout. Layout is based on user avatars and customizable containers. It shows last user avatar image instead forum icon or first topic/forum letter. It also adds a status indicator which notifies users about new topics or special actions.

![Styles](styles_1.png)

You can edit the color settings for both the avatar's background and the letter overlay by navigating to **Customise** in the admin, selecting **Style Settings** under the **RocketTheme Styles** section of the sidebar, and opening the **Style** tab. The options are listed as **Forumicon Background Color** and **Forumicon Letter Color**. 

## SCSS Compiler

To start using the SCSS compiler right away, you can do so using a `_custom.scss` file. This file is located inside style directory: `~/styles/callisto/theme/scss/phpbb/_custom.scss`. Changes you make here will be saved and automatically recompiled during your next forum visit. If you're not familiar with SCSS, you can find more information about this compiler be visiting its [official documentation](http://leafo.net/scssphp/docs/).

If you want to add your own SCSS file for compilation, open `template/modules/styledeclaration.html.twig`, find the core section:

~~~ .twig
{# Core Theme #}
~~~

and add something like that

~~~ .twig
{% INCLUDECSS scss_compiler ~ 'scss/your_file_name.scss' %}
~~~

This will load your custom SCSS file, but your custom SCSS file has to be uploaded into the `~/styles/callisto/theme/scss/` directory.

## Animation

![Animation](animation_1.png)

The animated elements that trigger as you scroll down the page are handled via classes applied to HTML elements, icons etc. You can access **Callisto's** main settings area by navigating to **Admin > Styles > Callisto**. From here, you will want to select the **Imageset Editor** tab where you can find the **Forum Icons** settings. In these fields, you can enter the tag of the animation(s) you wish to use. You can find a list (as well as visual examples) of these [animation classes here](http://daneden.github.io/animate.css/).

In our demo, we used the following in the three **Forum Icons** field.

| Option       | Setting                          |
| :----------  | :----------                      |
| Forum        | `fa fa-folder-open-o wow zoomIn` |
| Forum Linked | `fa fa-unlink wow zoomIn`        |
| Forum Locked | `fa fa-folder-o wow zoomIn`      |

The class name `wow zoomIn` sets the animation of each component to zoom in. The `wow` portion is the prefix, and `zoomIn` is the name of the animation. The `fa fa-(name)` classes set the **Font Awesome** icon used for each component.
