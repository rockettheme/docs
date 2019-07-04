---
title: Cygnet: Recreating the Demo - Footer
description: Your Guide to Recreating Elements of the Cygnet Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cygnet:Cygnet

---

Footer Section
-----

![Footer](assets/demo_13.jpeg)

Here is the widget breakdown for the Footer section:

#### RokSprocket (Quotes)

This area of the demo is a RokSprocket widget. You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Quotes** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom headline text without having to create separate posts or pages to do so. Here are the details of one of the items in the **Featured Article List**.

| Option     | Setting                                                                                                  |
| :-----     | :-----                                                                                                   |
| Quote Text | `Cygnet is both attractive and highly adaptable. Cygnet is the real deal! I will refer everyone I know.` |
| Image      | Custom                                                                                                   |
| Author     | `Reina Kyle`                                                                                             |
| Subtext    | `Developer at Jasmine Inc.`                                                                              |
| Link       | None                                                                                                     |
| Direction  | Bottom Left                                                                                              |

Here is a look at the **Quotes Layout Options** for this widget.

| Option            | Setting      |
| :-----            | :-----       |
| Theme             | Default      |
| Display Limit     | ∞            |
| Preview Length    | ∞            |
| Strip HTML Tags   | No           |
| Previews Per Page | `3`          |
| Items Per Row     | 3            |
| Arrow Navigation  | Hide         |
| Pagination        | Show         |
| Animation         | Fade Delayed |
| Autoplay          | Disable      |
| Autoplay Delay    | 5            |
| Image Resize      | Disable      |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to return to the Widgets settings and fill them out as noted below:

| Option            | Setting                                          |
| :-----            | :-----                                           |
| Choose Widget     | (Select the RokSprocket Widget You Just Created) |
| Custom Variations | `fp-roksprocket-quotes wow flipInX`              |

Leaving everything else at its default setting, select **Save**.