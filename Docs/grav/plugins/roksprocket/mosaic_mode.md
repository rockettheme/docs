---
title: RokSprocket: Mosaic Layout Mode
description: Your Guide to the Mosaic RokSprocket Layout Mode for Grav
breadcrumb: /grav:Grav/!plugins:Plugins/roksprocket:RokSprocket

---

Mosaic
-----

![][mosaic]

Mosaic displays content dynamically in blocks, that can be rearranged via tags or ordering commands.

Themes
-----

![Default][default]

Mosaic has two built-in themes available. The **Default** theme gives users a content-rich mosaic view of content that can be easily rearranged and sorted. This theme is the standard for the Mosaic layout mode, and one of the most popular ways RokSprocket is used today.

![Gallery][gallery]

The second theme is **Gallery** which is just as easily rearranged, filtered, and sorted by users on the frontend, but has a modern gapless look that makes it exceptionally easy to create great looking image galleries and content presentations with minimal required effort.

Setup
-----

![][mosaic1]

:   1. **Title** This is the title you wish to give the RokSprocket instance. This is only used as a label on the backend, as the widget title will be what appears on the frontend of the site. [28%, 15%, se]
    2. **Filtered Article List Options** Gives you access to item-specific settings for the posts title, description, image, and link. [55%, 52%, nw]
    3. **Content Filter Rules** Sets the content filter rules for the widget. [54%, 83%, sw]

1. The **Title** field gives you the ability to set a title for the widget itself. Every widget has to have a title, though you can opt to hide it from public view for a cleaner, more theme integrated look. The **Position** field right below it gives you the ability to set the position within the theme's layout the widget should appear in.

2. The **Filtered Article List** gives you access to item-specific settings including:
    * **Image** - This allows you to circumvent the assigned image from the post and replace it with one specifically for the headline. 
    * **Link** - If set, the link will show a *Read More** button as well as link the title. On specific themes, it will link the image in the headline, as well.
    * **Description** - Allows you to set a description for the headline. If this is left at *Default* the introtext from the post is used. 

3. The **Content Filter Rules** section gives you the ability to determine how the widget will pull content to make up the headlines. For example, you can have the widget pull posts that are within a specific category, contain a particular name or keyword in the title, or choose specific posts. You can also modify how this content is sorted in the widget.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you have chosen. We have broken down the **Features Layout Options** and **Features Article Defaults** sections below.

![][mosaic_2]

:   1. **Theme** This sets the theme for displaying features in the widget. [12%, 53%, sw]
    2. **Display Limit** The amount of posts to show when rendering. [16%, 74%, sw]
    3. **Columns** Sets the number of columns posts are displayed in. [21%, 47%, sw]
    4. **Preview Length** This option sets the amount of words you wish to limit the preview to within the widget's post display. [24%, 74%, sw]
    5. **Only Show Tags** This field allows you to insert tags that you wish to have appear in the filter and in items. If the field is blank, all tags will be shown. [29%, 76%, sw]
    6. **Strip HTML Tags** This option removes HTML tags from the description of a post. [34%, 50%, sw]
    7. **Blocks Per View** This sets the amount of blocks that show on a page load. If the amount is lesser than the **Display Limit**, a **Load More** function will appear. [37%, 69%, sw]
    8. **Article Details** This option gives you control over whether details like the author's name or publishing date appear in the widget. [42%, 71%, sw]
    9. **Block Animation** Sets the combination of block animations used when rendering blocks in the mosaic. [46%, 80%, sw]
    10. **Ordering** Ordering options available to users on the frontend. [53%, 80%, sw]
    11. **Image Resize** Renders images in the mosaic to a maximum pixel width or height as set. This may not change the size of the actual mosaic blocks in some themes. [60%, 86%, sw]
    12. **Default Title** You can set a default title for all posts from this field. If this selection is set at **Default Article Title**, then the post's given titles are used. [74%, 67%, sw]
    13. **Default Article Text** This field allows you to set default post text for all features in the widget. If this is not changed from its default, then the post's introductory text is used. [78%, 68%, sw]
    14. **Default Article Image** Determines which image field the widget will default to when locating an image for the feature. [83%, 69%, sw]
    15. **Default Link** Determines which link field the widget will default to when locating a link for the feature. [87%, 67%, sw]

1. **Theme** sets the theme for displaying features in the widget.

2. **Display Limit** sets the amount of posts to show when rendering.

3. **Columns** gives you the option to set the number of columns posts are displayed in.

4. The **Preview Length** option sets the amount of words you wish to limit the preview to within the widget's post display.

5. **Only Show Tags** This field allows you to insert tags that you wish to have appear in the filter and in items. If the field is blank, all tags will be shown.

6. **Strip HTML Tags** removes or preserves HTML tags in the description of a post.

7. **Blocks Per View** sets the amount of blocks that show on a page load. If the amount is lesser than the **Display Limit**, a **Load More** function will appear.

8. **Article Details** gives you control over whether details like the author's name or publishing date appear in the widget.

9. **Block Animation** sets the combination of block animations used when rendering blocks in the mosaic. There needs to be at least one option in this field. These animations are rendered through CSS3 and may not be available on all browsers. 

10. **Ordering** sets ordering options available to users on the frontend. There needs to be at least one option in this field. If only one option is present, the switcher will not appear on the frontend.

11. **Image Resize** Renders images in the mosaic to a maximum pixel width or height as set. This may not change the size of the actual mosaic blocks in some themes.

12. **Default Title** sets a default title for all posts in the widget. If this selection is set at **Default Article Title**, then the post's given titles are used.

13. **Default Article Text** allows you to set default post text for all features in the widget. If this is not changed from its default, then the post's introductory text is used. You can choose to use post content, an assigned post excerpt, the default article text, or to have nothing appear at all.

14. **Default Article Image** determines which image field the widget will default to when locating an image for the feature.

15. **Default Link** determines which link field the widget will default to when locating a link for the feature.

[mosaic]: assets/mosaic.png
[mosaic_link]: mosaic_mode.md
[mosaic1]: assets/mosaic_1.jpeg
[mosaic_2]: assets/mosaic_2.jpeg
[gallery]: assets/mosaic_gallery.jpeg
[default]: assets/mosaic_default.jpeg
