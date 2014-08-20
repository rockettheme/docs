---
title: RokSprocket: Tables Layout Mode
description: Your Guide to the Tables RokSprocket Layout Mode for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!roksprocket:RokSprocket

---

Tables
-----

![][layout]

A tabular layout with image support, plus rows for price, four features, a description, as well as custom link labels and title. Tables has a single theme: Products.

![][layout_1]

:   1. **Title** This is the title of your module. [20%, 12%, se]
    2. **Show Title** Determines whether the title of the module will appear for visitors or remain hidden. [20%, 61%, sw]
    3. **Status** Sets the publishing status for the module. [28%, 63%, nw]
    4. **Access** Sets the access level for the module. [20%, 80%, se]
    5. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [42%, 5%, se]
    6. **Content Filter Rules** Sets the content filter rules for the module. [42%, 63%, se]

1. The **Title** field gives you the ability to set a title for the module itself. Every module has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look. The **Position** field right below it gives you the ability to set the position within the template's layout the module should appear in.

2. The **Show Title** option gives you the ability to determine whether or not the title of the module will appear with the module on the frontend.

3. The **Status** option allows you to determine the current publishing status of the module. An unpublished module will still appear on the backend for administrators, but will not appear on the live site.

4. The **Access** option gives you the ability to determine which user group will be able to see the module on the frontend. Someone logged in as a registered user may be able to see a module set at that level while random visitors do not see it.

5. The **Filtered Article List** gives you access to item-specific settings including:

    * **Title** - This is the title of the item as it appears in the module. You can select article title, none, or custom. If article title is selected in the **Simple** content provider, the simple item's title in the **Filtered Article List** will be used.
    * **Description** - This is the main text body of the item. You can use HTML in this field to customize how you want the content to appear.
    * **Image** - This field enables you to add an image which appears as a background for the item.
    * **Price** - Enables you to place a price in for the item.
    * **Feature 1 - 4** - This field enables you to enter a feature that appears in a row for the item.
    * **Link** - If set, the link will show a **Read More** button as well as link the title. On specific themes, it will link the image in the item, as well.
    * **Link Text** - Allows you to set specified text to appear in the link button.

6. The **Content Filter Rules** section gives you the ability to determine how the module will pull content to make up the quotes. For example, you can have the module pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the module. In the case of a **Simple** provider, this area allows you to add new items to the **Filtered Article List**.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you have chosen. We have broken down the **Tables Layout Options** and **Grids Article Defaults** sections below.

![][layout_2]

:   1. **Theme** This sets the theme for displaying items in the module. The **Tables** layout type presently only supports the **Product** theme. [12%, 11%, se]
    2. **Display Limit** The amount of items to show when rendering. [16%, 11%, se]
    3. **Preview Length** This option sets the amount of words you wish to limit the preview to within the item's text field. [20%, 11%, se]
    4. **Strip HTML Tags** This option removes HTML tags from the item text. [25%, 11%, se]
    5. **Previews Per Page** Sets the number of items to appear at one time. [30%, 11%, se]
    6. **Items Per Row** This option determines how many items appear in a single row. If you have a previews per page of 4, and this is set to 2, you will have two rows of items with two items each. [34%, 11%, se]
    7. **Arrow Navigation** This option enables arrow navigation for visitors to switch between pages of items in the module. [39%, 11%, se]
    8. **Pagination** This option enables pagination, which displays the amount of pages. [43%, 11%, se]
    9. **Animation** This option toggles the type of animation that appears as you transition between pages of tables. [47%, 11%, se]
    10. **Autoplay**: Automatically switches between pages of items without a required action by the visitor. [51%, 11%, se]
    11. **Autoplay Delay** Sets the delay between page switches during autoplay. [56%, 11%, se]
    12. **Image Resize** Allows you to set a maximum width and/or height of images that appear in the module. [60%, 11%, se]
    12. **Default Title** You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used. [73%, 11%, se]
    13. **Default Article Text** This field allows you to set default article text for all items in the module. If this is not changed from its default, then the article's introductory text is used. [78%, 11%, se]
    14. **Default Article Image** Determines which image field the module will default to when locating an image for the item. [82%, 11%, se]
    15. **Default Link** Determines which link field the module will default to when locating a link for the item. [87%, 11%, se]

1. **Theme**: This sets the theme for displaying items in the module. The **Tables** layout type presently only supports the **Product** theme.

2. **Display Limit**: The amount of items to show when rendering.

3. **Preview Length**: This option sets the amount of words you wish to limit the preview to within the item's text field.

4. **Strip HTML Tags**: This option removes HTML tags from the item text.

5. **Previews Per Page**: Sets the number of items to appear at one time.

6. **Items Per Row**: This option determines how many items appear in a single row. If you have a previews per page of 4, and this is set to 2, you will have two rows of items with two items each.

7. **Arrow Navigation**: This option enables arrow navigation for visitors to switch between pages of items in the module.

8. **Pagination**: This option enables pagination, which displays the amount of pages.

9. **Animation**: This option toggles the type of animation that appears as you transition between pages of tables.

10. **Autoplay**: Automatically switches between pages of items without a required action by the visitor.

11. **Autoplay Delay**: Sets the delay between page switches during autoplay.

12. **Default Title**: You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used.

13. **Default Article Text**: This field allows you to set default article text for all items in the module. If this is not changed from its default, then the article's introductory text is used.

14. **Default Article Image**: Determines which image field the module will default to when locating an image for the item.

15. **Default Link**: Determines which link field the module will default to when locating a link for the item.



[layout]: assets/tables.jpeg
[layout_1]: assets/tables_1.jpeg
[layout_2]: assets/tables_2.jpeg