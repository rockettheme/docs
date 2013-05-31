---
title: RokSprocket: Mosaic Layout Mode
description: Your Guide to the Mosaic RokSprocket Layout Mode for Joomla
breadcrumb: /joomla:Joomla/extensions:Extensions/!roksprocket:RokSprocket

---

### Mosaic
![][mosaic]
Mosaic displays content dynamically in blocks, that can be rearranged via tags or ordering commands.

![][mosaic_1]

:   1. **Title** This is the title of your module. [16%, 08%]
    2. **Show Title** Determines whether the title of the module will appear for visitors or remain hidden. [14%, 45%]
    3. **Status** Sets the publishing status for the module. [21%, 45%]
    4. **Access** Sets the access level for the module. [16%, 68%]
    5. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [53%, 50%]
    6. **Layout Type** This is where you will select the Layout Mode you wish to use for your RokSprocket Module. [47%, 85%]
    7. **Content Filter Rules** Sets the content filter rules for the module. [56%, 78%]

1. The **Title** field gives you the ability to set a title for the module itself. Every module has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look. The **Position** field right below it gives you the ability to set the position within the template's layout the module should appear in.

2. The **Show Title** option gives you the ability to determine whether or not the title of the module will appear with the module on the frontend.

3. The **Status** option allows you to determine the current publishing status of the module. An unpublished module will still appear on the backend for administrators, but will not appear on the live site.

4. The **Access** option gives you the ability to determine which user group will be able to see the module on the frontend. Someone logged in as a registered user may be able to see a module set at that level while random visitors don't see it.

5. The **Filtered Article List** gives you access to item-specific settings including:

    * **Title** - Allows you to override the article title in the module. The article title will be used if this is left at *Default*.
    * **Description** - Allows you to set a description for the feature. If this is left at *Default* the introtext from the article is used. 
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the feature. 
    * **Link** - If set, the link will show a *Read More** button as well as link the title. On specific themes, it will link the image in the feature, as well.
    * **Tags** - Comma separated list of tags for filtering on the frontend.

6. The **Content Provider and Layout Type** section gives you the ability to set the Layout Mode you wish to use for the module. This is often the first setting you want to pay attention to when creating a new RokSprocket module. The Content Provider can vary, but in most Joomla instances, this will default to Joomla.

7. The **Content Filter Rules** section gives you the ability to determine how the module will pull content to make up the features. For example, you can have the module pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the module.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you've chosen. We've broken down the **Features Layout Options** and **Features Article Defaults** sections below.

![][mosaic_2]

:   1. **Theme** This sets the theme for displaying features in the module. [11%, 27%]
    2. **Display Limit** The amount of articles to show when rendering. [15%, 27%]
    3. **Columns** Sets the number of columns articles are displayed in. [20%, 27%]
    4. **Preview Length** This option sets the amount of words you wish to limit the preview to within the module's article display. [25%, 27%]
    5. **Strip HTML Tags** This option removes HTML tags from the description of an article. [29%, 27%]
    6. **Blocks Per View** This sets the amount of blocks that show on a page load. If the amount is lesser than the **Display Limit**, a **Load More** function will appear. [34%, 27%]
    7. **Article Details** This option gives you control over whether details like the author's name or publishing date appear in the module. [38%, 27%]
    8. **Block Animation** Sets the combination of block animations used when rendering blocks in the mosaic. [44%, 27%]
    9. **Ordering** Ordering options available to users on the frontend. [52%, 27%]
    10. **Image Resize** Renders images in the mosaic to a maximum pixel width or height as set. This may not change the size of the actual mosaic blocks in some templates. [61%, 27%]
    11. **Default Title** You can set a default title for all articles from this field. If this selection is set at **Default Article Title**, then the article's given titles are used. [72%, 27%]
    12. **Default Article Text** This field allows you to set default article text for all features in the module. If this is not changed from its default, then the article's introductory text is used. [76%, 27%]
    13. **Default Article Image** Determines which image field the module will default to when locating an image for the feature. [81%, 27%]
    14. **Default Link** Determines which link field the module will default to when locating a link for the feature. [85%, 27%]

1. **Theme** sets the theme for displaying features in the module.

2. **Display Limit** sets the amount of articles to show when rendering.

3. **Columns** gives you the option to set the number of columns articles are displayed in.

4. The **Preview Length** option sets the amount of words you wish to limit the preview to within the module's article display.

5. **Strip HTML Tags** removes or preserves HTML tags in the description of an article.

6. **Blocks Per View** sets the amount of blocks that show on a page load. If the amount is lesser than the **Display Limit**, a **Load More** function will appear.

7. **Article Details** gives you control over whether details like the author's name or publishing date appear in the module.

8. **Block Animation** sets the combination of block animations used when rendering blocks in the mosaic. There needs to be at least one option in this field. These animations are rendered through CSS3 and may not be available on all browsers. 

9. **Ordering** sets ordering options available to users on the frontend. There needs to be at least one option in this field. If only one option is present, the switcher will not appear on the frontend.

10. **Image Resize** Renders images in the mosaic to a maximum pixel width or height as set. This may not change the size of the actual mosaic blocks in some templates.

11. **Default Title** sets a default title for all articles in the module. If this selection is set at **Default Article Title**, then the article's given titles are used.

12. **Default Article Text** allows you to set default article text for all features in the module. If this is not changed from its default, then the article's introductory text is used.

13. **Default Article Image** determines which image field the module will default to when locating an image for the feature.

14. **Default Link** determines which link field the module will default to when locating a link for the feature.

[mosaic]: assets/mosaic.png
[mosaic_link]: mosaic_mode.md
[mosaic_1]: assets/mosaic_1.png
[mosaic_2]: assets/mosaic_2.png