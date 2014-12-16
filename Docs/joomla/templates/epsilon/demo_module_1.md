---
title: Epsilon: Recreating the Demo - FP RokSprocket Animation P1
description: Your Guide to Recreating Elements of the Epsilon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/epsilon:Epsilon

---

FP RokSprocket Animation P1
-----

![][demo]

The **RokSprocket Features** module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest.

>> NOTE: In the demo, we used a separate RokSprocket module for each preset. This was done in order to demonstrate the versatility of RokSprocket.

We utilized the **Simple** Content Provider type in order to create custom articles for the front page. Most of the magic involving the look and feel of these items happen in the **Title** and **Description** fields for the individual line items. Custom images are also used to add visual flair to each item in the showcase.

With Epsilon specifically, you can define a **background** and primary image. This makes it easier to utilize primary images with transparency, and/or create a look entirely your own.

### Details

![][demo2]

| Option           | Setting                       |  
| :--------------- | :---------------------------- |  
| Title            | `FP RokSprocket Animation P1` |  
| Show Title       | Hide                          |  
| Access           | Public                        |  
| Position         | slideshow                     |  
| Status           | Published                     |  
| Content Provider | Simple                        |  
| Type             | Features                      |  

### Filtered Article List

#### Simple Item 1

| Option    | Setting |  
| :-------- | :------ |  
| Position  | Right   |  
| Animation | FlipInX |  

**Title**

~~~ .html
A Modern Approach to Design.
~~~

**Description**

~~~ .html
Epsilon is a modern, sectioned based design, with a diverse infusion of background textures and patterns. These enrich and differentiate your site whilst maintaining an overall conservative approach, for flexible site application.
~~~

#### Simple Item 2

| Option    | Setting |  
| :-------- | :------ |  
| Position  | Left    |  
| Animation | FlipInX |  

**Title**

~~~
Background Slideshow
~~~

**Description**

~~~ .html
Epsilon provides for full width, custom, transitional background images, in the slideshow position, a full width container, specifically designed for RokSprocket's Features layout. It also has separate options for per panel background and content images.
~~~

#### Simple Item 3

| Option    | Setting |  
| :-------- | :------ |  
| Position  | Below   |  
| Animation | FlipInX |  

**Title**

~~~ .html
Custom Animation
~~~

**Description**

~~~ .html
Animation provides an extended layout of visual flair as well as smooth interaction for your visitors, to facilitate the seamless experience of using your site. RokSprocket Features benefits from a custom, per-panel array of up to 16 animation types.
~~~

### Layout Options

![][demo3]

| Option           | Setting       |  
| :--------------- | :------------ |  
| Display Limit    | ∞             |  
| Theme            | Animation     |  
| Article Titles   | Show          |  
| Article Text     | Show          |  
| Preview Length   | ∞             |  
| Strip HTML Tags  | No            |  
| Arrow Navigation | Hide          |  
| Pagination       | Show          |  
| Animation        | Crossfade     |  
| Autoplay         | Enable        |  
| Autoplay Delay   | 5             |  
| Image Resize     | Disable       |  

>> The **Animation** theme is unique to Epsilon and was created to give the RokSprocket mode a certain set of attributes that enables it to look the way it does in this template. You can find more information about overriding themes [here](../../extensions/roksprocket/layout_modes.md#custom-layout-theme-overrides).

### Advanced

![][demo4]

| Option              | Setting                    |  
| :------------------ | :------------------------- |  
| Module Class Suffix | `fp-slideshow fps-preset1` |  

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
