---
title: Omnicron: Recreating the Demo - FeatureTable
description: Your Guide to Recreating Elements of the Omnicron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/omnicron:Omnicron

---

FeatureTable
-----

![][demo]

This area of the front page is a standard **RokFeatureTable** module.

The demo utilized RokTabs, an extension which has since been replaced by RokSprocket, to present the table in a slideshow alongside other articles. The RokFeatureTable module was embedded in an article as its content body.

For the purposes of simplicity, we have detailed the settings we used for the RokFeatureTable module, specifically.

### Details

![][demo2]

| Option     | Setting              |
| :--------- | :---------------     |
| Title      | `FeatureTable`       |
| Show Title | Hide                 |
| Position   | special-featuretable |
| Status     | Published            |
| Access     | Public               |

### Basic

![][demo3]

| Option              | Setting       |
| :------------------ | :------------ |
| Built-in CSS        | Yes           |
| Highlight Column    | Column 3      |
| Preset Templates    | None Selected |
| Layout Setup        | 7 x 4         |

### Layout Setup

![][demo5]

You can reach this menu, which allows you to customize content within the table, by clicking on the sprocket icon in the **Layout Setup** area of **Basic Options**.

The following text is placed in the row fields for **COL 1** (other columns have similar data). 

| Row   | Main Field              | Class               | Subline                    | Link      | Style        |
| :---- | :----                   | :----               | :----                      | :----     | :----        |
| ROW 1 | Free                    | name                | row-1                      | row-1     | row-1        |
| ROW 2 | $0                      | price               | per month                  | cell link |              |
| ROW 3 | <b>2</b> Users          | row-3               | subline text               | cell link |              |
| ROW 4 | <b>1 GB</b> Storage     | row-4               | subline text               | cell link |              |
| ROW 5 | <b>No</b> Customization | row-5               | subline text               | cell link |              |
| ROW 6 | ⊕ iPhone App<br />      | row-6               | subline text               | cell link | height:89px; |
| ROW 7 | Sign Up Now             | button-text button4 | Sign Up to get access now! | cell link |              |

### Advanced
![][demo4]

| Option              | Setting        |
| :------------------ | :------------  |
| Module Class Suffix | `featuretable` |

[demo]: assets/demo_7.jpg
[demo2]: assets/demo_7a.jpeg
[demo3]: assets/demo_7b.jpeg
[demo4]: assets/demo_7c.jpeg
[demo5]: assets/demo_7d.jpeg
