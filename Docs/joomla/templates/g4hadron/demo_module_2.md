---
title: Hadron: Recreating the Demo - FP RokSprocket Showcase
description: Your Guide to Recreating Elements of the Hadron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hadron:Hadron

---

FP RokSprocket Showcase
-----

![][demo]

The **RokSprocket Showcase** module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest.

We utilized the **Simple** Content Provider type in order to create custom articles for the front page. Most of the magic involving the look and feel of these items happen in the **Title** and **Description** fields for the individual line items. Custom images are also used to add visual flair to each item in the showcase.

### Details

![][demo2]

| Option           | Setting                   |  
| :--------------- | :------------------------ |  
| Title            | `FP RokSprocket Showcase` |  
| Show Title       | Hide                      |  
| Access           | Public                    |  
| Position         | showcase-a                |  
| Status           | Published                 |  
| Content Provider | Simple                    |  
| Type             | Features                  |  

### Filtered Article List

#### Simple Item 1

**Title**

~~~ .html
<span class="rt-bold hidden-tablet">Flexible Layouts</span> Gantry 4
~~~

**Description**

~~~ .html
Gantry provides up to 6 positions per row, each with configurable widths.<span class="hidden-tablet"> There are over 80 positions available, each collapsible to provide ultimate flexibility.</span><br />
~~~

#### Simple Item 2

**Title**

~~~
<span class="rt-bold hidden-tablet">Versatile</span> RokSprocket
~~~

**Description**

~~~ .html
<span class="hidden-tablet">RokSprocket is a powerful content display extension with an advanced administrative interface, and numerous layout modes, such as Strips and Tabs.</span><span class="visible-tablet">RokSprocket is a content display extension with numerous layouts.</span><br />
~~~

#### Simple Item 3

**Title**

~~~ .html
<span class="rt-bold hidden-tablet">Dropdown</span> Menu
~~~

**Description**

~~~ .html
Dropdown is a CSS based menu system with advanced features<span class="hidden-tablet"> such as multiple columns, inline icons, inline modules and positions, on a per menu item basis</span>.<br />
~~~

### Layout Options

![][demo3]

| Option           | Setting       |  
| :--------------- | :------------ |  
| Display Limit    | ∞             |  
| Theme            | Showcase      |  
| Article Titles   | Show          |  
| Article Text     | Show          |  
| Preview Length   | ∞             |  
| Strip HTML Tags  | No            |  
| Arrow Navigation | Show          |  
| Pagination       | Hide          |  
| Animation        | Crossfade     |  
| Autoplay         | Disable       |  
| Autoplay Delay   | 5             |  
| Image Resize     | Disable       |  

### Advanced

![][demo4]

| Option              | Setting                   |  
| :------------------ | :------------------------ |  
| Module Class Suffix | `fp-roksprocket-showcase` |  

[demo]: assets/demo_1.jpeg
[demo2]: assets/showcase_1.jpeg
[demo3]: assets/showcase_2.jpeg
[demo4]: assets/showcase_3.jpeg