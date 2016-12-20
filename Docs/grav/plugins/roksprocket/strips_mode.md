---
title: RokSprocket: Strips Layout Mode
description: Your Guide to the Strips RokSprocket Layout Mode for Grav
breadcrumb: /grav:Grav/!plugins:Plugins/roksprocket:RokSprocket

---

### Strips
![][strips_demo]

Strips displays content in long rectangular blocks, which appear vertically on larger browsers and horizontally on smaller mobile screens.

Themes
-----

The **Strips** layout mode has four built-in themes. These include: **Default**, **Separated**, **Cards**, and **Parallel**.

![][default]

The **Default** theme gives you a simple, flexible layout for your content that gives your images center stage, overlaying your text content on top. You can set this theme up in several different ways.

![][separated]

The **Separated** theme gives each item in your widget its own content area, each with plenty of room for your image, title, and description content.

![][cards]

The **Cards** theme is all about your images. This theme makes it easy to display rich, bold content in a single widget without sacrificing that modern, stylish look.

![][parallel]

The **Parallel** theme gives your items plenty of room to roam, highlighting text content and presenting it in a clean, professional way.

Setup
-----

![][strips_1]

:   1. **Title** This is the title you wish to give the RokSprocket instance. This is only used as a label on the backend, as the widget title will be what appears on the frontend of the site. [28%, 15%, se]
    2. **Filtered Article List Options** Gives you access to item-specific settings for the posts title, description, image, and link. [55%, 52%, nw]
    3. **Content Filter Rules** Sets the content filter rules for the widget. [54%, 83%, sw]

1. The **Title** field gives you the ability to set a title for the widget itself. Every widget has to have a title, though you can opt to hide it from public view for a cleaner, more theme integrated look. The **Position** field right below it gives you the ability to set the position within the theme's layout the widget should appear in.

2. The **Filtered Article List** gives you access to item-specific settings including:
    * **Image** - This allows you to circumvent the assigned image from the post and replace it with one specifically for the headline. 
    * **Link** - If set, the link will show a *Read More** button as well as link the title. On specific themes, it will link the image in the headline, as well.
    * **Description** - Allows you to set a description for the headline. If this is left at *Default* the introtext from the post is used. 

3. The **Content Filter Rules** section gives you the ability to determine how the widget will pull content to make up the headlines. For example, you can have the widget pull posts that are within a specific category, contain a particular name or keyword in the title, or choose specific posts. You can also modify how this content is sorted in the widget.

![][strips_2]

:   1. **Display Limit** The amount of posts to show when rendering. [11%, 53%, sw]
    2. **Theme** This sets the theme for displaying strips in the module. [16%, 75%, sw]
    3. **Article Titles** This toggle enables you to show or hide post titles. [20%, 74%, sw]
    4. **Article Text** This toggle allows you to show or hide post text in a strips. [24%, 49%, sw]
    5. **Preview Length** This option sets the amount of words you wish to limit the preview to within the module's post display. [29%, 70%, sw]
    6. **Strip HTML Tags** This option removes HTML tags from the description of a post. [33%, 46%, sw]
    7. **Arrow Navigation** This option determines whether you wish to show or hide the arrow navigation controls on the module. [37%, 51%, sw]
    8. **Pagination** This toggle gives you control over whether or not you wish to show pagination. [42%, 51%, sw]
    9. **Animation**  This dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next. [46%, 60%, sw]
    10. **Autoplay** Sets whether you want the widget to start rolling through strips automatically when the page loads, or to await a command from the visitor. [50%, 53%, sw]
    11. **Autoplay Delay** Sets the amount of time between cycled strips in the module. The longer this delay (in seconds), the longer a single post will be featured in the module. [55%, 68%, sw]
    12. **Image Resize** This option is best utilized on a non-responsive theme. It renders a copy of the selected image with a maximum width or height determined in these fields. [60%, 85%, sw]
    13. **Default Title** You can set a default title for all posts from this field. If this selection is set at `Default post Title`, then the post's given titles are used. [73%, 67%, sw]
    14. **Default Article Text** This field allows you to set default post text for all strips in the module. If this is not changed from its default, then the post's introductory text is used. [77%, 67%, sw]
    15. **Default Article Image** Determines which image field the widget will default to when locating an image for the feature. [82%, 70%, sw]
    16. **Default Link** Determines which link field the widget will default to when locating a link for the feature. [86%, 67%, sw]

1. The **Theme** option sets the theme for displaying strips in the module. These themes determine how the strips look within the module. You can choose the one that best fits your theme and/or personal taste.

2. The **Display Limit** field sets the amount of posts shown when the page is rendered.  Setting this limit to zero or infinity will allow it to cycle through all applicable items.

3. The **Preview Length** option sets the amount of words you wish to limit the preview to within the module's post display. This can help reduce occurrences of controls overlaying the description and make your strips more uniform.

4.  The **Strip HTML Tags** option removes HTML tags from the description of a post.

5.  The **Previews per Page** option gives you control over how many post previews show on each page.

6. **Items Per Row** sets the amount of post items to show in each row.

7.  The **Arrow Navigation** option determines whether you wish to show or hide the arrow navigation controls on the module.

8. The **Pagination** toggle gives you control over whether or not you wish to show pagination.

9.  The **Animation** dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next.

10.  **Autoplay** sets whether you want the widget to start rolling through strips automatically when the page loads, or to await a command from the visitor.

11.  **Autoplay Delay** sets the amount of time between cycled strips in the module. The longer this delay (in seconds), the longer a single post will be featured in the module.

12.  The **Image Resize** option is best utilized on a non-responsive theme. It renders a copy of the selected image with a maximum width or height determined in these fields. This option is disabled by default, but can be used to fit a variety of themes which would benefit from this uniformity. In a responsive theme, images will continue to expand or shrink based on the grid and browser window size.

13.  You can set a default title for all posts from the **Default Title** field. If this selection is set at **Default post Title**, then the post's given titles are used. 

14. The **Default Article Text** field allows you to set default post text for all strips in the module. If this is not changed from its default, then the post's introductory text is used. You can choose to use post content, an assigned post excerpt, the default article text, or to have nothing appear at all..

15. The **Default Article Image** option gives you the ability to set a standard default image for posts. This includes: a custom image, post intro image, and post full image. Alternatively, you can leave this set to default and it will grab the global default post image.

16. The **Default Article Link** gives you the ability to set a default link field from posts in this module. For example, if you wish to link to the link provided in the post's **Link A** or **Link B** settings, you can do so here.

[features]: assets/features.png
[headlines]: assets/headlines.png
[lists]: assets/lists.png
[mosaic]: assets/mosaic.png
[tabs]: assets/tabs.png
[features_link]: features_mode.md
[lists_link]: lists_mode.md
[tabs_link]: tabs_mode.md
[mosaic_link]: mosaic_mode.md
[headlines_link]: headlines_mode.md
[strips_link]: strips_mode.md
[features_1]: assets/features_1.png
[features_2]: assets/features_2.jpeg
[lists_1]: assets/lists_1.png
[lists_2]: assets/lists_2.jpeg
[mosaic_1]: assets/mosaic_1.png
[mosaic_2]: assets/mosaic_2.jpeg
[strips_1]: assets/strips_1.jpg
[strips_2]: assets/strips_2.jpeg
[headlines_1]: assets/headlines_1.png
[headlines_2]: assets/headlines_2.png
[tabs_1]: assets/tabs_1.png
[tabs_2]: assets/tabs_2.png
[separated]: assets/strips_separated.jpeg
[default]: assets/strips_default.jpeg
[cards]: assets/strips_cards.jpeg
[parallel]: assets/strips_parallel.jpeg
[roksprocket_module_1]: assets/roksprocket_module_1.png
[strips_demo]: assets/strips_demo.png