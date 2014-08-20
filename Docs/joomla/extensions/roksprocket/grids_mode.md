---
title: RokSprocket: Grids Layout Mode
description: Your Guide to the Grids RokSprocket Layout Mode for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!roksprocket:RokSprocket

---

Grids
-----

![][layout]

The **Grids** layout mode gives you the ability to quickly deploy a grid of images and/or other items that display in a modern grid-like fashion.

![][layout_1]

:   1. **Title** This is the title of your module. [25%, 12%, se]
    2. **Show Title** Determines whether the title of the module will appear for visitors or remain hidden. [25%, 61%, sw]
    3. **Status** Sets the publishing status for the module. [35%, 63%, nw]
    4. **Access** Sets the access level for the module. [25%, 81%, se]
    5. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [63%, 50%, sw]
    6. **Content Filter Rules** Sets the content filter rules for the module. [63%, 83%, sw]

1. The **Title** field gives you the ability to set a title for the module itself. Every module has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look. The **Position** field right below it gives you the ability to set the position within the template's layout the module should appear in.

2. The **Show Title** option gives you the ability to determine whether or not the title of the module will appear with the module on the frontend.

3. The **Status** option allows you to determine the current publishing status of the module. An unpublished module will still appear on the backend for administrators, but will not appear on the live site.

4. The **Access** option gives you the ability to determine which user group will be able to see the module on the frontend. Someone logged in as a registered user may be able to see a module set at that level while random visitors do not see it.

5. The **Filtered Article List** gives you access to item-specific settings including:

    * **Title** - Allows you to override the article title in the module. The article title will be used if this is left at *Default*. In the **Simple** content provider, the fallback for the default article title is the item name in the **Filtered Article List**.
    * **Description** - Allows you to set a description for the item. If this is left at *Default* the introtext from the article is used. 
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the item. 
    * **Link** - If set, the link will show a **Read More** button as well as link the title. On specific themes, it will link the image in the item, as well.

6. The **Content Filter Rules** section gives you the ability to determine how the module will pull content to make up the grid items. For example, you can have the module pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the module. In the case of a **Simple** provider, this area allows you to add new items to the **Filtered Article List**.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you have chosen. We have broken down the **Grids Layout Options** and **Grids Article Defaults** sections below.

![][layout_2]

:   1. **Theme** This sets the theme for displaying items in the module. [15%, 11%, se]
    2. **Display Limit** The amount of articles to show when rendering. [20%, 11%, se]
    3. **Columns** This option allows you to set the number of horizontal columns items appear in. [25%, 11%, se]
    4. **Preview Length** This option sets the amount of words you wish to limit the preview to within the module's article display. [32%, 11%, se]
    5. **Strip HTML Tags** This option removes HTML tags from the description of an article. [37%, 11%, se]
    6. **Block Animation** This option sets the the animation type(s) for the blocks when appearing or disappearing. The default is *Fade*. [43%, 11%, se]
    7. **Image Resize** This option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields. [48%, 11%, se]
    8. **Default Title** You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used. [65%, 11%, se]
    9. **Default Article Text** This field allows you to set default article text for all items in the module. If this is not changed from its default, then the article's introductory text is used. [71%, 11%, se]
    10. **Default Article Image** Determines which image field the module will default to when locating an image for the item. [76%, 11%, se]
    11. **Default Link** Determines which link field the module will default to when locating a link for the item. [82%, 11%, se]

1. **Theme**: This sets the theme for displaying items in the module.

2. **Display Limit**: The amount of articles to show when rendering.

3. **Columns**: This option allows you to set the number of horizontal columns items appear in.

4. **Preview Length**: This option sets the amount of words you wish to limit the preview to within the module's article display.

5. **Strip HTML Tags**: This option removes HTML tags from the description of an article.

6. **Block Animation**: This option sets the the animation type(s) for the blocks when appearing or disappearing. The default is *Fade*.

7. **Image Resize**: This option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields.

8. **Default Title**: You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used.

9. **Default Article Text**: This field allows you to set default article text for all items in the module. If this is not changed from its default, then the article's introductory text is used.

10. **Default Article Image**: Determines which image field the module will default to when locating an image for the item.

11. **Default Link**: Determines which link field the module will default to when locating a link for the item.

[layout]: assets/grids.jpeg
[layout_1]: assets/grids_1.jpeg
[layout_2]: assets/grids_2.jpeg