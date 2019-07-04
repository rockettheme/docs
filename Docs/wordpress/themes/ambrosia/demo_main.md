---
title: Ambrosia: Recreating the Demo - Mainbar Section
description: Your Guide to Recreating Elements of the Ambrosia Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/ambrosia:Ambrosia

---

## Introduction

![](assets/demo_main.jpeg)

:   1. **RokSprocket (Tabs) 1 / Info List (Particle)** [7%, 7%, se]
    2. **RokSprocket (Headlines) / Info List (Particle)** [50%, 7%, se]
    3. **RokSprocket (Tabs) 1 / Info List (Particle)** [50%, 42%, se]

The **Mainbar** section contains three **Widget Position** particles, each containing a RokSprocket widget. Some of the RokSprocket widgets load **Gantry 5 Particle** widgets which enable you to embed particles within RokSprocket items.

Here is a breakdown of the particles that appear in this section:

* [Widget Position (mainbar)](#widget-position-(mainbar))
    * [RokSprocket (Tabs)](#assigned-widget(s)---roksprocket-(tabs))
        * [Gantry 5 Particle (Widget)](#gantry-5-particle-(widget))
            * [Info List (Particle)](#info-list-(particle))
* [Widget Position (mainleft)](#widget-position-(mainleft))
    * [RokSprocket (Headlines)](#assigned-widget(s)---roksprocket-(headlines))
        * [Gantry 5 Particle (Widget)](#gantry-5-particle-(widget)-2)
            * [Info List (Particle)](#inf-list-(particle)-2)
* [Widget Position (mainright)](#widget-position-(mainright))
    * [RokSprocket (Tabs)](#assigned-widget(s)---roksprocket-(tabs)-2)
        * [Gantry 5 Particle (Widget)](#gantry-5-particle-(widget)-3)
            * [Info List (Particle)](#info-list-(particle)-3)

![](assets/home_main.jpeg)

Settings used in this section can be found below.

## Section Settings

![](assets/demo_main_1.jpeg)

| Field          | Setting   |
| :-----         | :-----    |
| CSS Classes    | Blank     |
| Tag Attributes | Blank     |
| Width          | `67%`     |

## Widget Position (mainbar)

There is an important aspect of this widget position used in our demo you should be aware of. First, the `mainbar` widget position contains a RokSprocket (Tabs) widget. This widget loads multiple widget positions through its simple items' descriptions. These widget positions are then used to assign **Gantry 5 Particle** widgets which enable you to embed Gantry 5 particles within RokSprocket.

### Particle Settings

![](assets/demo_main_2.png)

| Field         | Setting              |
| :-----        | :-----               |
| Particle Name | `Position - Mainbar` |
| Key           | `mainbar`            |
| Chrome        | `gantry`             |

### Block Settings

![](assets/demo_main_3.jpeg)

| Field          | Setting                                       |
| :-----         | :-----                                        |
| CSS ID         | Blank                                         |
| CSS Classes    | `fp-mainbar-tab` `g-roksprocket-tabs-style-2` |
| Variations     | No Padding                                    |
| Tag Attributes | Blank                                         |
| Block Size     | `100%`                                        |

### Assigned Widget(s) - RokSprocket (Tabs)

The `mainbar` widget position is host to a single **RokSprocket** widget.

We utilized the **Simple** Content Provider, linking each item in the RokSprocket widget to an post. You can find examples of the **Simple** items used in this widget in the **Filtered Article List** section below.

#### Details

![](assets/demo_main_4.png)

| Option                | Setting               |
| :-----                | :-----                |
| Title                 | `Todays Highlights`   |
| Content Provider      | Simple                |
| Type                  | Tabs                  |
| Theme                 | Default               |
| Display Limit         | `∞`                   |
| Tabs Position         | Top                   |
| Animation             | Slide and Fade        |
| Autoplay              | Disable               |
| Autoplay Delay        | `5`                   |
| Image Resize          | Disable               |
| Default Title         | Default Article Title |
| Default Article Text  | Default Article Text  |
| Default Article Image | Default Article Image |
| Default Link          | Default Article Link  |

#### Filtered Article List

##### Item 1

| Option      | Setting                                             |
| :-----      | :-----                                              |
| Tab Label   | `News`                                              |
| Icon        | None                                                |
| Link        | None                                                |
| Description | `[loadposition id="mainbar-tabs-1"][/loadposition]` |

##### Item 2

| Option      | Setting                                             |
| :-----      | :-----                                              |
| Tab Label   | `Games`                                             |
| Icon        | None                                                |
| Link        | None                                                |
| Description | `[loadposition id="mainbar-tabs-2"][/loadposition]` |

##### Item 3

| Option      | Setting                                             |
| :-----      | :-----                                              |
| Tab Label   | `Articles`                                          |
| Icon        | None                                                |
| Link        | None                                                |
| Description | `[loadposition id="mainbar-tabs-3"][/loadposition]` |

>> NOTE: The description fields for these items load widget positions (for example: `mainbar-tabs-1`), which have been assigned **Gantry 5 Particle** widgets, each of which contain a single **Tab Image** particle. You will find the details for the **Tab Image** particle assigned to the **Gantry 5 Particle** widget, and assigned to the `mainbar-tabs-1` position loaded in the `News` tab in the [Info List (Particle)](#info-list-(particle)) section below.

### Gantry 5 Particle (Widget)

In this section, we will cover one of the embedded particles that appear in the **RokSprocket** widget assigned to the `mainbar` position. This **Gantry 5 Particle** widget loads a single **Tab Image** particle.

#### Details

![](assets/demo_main_8.jpeg)

| Option     | Setting                      |
| :-----     | :-----                       |
| Title      | `FP Today's Highlight Tab 1` |
| Show Title | Hide                         |
| Position   | `mainbar-tabs-1`             |
| Particle   | Info List                    |

### Info List (Particle)

#### Particle Settings

![](assets/demo_main_9.jpeg)

| Field         | Setting     |
| :-----        | :-----      |
| Particle Name | `Info List` |
| CSS Classes   | Blank       |
| Title         | None        |
| Intro         | None        |
| Grid Column   | 2 Columns   |

#### Tab Image Example

![](assets/demo_main_10.jpeg)

| Field                           | Setting                                |
| :-----                          | :-----                                 |
| Info List Item 1 Name           | `Six presets with individual settings` |
| Info List Item 1 Image Location | Left                                   |
| Info List Item 1 Text Style     | Bold                                   |
| Info List Item 1 Image Style    | Large                                  |
| Info List Item 1 Description    | `Pre-built styling easily configured`  |
| Info List Item 1 Tag            | `Style`                                |
| Info List Item 1 Sub Tag        | `Presets`                              |
| Info List Item 1 Label          | Blank                                  |
| Info List Item 1 Link           | `#`                                    |
| Info List Item 1 Icon           | Blank                                  |
| Info List Item 1 CSS Classes    | Blank                                  |

## Widget Position (mainleft)

There is an important aspect of this widget position used in our demo you should be aware of. First, the `mainleft` widget position contains a RokSprocket (Tabs) widget. This widget loads multiple widget positions through its simple items' descriptions. These widget positions are then used to assign **Gantry 5 Particle** widgets which enable you to embed Gantry 5 particles within RokSprocket.

### Particle Settings

![](assets/demo_main_12.jpeg)

| Field         | Setting               |
| :-----        | :-----                |
| Particle Name | `Position - Mainleft` |
| Key           | `mainleft`            |
| Chrome        | `gantry`              |

### Block Settings

![](assets/demo_main_13.png)

| Field          | Setting                           |
| :-----         | :-----                            |
| CSS ID         | Blank                             |
| CSS Classes    | `g-roksprocket-headlines-style-2` |
| Variations     | No Padding, Box 3                 |
| Tag Attributes | Blank                             |
| Block Size     | `40%`                             |

### Assigned Widget(s) - RokSprocket (Headlines)

The `mainleft` widget position is host to a single **RokSprocket** widget.

We utilized the **Simple** Content Provider, linking each item in the RokSprocket widget to an post. You can find examples of the **Simple** items used in this widget in the **Filtered Article List** section below.

#### Details

![](assets/demo_main_14.png)

| Option                | Setting                             |
| :-----                | :-----                              |
| Title                 | `FP RokSprocket Headlines Mainleft` |
| Content Provider      | Simple                              |
| Type                  | Headlines                           |
| Theme                 | Default                             |
| Display Limit         | `2`                                 |
| Label Text            | `Side Notes`                        |
| Preview Length        | `∞`                                 |
| Strip HTML Tags       | No                                  |
| Arrow Navigation      | Show                                |
| Animation             | Fade                                |
| Autoplay              | Disable                             |
| Autoplay Delay        | `5`                                 |
| Image Resize          | Disable                             |
| Default Title         | Default Article Title               |
| Default Article Text  | Default Article Text                |
| Default Article Image | Default Article Image               |
| Default Link          | Default Article Link                |

#### Filtered Article List

##### Item 1

| Option      | Setting                                                   |
| :-----      | :-----                                                    |
| Image       | None                                                      |
| Link        | None                                                      |
| Description | `[loadposition id="mainleft-headlines-1"][/loadposition]` |

##### Item 2

| Option      | Setting                                                   |
| :-----      | :-----                                                    |
| Image       | None                                                      |
| Link        | None                                                      |
| Description | `[loadposition id="mainleft-headlines-2"][/loadposition]` |

>> NOTE: The description fields for these items load widget positions (for example: `mainleft-headlines-1`), which have been assigned **Gantry 5 Particle** widgets, each of which contain a single **Tab Image** particle. You will find the details for the **Tab Image** particle assigned to the **Gantry 5 Particle** widget, and assigned to the `mainleft-headlines-1` position loaded in the `News` tab in the [Info List (Particle)](#info-list-(particle)-2) section below.

### Gantry 5 Particle (Widget) 2

In this section, we will cover one of the embedded particles that appear in the **RokSprocket** widget assigned to the `mainleft` position. This **Gantry 5 Particle** widget loads a single **Tab Image** particle.

#### Details

![](assets/demo_main_17.jpeg)

| Option     | Setting                   |
| :-----     | :-----                    |
| Title      | `FP Mainleft Headlines 1` |
| Show Title | Hide                      |
| Position   | `mainleft-headlines-1`    |
| Particle   | Info List                 |

### Info List (Particle) 2

#### Particle Settings

![](assets/demo_main_19.png)

| Field         | Setting     |
| :-----        | :-----      |
| Particle Name | `Info List` |
| CSS Classes   | Blank       |
| Title         | None        |
| Grid Column   | 1 Column    |

**Intro**
~~~ .html
<span>Gantry benefits from an extensive, and ever expanding, catalog of online and free documentation<span class="hidden-tablet"> covering basic to more advanced topics</span>.</span>
~~~

#### Tab Image Example

![](assets/demo_main_18.jpeg)

| Field                           | Setting                                    |
| :-----                          | :-----                                     |
| Info List Item 1 Name           | `Gantry 5 is packed full of rich features` |
| Info List Item 1 Image Location | Left                                       |
| Info List Item 1 Text Style     | Compact                                    |
| Info List Item 1 Image Style    | Compact                                    |
| Info List Item 1 Description    | Blank                                      |
| Info List Item 1 Tag            | Blank                                      |
| Info List Item 1 Sub Tag        | Blank                                      |
| Info List Item 1 Label          | Blank                                      |
| Info List Item 1 Link           | `#`                                        |
| Info List Item 1 Icon           | Blank                                      |
| Info List Item 1 CSS Classes    | Blank                                      |

## Widget Position (mainright)

There is an important aspect of this widget position used in our demo you should be aware of. First, the `mainright` widget position contains a RokSprocket (Tabs) widget. This widget loads multiple widget positions through its simple items' descriptions. These widget positions are then used to assign **Gantry 5 Particle** widgets which enable you to embed Gantry 5 particles within RokSprocket.

### Particle Settings

![](assets/demo_main_20.jpeg)

| Field         | Setting              |
| :-----        | :-----               |
| Particle Name | `Position - Mainbar` |
| Key           | `mainright`          |
| Chrome        | `gantry`             |

### Block Settings

![](assets/demo_main_21.jpeg)

| Field          | Setting                                         |
| :-----         | :-----                                          |
| CSS ID         | Blank                                           |
| CSS Classes    | `fp-mainright-tab` `g-roksprocket-tabs-style-3` |
| Variations     | No Padding                                      |
| Tag Attributes | Blank                                           |
| Block Size     | `60%`                                           |

### Assigned Widget(s) - RokSprocket (Tabs) 2

The `mainright` widget position is host to a single **RokSprocket** widget.

We utilized the **Simple** Content Provider, linking each item in the RokSprocket widget to an post. You can find examples of the **Simple** items used in this widget in the **Filtered Article List** section below.

#### Details

![](assets/demo_main_22.jpeg)

| Option                | Setting                         |
| :-----                | :-----                          |
| Title                 | `FP RokSprocket Tabs Mainright` |
| Content Provider      | Simple                          |
| Type                  | Tabs                            |
| Theme                 | Default                         |
| Display Limit         | `∞`                             |
| Tabs Position         | Top                             |
| Animation             | Fade                            |
| Autoplay              | Disable                         |
| Autoplay Delay        | `5`                             |
| Image Resize          | Disable                         |
| Default Title         | Default Article Title           |
| Default Article Text  | Default Article Text            |
| Default Article Image | Default Article Image           |
| Default Link          | Default Article Link            |

#### Filtered Article List

##### Item 1

| Option      | Setting                                               |
| :-----      | :-----                                                |
| Tab Label   | `Promoted News`                                       |
| Icon        | None                                                  |
| Link        | None                                                  |
| Description | `[loadposition id="mainright-tabs-1"][/loadposition]` |

##### Item 2

| Option      | Setting                                               |
| :-----      | :-----                                                |
| Tab Label   | `Other News`                                          |
| Icon        | None                                                  |
| Link        | None                                                  |
| Description | `[loadposition id="mainright-tabs-2"][/loadposition]` |

##### Item 3

| Option      | Setting                                               |
| :-----      | :-----                                                |
| Tab Label   | `Rumors`                                              |
| Icon        | None                                                  |
| Link        | None                                                  |
| Description | `[loadposition id="mainright-tabs-3"][/loadposition]` |

>> NOTE: The description fields for these items load widget positions (for example: `mainright-tabs-1`), which have been assigned **Gantry 5 Particle** widgets, each of which contain a single **Tab Image** particle. You will find the details for the **Tab Image** particle assigned to the **Gantry 5 Particle** widget, and assigned to the `mainright-tabs-1` position loaded in the `News` tab in the [Info List (Particle)](#info-list-(particle)-3) section below.

### Gantry 5 Particle (Widget) 3

In this section, we will cover one of the embedded particles that appear in the **RokSprocket** widget assigned to the `mainright` position. This **Gantry 5 Particle** widget loads a single **Tab Image** particle.

#### Details

![](assets/demo_main_25.jpeg)

| Option     | Setting               |
| :-----     | :-----                |
| Title      | `FP Mainright Tabs 1` |
| Show Title | Hide                  |
| Position   | `mainright-tabs-1`    |
| Particle   | Info List             |

### Info List (Particle) 3

#### Particle Settings

![](assets/demo_main_26.jpeg)

| Field         | Setting     |
| :-----        | :-----      |
| Particle Name | `Info List` |
| CSS Classes   | Blank       |
| Title         | None        |
| Intro         | None        |
| Grid Column   | 1 Column    |

#### Tab Image Example

![](assets/demo_main_27.jpeg)

| Field                           | Setting                                                                                                            |
| :-----                          | :-----                                                                                                             |
| Info List Item 1 Name           | `The new and powerful Gantry 5 Framework`                                                                          |
| Info List Item 1 Image          | Blank                                                                                                              |
| Info List Item 1 Image Location | Left                                                                                                               |
| Info List Item 1 Text Style     | Large                                                                                                              |
| Info List Item 1 Image Style    | Compact                                                                                                            |
| Info List Item 1 Description    | `Gantry 5 is an advanced, versatile and multi-platform theme framework, perfectly designed for the modern web.` |
| Info List Item 1 Tag            | Blank                                                                                                              |
| Info List Item 1 Sub Tag        | `Drag and Drop Functionality`                                                                                      |
| Info List Item 1 Label          | Blank                                                                                                              |
| Info List Item 1 Link           | `#`                                                                                                                |
| Info List Item 1 Icon           | Blank                                                                                                              |
| Info List Item 1 CSS Classes    | Blank                                                                                                              |
