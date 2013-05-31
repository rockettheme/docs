---
title: RokSprocket: Features Layout Mode
description: Your Guide to the Features RokSprocket Layout Mode for Joomla
breadcrumb: /wordpress:WordPress/plugins:Plugins/!roksprocket:RokSprocket

---

Features
-----
![][features]
Features is a content slideshow/showcase layout mode. It can display both images and text, or images only, with varying options on their display. Here's a look at the options screen for the Features layout mode.

![][features1]

:   1. **Title** This is the title of your widget. [16%, 08%]
    2. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [53%, 50%]
    3. **Layout Type** This is where you will select the Layout Mode you wish to use for your RokSprocket widget. [47%, 85%]
    4. **Content Filter Rules** Sets the content filter rules for the widget. [56%, 78%]

1. The **Title** field gives you the ability to set a title for the widget itself. Every widget has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look. The **Position** field right below it gives you the ability to set the position within the template's layout the widget should appear in.

2. The **Filtered Article List** gives you access to item-specific settings including:

    * **Title** - Allows you to override the article title in the widget. The article title will be used if this is left at *Default*.
    * **Description** - Allows you to set a description for the feature. If this is left at *Default* the introtext from the article is used. 
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the feature. 
    * **Link** - If set, the link will show a *Read More** button as well as link the title. On specific themes, it will link the image in the feature, as well.

3. The **Content Provider and Layout Type** section gives you the ability to set the Layout Mode you wish to use for the widget. This is often the first setting you want to pay attention to when creating a new RokSprocket widget. The Content Provider can vary, but in most Joomla instances, this will default to Joomla.

4. The **Content Filter Rules** section gives you the ability to determine how the widget will pull content to make up the features. For example, you can have the widget pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the widget.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you've chosen. We've broken down the **Features Layout Options** and **Features Article Defaults** sections below.

![][features_2]

:   1. **Display Limit** The amount of articles to show when rendering. [11%, 27%]
    2. **Theme** This sets the theme for displaying features in the widget. [16%, 27%]
    3. **Article Titles** This toggle enables you to show or hide article titles. [20%, 27%]
    4. **Article Text** This toggle allows you to show or hide article text in a features. [24%, 27%]
    5. **Preview Length** This option sets the amount of words you wish to limit the preview to within the widget's article display. [29%, 27%]
    6. **Strip HTML Tags** This option removes HTML tags from the description of an article. [33%, 27%]
    7. **Arrow Navigation** This option determines whether you wish to show or hide the arrow navigation controls on the widget. [38%, 27%]
    8. **Pagination** This toggle gives you control over whether or not you wish to show pagination. [42%, 27%]
    9. **Animation**  This dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next. [47%, 27%]
    10. **Autoplay** Sets whether you want the widget to start rolling through features automatically when the page loads, or to await a command from the visitor. [51%, 27%]
    11. **Autoplay Delay** Sets the amount of time between cycled features in the widget. The longer this delay (in seconds), the longer a single article will be featured in the widget. [55%, 27%]
    12. **Image Resize** This option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields. [62%, 27%]
    13. **Default Title** You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the article's given titles are used. [72%, 27%]
    14. **Default Article Text** This field allows you to set default article text for all features in the widget. If this is not changed from its default, then the article's introductory text is used. [76%, 27%]
    15. **Default Article Image** Determines which image field the widget will default to when locating an image for the feature. [81%, 27%]
    16. **Default Link** Determines which link field the widget will default to when locating a link for the feature. [85%, 27%]

1. The **Display Limit** field sets the amount of articles shown when the page is rendered.  Setting this limit to zero or infinity will allow it to cycle through all applicable items.

2. The **Theme** option sets the theme for displaying features in the widget. These themes determine how the features look within the widget. You can choose the one that best fits your template and/or personal taste.

3. The **Article Titles** toggle enables you to show or hide article titles. When a photo and/or the description says it all, you can opt to hide the title from the widget feature display.

4.  The **Article Text** toggle allows you to show or hide article text in a features. This is handy when you want to only display titles and photos in the widget. 

5.  The **Preview Length** option sets the amount of words you wish to limit the preview to within the widget's article display. This can help reduce occurrences of controls overlaying the description and make your features more uniform.

6. The **Strip HTML Tags** option removes HTML tags from the description of an article.

7.  The **Arrow Navigation** option determines whether you wish to show or hide the arrow navigation controls on the widget.

8. The **Pagination** toggle gives you control over whether or not you wish to show pagination.

9.  The **Animation** dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next.

10.  **Autoplay** sets whether you want the widget to start rolling through features automatically when the page loads, or to await a command from the visitor.

11.  **Autoplay Delay** sets the amount of time between cycled features in the widget. The longer this delay (in seconds), the longer a single article will be featured in the widget.

12.  The **Image Resize** option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields. This option is disabled by default, but can be used to fit a variety of templates which would benefit from this uniformity. In a responsive template, images will continue to expand or shrink based on the grid and browser window size.

13.  You can set a default title for all articles from the **Default Title** field. If this selection is set at **Default Article Title**, then the article's given titles are used. 

14. The **Default Article Text** field allows you to set default article text for all features in the widget. If this is not changed from its default, then the article's introductory text is used. You can choose full text or to pull from the meta description for each article in this field.

15. The **Default Article Image** option gives you the ability to set a standard default image for articles. This includes: a custom image, article intro image, and article full image. Alternatively, you can leave this set to default and it will grab the global default article image.

16. The **Default Article Link** gives you the ability to set a default link field from articles in this widget. For example, if you wish to link to the link provided in the article's **Link A** or **Link B** settings, you can do so here.

[features]: assets/features.png
[features_link]: features_mode.md
[features_1]: assets/features_1.png
[features_2]: assets/features_2.png
[features1]: assets/wp_roksprocket_features_1.png