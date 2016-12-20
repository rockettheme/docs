---
title: RokSprocket: Tabs Layout Mode
description: Your Guide to the Tabs RokSprocket Layout Mode for Grav
breadcrumb: /grav:Grav/!plugins:Plugins/roksprocket:RokSprocket

---

### Tabs

![][tabs]
Tabs is a tabbed content display mode, presenting content in dynamically sizing tabs.

![][tabs1]

:   1. **Title** This is the title you wish to give the RokSprocket instance. This is only used as a label on the backend, as the widget title will be what appears on the frontend of the site. [28%, 15%, se]
    2. **Filtered Article List Options** Gives you access to item-specific settings for the posts title, description, image, and link. [55%, 52%, nw]
    3. **Content Filter Rules** Sets the content filter rules for the widget. [54%, 83%, sw]

1. The **Title** field gives you the ability to set a title for the widget itself. Every widget has to have a title, though you can opt to hide it from public view for a cleaner, more theme integrated look. The **Position** field right below it gives you the ability to set the position within the theme's layout the widget should appear in.

2. The **Filtered Article List** gives you access to item-specific settings including:
    * **Image** - This allows you to circumvent the assigned image from the post and replace it with one specifically for the headline. 
    * **Link** - If set, the link will show a *Read More** button as well as link the title. On specific themes, it will link the image in the headline, as well.
    * **Description** - Allows you to set a description for the headline. If this is left at *Default* the introtext from the post is used. 

3. The **Content Filter Rules** section gives you the ability to determine how the widget will pull content to make up the headlines. For example, you can have the widget pull posts that are within a specific category, contain a particular name or keyword in the title, or choose specific posts. You can also modify how this content is sorted in the widget.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you have chosen. We have broken down the **Tabs Layout Options** and **Tabs Article Defaults** sections below.

![][tabs_2]

:   1. **Theme** This sets the theme for displaying tabs in the module. [12%, 50%, sw]
    2. **Tabs Position** This option sets where in the widget the tabs will appear. [16%, 51%, sw]
    3. **Display Limit** This option sets the amount of items that display when rendering. 0 or ∞ indicates unlimited. [22%, 75%, sw]
    4. **Animation**  This dropdown gives you the ability to set the type of animation that happens during transitions from one tab to the next. [27%, 62%, sw]
    5. **Autoplay** Sets whether you want the widget to start rolling through tabs automatically when the page loads, or to await a command from the visitor. [32%, 55%, sw]
    6. **Autoplay Delay** Sets the amount of time between cycled tabs in the module. The longer this delay (in seconds), the longer a single post will be featured in the module. [37%, 69%, sw]
    7. **Image Resize** Sets the maximum width and/or height of displayed thumbnails. [43%, 85%, sw]
    8. **Preview Length** This toggle allows you to set the length (in words) of the preview. [51%, 73%, sw]
    9.  **Strip HTML Tags** This option removes HTML tags from the description of a post. [57%, 50%, sw]
    10. **Default Title** You can set a default title for all posts from this field. If this selection is set at **Default post Title**, then the post's given titles are used.  [68%, 67%, sw]
    11. **Default Icon** Determines which image the widget will default to when locating an icon for the tab. [73%, 69%, sw]
    12. **Default Link** Determines which link field the widget will default to when locating a link for the tab. [78%, 67%, sw]
    13. **Default Article Text** This field allows you to set default post text for all tab in the module. If this is not changed from its default, then the post's introductory text is used. [83%, 67%, sw]

1. The **Theme** option sets the theme for displaying tabs in the module. This may not be adjustable, depending on the theme.

2. **Tabs Position** sets where in the widget the tabs will appear. 

3. **Display Limit** sets the amount of items that display when rendering. 0 or ∞ indicates unlimited.

4. **Animation** gives you the ability to set the type of animation that happens during transitions from one tab to the next. 

5. **Autoplay** sets whether you want the widget to start rolling through tabs automatically when the page loads, or to await a command from the visitor.

6. **Autoplay Delay** changes the amount of time between cycled tabs in the module. The longer this delay (in seconds), the longer a single post will be featured in the module.

7. **Image Resize** Sets the maximum width and/or height of displayed thumbnails.

8. **Preview Length** This toggle allows you to set the length (in words) of the preview.

9. **Strip HTML Tags** removes or preserves HTML tags in the description of a post.

10. You can set a default title for all posts from the **Default Title** field. If this selection is set at **Default Article Title**, then the post's given titles are used.

11. **Default Icon** determines which image the widget will default to when locating an icon for the tab.

12. **Default Link** determines which link field the widget will default to when locating a link for the tab.

13. **Default Article Text** allows you to set default post text for all features in the widget. If this is not changed from its default, then the post's introductory text is used. You can choose to use post content, an assigned post excerpt, the default article text, or to have nothing appear at all.

[tabs]: assets/tabs.png
[tabs_link]: tabs_mode.md
[tabs1]: assets/tabs_1.jpg
[tabs_2]: assets/tabs_2.png
