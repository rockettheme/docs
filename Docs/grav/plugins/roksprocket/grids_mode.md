---
title: RokSprocket: Grids Layout Mode
description: Your Guide to the Grids RokSprocket Layout Mode for Grav
breadcrumb: /grav:Grav/!extensions:Extensions/!roksprocket:RokSprocket

---

Grids
-----

![][layout]

The **Grids** layout mode gives you the ability to quickly deploy a grid of images and/or other items that display in a modern grid-like fashion.

![][layout_1]

:   1. **Title** This is the title of your widget. [27%, 13%, se]
    2. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [63%, 50%, sw]
    3. **Content Filter Rules** Sets the content filter rules for the widget. [63%, 83%, sw]

1. The **Title** field gives you the ability to set a title for the widget itself. Every widget has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look. The **Position** field right below it gives you the ability to set the position within the template's layout the widget should appear in.

2. The **Filtered Article List** gives you access to item-specific settings including:

    * **Title** - Allows you to override the article title in the widget. The article title will be used if this is left at *Default*. In the **Simple** content provider, the fallback for the default article title is the item name in the **Filtered Article List**.
    * **Description** - Allows you to set a description for the item. If this is left at *Default* the introtext from the article is used. 
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the item. 
    * **Link** - If set, the link will show a **Read More** button as well as link the title. On specific themes, it will link the image in the item, as well.

3. The **Content Filter Rules** section gives you the ability to determine how the widget will pull content to make up the grid items. For example, you can have the widget pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the widget. In the case of a **Simple** provider, this area allows you to add new items to the **Filtered Article List**.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you have chosen. We have broken down the **Grids Layout Options** and **Grids Article Defaults** sections below.

![][layout_2]

:   1. **Theme** This sets the theme for displaying items in the widget. [15%, 12%, se]
    2. **Display Limit** The amount of articles to show when rendering. [20%, 12%, se]
    3. **Columns** This option allows you to set the number of horizontal columns items appear in. [25%, 12%, se]
    4. **Preview Length** This option sets the amount of words you wish to limit the preview to within the widget's article display. [30%, 12%, se]
    5. **Strip HTML Tags** This option removes HTML tags from the description of an article. [35%, 12%, se]
    6. **Block Animation** This option sets the the animation type(s) for the blocks when appearing or disappearing. The default is *Fade*. [43%, 12%, se]
    7. **Image Resize** This option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields. [49%, 12%, se]
    8. **Default Title** You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used. [67%, 12%, se]
    9. **Default Article Text** This field allows you to set default article text for all items in the widget. If this is not changed from its default, then the article's introductory text is used. [73%, 12%, se]
    10. **Default Article Image** Determines which image field the widget will default to when locating an image for the item. [78%, 12%, se]
    11. **Default Link** Determines which link field the widget will default to when locating a link for the item. [84%, 12%, se]

1. **Theme**: This sets the theme for displaying items in the widget.

2. **Display Limit**: The amount of articles to show when rendering.

3. **Columns**: This option allows you to set the number of horizontal columns items appear in.

4. **Preview Length**: This option sets the amount of words you wish to limit the preview to within the widget's article display.

5. **Strip HTML Tags**: This option removes HTML tags from the description of an article.

6. **Block Animation**: This option sets the the animation type(s) for the blocks when appearing or disappearing. The default is *Fade*.

7. **Image Resize**: This option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields.

8. **Default Title**: You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used.

9. **Default Article Text**: This field allows you to set default article text for all items in the widget. If this is not changed from its default, then the article's introductory text is used.

10. **Default Article Image**: Determines which image field the widget will default to when locating an image for the item.

11. **Default Link**: Determines which link field the widget will default to when locating a link for the item.

[layout]: assets/grids.jpeg
[layout_1]: assets/grids_1.jpeg
[layout_2]: assets/grids_2.jpeg