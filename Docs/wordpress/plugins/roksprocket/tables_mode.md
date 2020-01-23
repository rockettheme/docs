---
title: RokSprocket: Tables Layout Mode
description: Your Guide to the Tables RokSprocket Layout Mode for WordPress
breadcrumb: /wordpress:WordPress/!extensions:Extensions/!roksprocket:RokSprocket

---

Tables
-----

![][layout]

A tabular layout with image support, plus rows for price, four features, a description, as well as custom link labels and title. Tables has a single theme: Products.

![][layout_1]

:   1. **Title** This is the title of your widget. [22%, 13%, se]
    2. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [59%, 50%, sw]
    3. **Content Filter Rules** Sets the content filter rules for the widget. [42%, 75%, sw]

1. The **Title** field gives you the ability to set a title for the widget itself. Every widget has to have a title, though you can opt to hide it from public view for a cleaner, more theme integrated look. The **Position** field right below it gives you the ability to set the position within the theme's layout the widget should appear in.

2. The **Filtered Article List** gives you access to item-specific settings including:

    * **Title** - Allows you to override the article title in the widget. The article title will be used if this is left at *Default*. In the **Simple** content provider, the fallback for the default article title is the item name in the **Filtered Article List**.
    * **Description** - Allows you to set a description for the item. If this is left at *Default* the introtext from the article is used. 
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the item. 
    * **Link** - If set, the link will show a **Read More** button as well as link the title. On specific themes, it will link the image in the item, as well.

3. The **Content Filter Rules** section gives you the ability to determine how the widget will pull content to make up the grid items. For example, you can have the widget pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the widget. In the case of a **Simple** provider, this area allows you to add new items to the **Filtered Article List**.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you have chosen. We have broken down the **Tables Layout Options** and **Grids Article Defaults** sections below.

![][layout_2]

:   1. **Theme** This sets the theme for displaying items in the widget. The **Tables** layout type presently only supports the **Product** theme. [12%, 12%, se]
    2. **Display Limit** The amount of items to show when rendering. [16%, 12%, se]
    3. **Preview Length** This option sets the amount of words you wish to limit the preview to within the item's text field. [20%, 12%, se]
    4. **Strip HTML Tags** This option removes HTML tags from the item text. [25%, 12%, se]
    5. **Previews Per Page** Sets the number of items to appear at one time. [30%, 12%, se]
    6. **Items Per Row** This option determines how many items appear in a single row. If you have a previews per page of 4, and this is set to 2, you will have two rows of items with two items each. [34%, 12%, se]
    7. **Arrow Navigation** This option enables arrow navigation for visitors to switch between pages of items in the widget. [39%, 12%, se]
    8. **Pagination** This option enables pagination, which displays the amount of pages. [43%, 12%, se]
    9. **Animation** This option toggles the type of animation that appears as you transition between pages of tables. [47%, 12%, se]
    10. **Autoplay**: Automatically switches between pages of items without a required action by the visitor. [51%, 12%, se]
    12. **Autoplay Delay** Sets the delay between page switches during autoplay. [56%, 12%, se]
    12. **Image Resize** Allows you to set a maximum width and/or height of images that appear in the widget. [60%, 12%, se]
    12. **Default Title** You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used. [73%, 12%, se]
    13. **Default Article Text** This field allows you to set default article text for all items in the widget. If this is not changed from its default, then the article's introductory text is used. [78%, 12%, se]
    14. **Default Article Image** Determines which image field the widget will default to when locating an image for the item. [82%, 12%, se]
    15. **Default Link** Determines which link field the widget will default to when locating a link for the item. [87%, 12%, se]

1. **Theme**: This sets the theme for displaying items in the widget. The **Tables** layout type presently only supports the **Product** theme.

2. **Display Limit**: The amount of items to show when rendering.

3. **Preview Length**: This option sets the amount of words you wish to limit the preview to within the item's text field.

4. **Strip HTML Tags**: This option removes HTML tags from the item text.

5. **Previews Per Page**: Sets the number of items to appear at one time.

6. **Items Per Row**: This option determines how many items appear in a single row. If you have a previews per page of 4, and this is set to 2, you will have two rows of items with two items each.

7. **Arrow Navigation**: This option enables arrow navigation for visitors to switch between pages of items in the widget.

8. **Pagination**: This option enables pagination, which displays the amount of pages.

9. **Animation**: This option toggles the type of animation that appears as you transition between pages of tables.

10. **Autoplay**: Automatically switches between pages of items without a required action by the visitor.

11. **Autoplay Delay**: Sets the delay between page switches during autoplay.

12. **Default Title**: You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used.

13. **Default Article Text**: This field allows you to set default article text for all items in the widget. If this is not changed from its default, then the article's introductory text is used.

14. **Default Article Image**: Determines which image field the widget will default to when locating an image for the item.

15. **Default Link**: Determines which link field the widget will default to when locating a link for the item.



[layout]: assets/tables.jpeg
[layout_1]: assets/tables_1.jpeg
[layout_2]: assets/tables_2.jpeg