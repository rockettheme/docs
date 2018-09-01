---
title: Anacron: Recreating the Demo - FP RokSprocket Showcase
description: Your Guide to Recreating Elements of the Anacron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Anacron:Anacron

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
Maximize Site Utility,<br />with the Dynamic Header
~~~

**Description**

~~~ .html
<span class="rt-button-group"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=107" class="readon">Read More</a><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=107" class="readon2">Download</a></span>
~~~

#### Simple Item 2

**Title**

~~~
Two Menu Options,<br />Dropdown &amp; SplitMenu
~~~

**Description**

~~~ .html
<span class="rt-button-group"><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=111" class="readon">Read More</a><a href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=111" class="readon2">Download</a></span>
~~~

#### Simple Item 3

**Title**

~~~ .html
Gantry Framework,<br />Powerful Features &amp; Extras
~~~

**Description**

~~~ .html
<span class="rt-button-group"><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=107" class="readon">Read More</a><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=107" class="readon2">Download</a></span>
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
| Pagination       | Show          |  
| Animation        | Bottom to Top |  
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
