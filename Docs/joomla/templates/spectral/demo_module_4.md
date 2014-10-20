---
title: Spectral: Recreating the Demo - Popular Features
description: Your Guide to Recreating Elements of the Spectral Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/spectral:Spectral

---

Popular Features
-----

![][demo]

We used a **RokSprocket** module with the **Tabs** layout to make up this area of the front page. You will find the settings used in our demo below.

### Details

![][demo2]

| Option           | Setting                                                            |  
| :--------------- | :----------------------------------------------------------------- |  
| Title            | `Popular Features[span class="rt-title-tag"]By RokSprocket[/span]` |  
| Show Title       | Show                                                               |  
| Access           | Public                                                             |  
| Position         | feature-a                                                          |  
| Status           | Published                                                          |  
| Content Provider | Simple                                                             |  
| Type             | Tabs                                                               |  

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

### Filtered Article List

#### Item 1

| Option | Setting                                     |  
| :----- | :------------------------------------------ |  
| Label  | `<span class="icon-cloud-download"></span>` |  
| Icon   | None                                        |  

**Description**

~~~ .html
<p>RokSprocket is a powerful, versatile and flexible content presentation
extension. It is prebuilt with many layout options, such as Tabs and Lists, to
cover most desired configurations, and is easily expandable.</p>

<p class="hidden-tablet"><span>It also benefits from an advanced <span class=
"visible-large">but user friendly</span> administrator <span class=
"visible-large">for quick and easy setup</span>.</span>
~~~

### Layout Options

![][demo3]

| Option          | Setting        |  
| :-------------- | :------------- |  
| Theme           | Default        |  
| Tabs Position   | Top            |  
| Display Limit   | ∞              |  
| Animation       | Slide and Fade |  
| Autoplay        | Disable        |  
| Autoplay Delay  | 5              |  
| Preview Length  | 0              |  
| Image Resize    | Disable        |  
| Strip HTML Tabs | No             |

### Advanced

![][demo4]

| Option              | Setting               |  
| :------------------ | :-------------------- |  
| Module Class Suffix | `fp-roksprocket-tabs` |  

[demo]: assets/demo_11.jpeg
[demo2]: assets/tabs_1.jpeg
[demo3]: assets/tabs_2.jpeg
[demo4]: assets/tabs_3.jpeg