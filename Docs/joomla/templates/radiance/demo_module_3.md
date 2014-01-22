---
title: Radiance: Recreating the Demo - Radiance Gallery
description: Your Guide to Recreating Elements of the Radiance Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Radiance:Radiance

---

Radiance Gallery
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

There is also a primary **RokGallery** module that appears in the **fp-rokgallery** position. We created a gallery called **Front** for this position. Below are the details for both of these module types, starting with a preset-specific module.

The most important thing to remember when embedding a module in an article is to use the `loadposition` call. It tells Joomla to load any module assigned to that position within the article body. For example, `{loadposition rokgallery}` loads the `rokgallery` position in the article featured on the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Radiance -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [43%, 71%, se]
    2. **Article Order** [67%, 71%, se]

In order to show two featured articles on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Popular Features** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
{loadposition rokgallery}<br />
~~~

Once this article is created and set to **Featured**, it should appear on the front page.

FP RokGallery Module
-----

### Details

![][demo5]

| Option     | Setting         |  
| :--------- | :-------------- |  
| Title      | `FP RokGallery` |  
| Show Title | Show            |  
| Access     | Public          |  
| Position   | rokgallery      |  
| Status     | Published       |  

### Basic Options

![][demo6]

| Option                    | Setting                     |  
| :------------------------ | :-------------------------- |  
| Gallery                   | Front                       |  
| Link Type                 | Link to RokBox1 Slice Image |  
| Default Linked Item       | - Home                      |  
| Show Title                | No                          |  
| Show Caption              | No                          |  
| Sort By                   | Title                       |  
| Sort Direction            | Ascending                   |  
| Slice Limit               | 8                           |  
| Gallery Style             | Light                       |  
| Gallery Layout            | Grid                        |  
| Grid Columns              | 4                           |  
| Select a Background Image | Blank                       |  

### Advanced Options

![][demo7]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_3.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg
[demo5]: assets/rokgallery_1.jpeg
[demo6]: assets/rokgallery_2.jpeg
[demo7]: assets/rokgallery_3.jpeg