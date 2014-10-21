---
title: Reaction: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Reaction Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/reaction:Reaction

---

Sidebar Section
-----

![][demo]

:   1. **RokNewsPager** [5%, 20%, se]
    2. **Text** [25%, 20%, se]
    3. **Gantry Recent Comments** [33%, 20%, se]
    4. **Gantry Categories** [63%, 20%, se]
    5. **Tag Cloud** [76%, 20%, se]
    6. **Gantry Meta** [84%, 20%, se]

Here is the widget breakdown for the Sidebar section:

* RokNewsPager
* Text
* Gantry Recent Comments
* Gantry Categories
* Tag Cloud
* Gantry Meta

#### RokNewsPager

This area of the demo is a RokNewsPager widget. RokNewsPager is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="module-content">
    <div class="demo-rss-left">
        <img alt="RSS" class="demo-rss-img" src=
        "http://demo.rockettheme.com/live/wordpress/reaction/wp-content/rockettheme/rt_reaction_wp/frontpage/rss.png">
        <a href="#"><strong>Subscribe via RSS?</strong></a>
    </div>

    <div class="demo-rss-right">
        <img alt="Twitter" class="demo-rss-img" src=
        "http://demo.rockettheme.com/live/wordpress/reaction/wp-content/rockettheme/rt_reaction_wp/frontpage/twitter.png">
        <span><strong>Follow us on Twitter?</strong></span>
    </div>

    <div class="demo-divider"></div>

    <div class="demo-rss-left">
        <img alt="Email" class="demo-rss-email" src=
        "http://demo.rockettheme.com/live/wordpress/reaction/wp-content/rockettheme/rt_reaction_wp/frontpage/email.png">
        <span><strong>Subscribe via Email?</strong></span>
    </div>

    <div class="demo-rss-right">
        <img alt="Facebook" class="demo-rss-img" src=
        "http://demo.rockettheme.com/live/wordpress/reaction/wp-content/rockettheme/rt_reaction_wp/frontpage/facebook.png">
        <span><strong>Find us on Facebook?</strong></span>
    </div>

    <div class="clear"></div>
</div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Subscribe RSS`.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Recent Comments

The **Ganty Recent Comments** widget lists the latest comments in a clean, seamless way. Here are the settings we used with this widget.

| Option                     | Setting           |
| :----------                | :----------       |
| Title                      | `Latest Comments` |
| Number of Comments to Show | `8`               |
| Word Limit                 | `8`               |
| List Class                 | `jclist`          |
| Link Class                 | `jcl_comment`     |

#### Gantry Categories

The **Gantry Categories** widget gives visitors an easy way to navigate through categories of posts on your blog. Here are the options used in our demo.

| Option          | Setting       |
| :----------     | :----------   |
| Title           | `Categories`  |
| Display         | List          |
| Order By        | Category Name |
| List Class      | `menu`        |
| Show Post Count | No            |
| Show Hierarchy  | Yes           |
| Hide Empty      | Yes           |
| Exclude         | Blank         |
| Depth           | `0`           |

#### Tag Cloud

The **Tag Cloud** widget presents tags assigned to posts in a visually appealing way. This makes it easy for visitors to find posts on a topic that they are interested in, without the limitation of setting entire categories on the posts. Here are the settings used in our demo.

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `Tags`      |
| Taxonomy    | Tags        |

#### Gantry Meta

The **Gantry Meta** widget gives the visitor quick access to common tools such as the site admin and RSS feed. Here are the settings we used with this widget.

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `Meta`      |
| List Class  | `menu`      |

[roksprocket]: ../../plugins/roksprocket/
[demo]: assets/demo_4.jpeg
