---
title: Sirocco: Recreating the Demo - SideSlider
description: Your Guide to Recreating Elements of the Sirocco Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/sirocco:Sirocco

---

FP RokSprocket Features - SideSlider
-----

![](assets/sideslider.jpeg)

:   1. **SideSlider - Search** [5%, 21%, se]
    2. **SideSlider - Menu** [9%, 21%, se]
    3. **SideSlider - RokSprocket (Tabs)** [26%, 21%, se]
    4. **SideSlider -  Articles (Newsflash)** [51%, 21%, se]

The **SideSlider** module position enables you to add modules to the page that get out of the way of the content, but are available to visitors with a simple click. We used four modules in our demo, all of which are listed below along with their details.

1. [Search](demo_sideslider.md#search)
2. [Menu](demo_sideslider.md#menu)
3. [RokSprocket (Tabs)](demo_sideslider.md#roksprocket-(tabs))
4. [Articles - NewsFlash](demo_sideslider.md#articles---newsflash)

### Search

The first part of our SideSlider is a simple Joomla **Search** module. Here are the options used in our demo.

#### Module

|   Option   |       Setting       |
| :--------- | :------------------ |
| Title      | `SideSlider Search` |
| Show Title | Hide                |
| Position   | sideslider          |
| Status     | Published           |
| Access     | Public              |

#### Options

|          Option          | Setting |
| :----------------------- | :------ |
| Box Label                | Blank   |
| Box Width                | `20`    |
| Box Text                 | Blank   |
| Search Button            | No      |
| Button Position          | Right   |
| Search Button Image      | No      |
| Button Text              | Blank   |
| OpenSearch autodiscovery | Yes     |
| OpenSearch title         | Blank   |
| Set ItemID               | Search  |

#### Advanced

|        Option       |   Setting   |
| :------------------ | :---------- |
| Module Class Suffix | `fp-search` |

### Menu

This area of the demo is a **Menu** module. Here are the options used in our demo.

#### Module

|   Option   |      Setting      |
| :--------- | :---------------- |
| Title      | `SideSlider Menu` |
| Show Title | Hide              |
| Position   | sideslider        |
| Status     | Published         |
| Access     | Public            |

#### Options

|          Option          |     Setting     |
| :----------------------- | :-------------- |
| Select Menu              | SideSlider Menu |
| Base Item                | Current         |
| Start Level              | 1               |
| End Level                | All             |
| Show Sub-menu Items      | No              |

#### Advanced

|        Option       |  Setting  |
| :------------------ | :-------- |
| Module Class Suffix | `fp-menu` |

### RokSprocket (Tabs)

This area of the SideSlider is a **RokSprocket** module utilizing the **Simple** content provider and the **Tabs** layout.

The settings used in our demo are listed below.

#### Details

|      Option      |            Setting            |
| :--------------- | :---------------------------- |
| Title            | `SideSlider RokSprocket Tabs` |
| Show Title       | Hide                          |
| Access           | Public                        |
| Position         | sideslider                    |
| Status           | Published                     |
| Content Provider | Simple                        |

#### Simple Content Provider

The **Tab Label** and **Description** fields in each item have been altered. A few examples of these article changes can be found below.

##### Simple Item 1

**Tab Label**

~~~ .html
<span class="fa fa-file-text-o"></span>
~~~

**Description**

~~~ .html
<h2 class="title"><a href="#">-about</a></h2>

<h5>The SideSlider adds additional space for content outside of the main
template area.</h5>

<p><em>There are several options available for configuring the SideSlider
feature, such as the toggle or whether it is fixed or slides into
view.</em></p>

<p>The position is perfect for extra content or even full length
advertisements.</p>
~~~

##### Simple Item 2

**Tab Label**

~~~
<span class="fa fa-comments-o"></span>
~~~

**Description**

~~~ .html
<h2 class="title"><a href="#">-menus</a></h2>

<h5>Choose between two menu options: Dropdown Menu or Splitmenu; each with
mobile support.</h5>

<p><em>Dropdown Menu is a CSS based dropdown menu with advanced features such
as multiple columns and inline module positions.</em></p>

<p>Splitmenu is a static menu choice with parent items in the header and
children in the sidebar.</p>
~~~

##### Simple Item 3

The third item has a custom image in the **Image** field. This enables the grid item to show up as an image with the **Description** appearing as you move your mouse cursor over it.

**Tab Label**

~~~ .html
<span class="fa fa-picture-o"></span>
~~~

**Description**

~~~ .html
<h2 class="title"><a href="#">-gantry</a></h2>

<h5>A powerful, multi-platform, core template framework, which is free and
licensed under GPL.</h5>

<p><em>One of Gantry's most notable feature is its custom user interface which
provides an intuitive and user friendly configuration console.</em></p>

<p>A standardized set of features and capabilities are powered by Gantry.</p>
~~~

#### Layout Options

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

#### Advanced

|        Option       |             Setting              |
| :------------------ | :------------------------------- |
| Module Class Suffix | `fp-roksprocket-tabs-sideslider` |

### Articles - NewsFlash

This area of the demo is a **Articles - Newsflash** module. Here are the options used in our demo.

#### Module

|   Option   |  Setting   |
| :--------- | :--------- |
| Title      | `-popular` |
| Show Title | Show       |
| Position   | sideslider |
| Status     | Published  |
| Access     | Public     |

#### Options

|        Option       |       Setting        |
| :------------------ | :------------------- |
| Category            | Demo Popular Article |
| Show Images         | No                   |
| Show Article Title  | Yes                  |
| Linked Articles     | Yes                  |
| Header Level        | h3                   |
| Show Last Separator | Yes                  |
| Read More Link      | Hide                 |
| Number of Articles  | 3                    |
| Order Results       | Published Date       |
| Direction           | Descending           |

#### Advanced

|        Option       |    Setting     |
| :------------------ | :------------- |
| Module Class Suffix | `fp-newsflash` |
