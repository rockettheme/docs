---
title: Paradigm: Recreating the Demo - FP RokSprocket Showcase
description: Your Guide to Recreating Elements of the Paradigm Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradigm:Paradigm

---

FP RokSprocket Showcase
-----

![][demo]

The **RokSprocket Showcase** module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest.

We utilized the **Simple Content** Content Provider type in order to create custom articles for the front page. Most of the magic involving the look and feel of these items happen in the **Title** and **Description** fields for the individual line items. Custom images are also used to add visual flare to each item in the showcase.

### Details

![][demo2]

| Option           | Setting                 |  
| :--------------- | :---------------------- |  
| Title            | FP RokSprocket Showcase |  
| Show Title       | Hide                    |  
| Access           | Public                  |  
| Position         | showcase-a              |  
| Status           | Published               |  
| Content Provider | Simple                  |  
| Type             | Features                |  

### Filtered Article List

![][demo5]

#### Simple Item 1

**Title**

~~~ .html
Build Something Beautiful.
~~~

**Description**

~~~ .html
<span class="rt-showcase-description">Paradigm provides the tools you need to setup your website with ease and provide a great experience to your viewers.</span><a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=22&amp;Itemid=121">Purchase</a><a class="readon2" href="index.php?option=com_content&amp;view=article&amp;id=22&amp;Itemid=121">Learn More</a>
~~~

#### Simple Item 2

**Title**

~~~
Discover The Essentials.
~~~

**Description**

~~~ .html
<span class="rt-showcase-description">Use the powerful Dropdown Menu system, with its multiple levels and columns, to navigate through the varying site pages.</span><a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=111">Purchase</a><a class="readon2" href="index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=111">Learn More</a>
~~~

#### Simple Item 3

**Title**

~~~ .html
Control Your Content.
~~~

**Description**

~~~ .html
<span class="rt-showcase-description">RokSprocket is a powerful content extensive with numerous layout modes and an advanced administrative interface.</span><a class="readon" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=107">Purchase</a><a class="readon2" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=107">Learn More</a>
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
[demo5]: assets/showcase_4.jpeg