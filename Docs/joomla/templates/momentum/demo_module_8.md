---
title: Momentum: Recreating the Demo - Featured Article
description: Your Guide to Recreating Elements of the Momentum Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/momentum:Momentum

---

Featured Article
-----

![][demo]

This area of the front page is an article. Articles appear within the **Mainbody** area of the front page.

There is also a primary **RokGallery** module that appears in the **fp-rokgallery** position. We created a gallery called **Front** for this position. Below are the details for both of these module types, starting with a preset-specific module.

The most important thing to remember when embedding a module in an article is to use the `loadposition` call. It tells Joomla to load any module assigned to that position within the article body. For example, `{loadposition fp-rokgallery}` loads the fp-rokgallery position in the article featured on the front page.

Turning on Mainbody Content
-----

This content appears on the front page because the **Display Component** option has been turned on in the template settings. You can find these settings by navigating to **Administrator -> Extensions -> Templates Manager -> Momentum -> Advanced**.

![][advanced]

Once this is done, you can navigate to the **Menu Manager** by going to **Administrator -> Menus -> Menu Manager**. From here, you'll want to find the menu item for your home page and select it so you can access its settings. For our demo, it is located in **Main Menu -> Home**.

![][menu]

:   1. **Leading Articles** [43%, 72%, se]
    2. **Article Order** [67%, 72%, se]

In order to show two featured articles on the front page, we placed a `1` in the **Leading Articles** setting within the **Layout Options** menu. The **Article Order** has been set to **Featured Articles Order**. We also turned **Linked Titles** off in the **Article Options** menu.

Article Properties
-----

The **Popular Features** article is a standard article with the **Featured** option turned on so it appears in the front page mainbody.

Here is the **Article Text** we used:

~~~ .html
<p><strong>RokGallery</strong> is an advanced photo <strong>gallery</strong> solution for Joomla, that rests on a <strong>custom tagging architecture</strong>, combined with native application <strong>slice</strong> editing.</p>

<div class="rt-demo-grid-4 nomarginleft">
    <ul class="checkmark normalfont nomarginbottom">
        <li><strong>Gallery Styling:</strong> the template has integrated styled for the main Gallery pages</li>
        <li><strong>Administrator:</strong> select the main background image via the RokGallery interface</li>
    </ul>
</div>
<div class="rt-demo-grid-4">
    <ul class="checkmark normalfont nomarginbottom">
        <li><strong>Slideshow:</strong> use RoKGallery's slideshow to rotate between main background images</li>
        <li><strong>Grid Layout:</strong> the RokGallery module, in Grid mode, also benefits from styled suppor.</li>
    </ul>
</div>
<div class="clear"></div>

{loadposition fp-rokgallery}

~~~

Once this article is created and set to **Featured**, it should appear on the front page.

FP RokGallery Module
-----

### Details

![][demo5]

| Option     | Setting         |  
| :--------- | :-------------- |  
| Title      | `FP RokGallery` |  
| Show Title | Hide            |  
| Access     | Public          |  
| Position   | fp-rokgallery   |  
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
| Sort By                   | Random                      |  
| Sort Direction            | Ascending                   |  
| Slice Limit               | 4                           |  
| Gallery Style             | Light                       |  
| Gallery Layout            | Grid                        |  
| Grid Columns              | 4                           |  
| Select a Background Image | Blank                       |  

### Advanced Options

![][demo7]

| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix |         |  

[demo]: assets/demo_8.jpeg
[advanced]: assets/advanced.jpeg
[menu]: assets/menu.jpeg
[demo5]: assets/rokgallery_1.jpeg
[demo6]: assets/rokgallery_2.jpeg
[demo7]: assets/rokgallery_3.jpeg