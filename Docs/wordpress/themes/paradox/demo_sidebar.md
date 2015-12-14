---
title: Paradox: Recreating the Demo - Sidebar
description: Your Guide to Recreating Elements of the Paradox Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/paradox:Paradox

---

Sidebar Section
-----

![](demo_8.png)

:   1. **Gantry Login Form** [9%, 5%, se]
    2. **Gantry Categories** [60%, 5%, se]
    3. **Gantry Links** [9%, 53%, se]

Here is the widget breakdown for the Sidebar section:

* Gantry Login Form
* Gantry Categories
* Gantry Divider
* Gantry Links

### Gantry Login Form

The login form located on the front page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option            | Setting     |
| :----------       | :---------- |
| Title             | `Login`     |
| User Greeting     | `Hi,`       |
| Pre-text          | Blank       |
| Post-text         | Blank       |

### Gantry Categories

The **Gantry Categories** widget displays post categories in an easy-to-use list for visitors. The settings used in the demo are listed below.

| Option            | Setting       |
| :----------       | :----------   |
| Title             | `Categories`  |
| Display           | List          |
| Order By          | Category Name |
| List Class        | `menu`        |
| Show Post Count   | No            |
| Show Hierarchy    | Yes           |
| Hide Empty        | Yes           |
| Exclude           | Blank         |
| Depth             | `0`           |

### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

### Gantry Links

| Option                | Setting         |
| :----------           | :----------     |
| Title                 | `Blogroll`      |
| Links Category        | All Links       |
| Show Link Image       | Checked         |
| Show Link Name        | Checked         |
| Show Link Description | Unchecked       |
| Show Link Rating      | Unchecked       |
| Categorize            | Unchecked       |
| Categories Order By   | Name            |
| Links Order by        | Name            |
| Limit Links           | `-1`            |
| List Class            | `menu`          |
| Category Class        | `link_category` |
