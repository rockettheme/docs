---
title: RokSprocket: Sliders Layout Mode
description: Your Guide to the Sliders RokSprocket Layout Mode for WordPress
breadcrumb: /wordpress:WordPress/!extensions:Extensions/!roksprocket:RokSprocket

---

Sliders
-----

![][layout]

A vertical list layout, set within an accordion setup with images being used as the main structure. Text is also supported. **Sliders** has a single theme: **Accordion**.

![][layout_1]

:   1. **Title** This is the title of your widget. [27%, 13%, se]
    2. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [59%, 50%, sw]
    3. **Content Filter Rules** Sets the content filter rules for the widget. [55%, 75%, sw]

1. The **Title** field gives you the ability to set a title for the widget itself. Every widget has to have a title, though you can opt to hide it from public view for a cleaner, more theme integrated look. The **Position** field right below it gives you the ability to set the position within the theme's layout the widget should appear in.

2. The **Filtered Article List** gives you access to item-specific settings including:

    * **Title** - Allows you to override the article title in the widget. The article title will be used if this is left at *Default*. In the **Simple** content provider, the fallback for the default article title is the item name in the **Filtered Article List**.
    * **Description** - Allows you to set a description for the item. If this is left at *Default* the introtext from the article is used. 
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the item. 
    * **Link** - If set, the link will show a **Read More** button as well as link the title. On specific themes, it will link the image in the item, as well.

3. The **Content Filter Rules** section gives you the ability to determine how the widget will pull content to make up the grid items. For example, you can have the widget pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the widget. In the case of a **Simple** provider, this area allows you to add new items to the **Filtered Article List**.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you have chosen. We have broken down the **Sliders Layout Options** and **Grids Article Defaults** sections below.

![][layout_2]

:   1. **Display Limit** The amount of items to show when rendering. [13%, 12%, se]
    2. **Theme** This sets the theme for displaying items in the widget. [17%, 12%, se]
    3. **Panel Height** This sets the height of the panel to either auto or fixed. If it is set to fixed, the **Fixed Height Value** will be used. [21%, 12%, se]
    4. **Fixed Height Value** This sets the height of the panel when the **Panel Height** is set to **Fixed**. [25%, 12%, se]
    5. **Overlay** Toggles a dark overlay which puts inactive panels out of focus, drawing more attention to the active panel. [30%, 12%, se]
    6. **Article Titles** Allows you to toggle whether or not article titles appear in the item display. [34%, 12%, se]
    7. **Article Text** Allows you to toggle whether or not article text appears in the item display. [39%, 12%, se]
    8. **Preview Length** This option sets the amount of words you wish to limit the preview to within the item's text field. [43%, 12%, se]
    9. **Strip HTML Tags** This option removes HTML tags from the item text. [49%, 12%, se]
    10. **Arrow Navigation**: This option enables arrow navigation for visitors to switch between pages of items in the widget. [53%, 12%, se]
    12. **Autoplay**: Automatically switches between pages of items without a required action by the visitor. [57%, 12%, se]
    12. **Autoplay Delay**: Sets the delay between page switches during autoplay. [62%, 12%, se]
    13. **Default Title** You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used. [73%, 12%, se]
    14. **Default Article Text** This field allows you to set default article text for all items in the widget. If this is not changed from its default, then the article's introductory text is used. [77%, 12%, se]
    15. **Default Article Image** Determines which image field the widget will default to when locating an image for the item. [82%, 12%, se]
    16. **Default Link** Determines which link field the widget will default to when locating a link for the item. [86%, 12%, se]

1. **Display Limit**: The amount of items to show when rendering.

2. **Theme**: This sets the theme for displaying items in the widget.

3. **Panel Height**: This sets the height of the panel to either auto or fixed. If it is set to fixed, the **Fixed Height Value** will be used.

4. **Fixed Height Value**: This sets the height of the panel when the **Panel Height**: is set to **Fixed**.

5. **Overlay**: Toggles a dark overlay which puts inactive panels out of focus, drawing more attention to the active panel.

6. **Article Titles**: Allows you to toggle whether or not article titles appear in the item display.

7. **Article Text**: Allows you to toggle whether or not article text appears in the item display.

8. **Preview Length**: This option sets the amount of words you wish to limit the preview to within the item's text field.

9. **Strip HTML Tags**: This option removes HTML tags from the item text.

10. **Arrow Navigation**: This option enables arrow navigation for visitors to switch between pages of items in the widget.

11. **Autoplay**: Automatically switches between pages of items without a required action by the visitor.

12. **Autoplay Delay**: Sets the delay between page switches during autoplay.

13. **Default Title**: You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used.

14. **Default Article Text**: This field allows you to set default article text for all items in the widget. If this is not changed from its default, then the article's introductory text is used.

15. **Default Article Image**: Determines which image field the widget will default to when locating an image for the item.

16. **Default Link**: Determines which link field the widget will default to when locating a link for the item.

[layout]: assets/sliders.jpeg
[layout_1]: assets/sliders_1.jpeg
[layout_2]: assets/sliders_2.jpeg