---
title: RokSprocket: Lists Layout Mode
description: Your Guide to the Lists RokSprocket Layout Mode for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!roksprocket:RokSprocket

---

### Lists

![][lists]

Lists is a vertical display content mode, with accordion support. Here is a look at the options screen for the Lists layout mode.

Themes
-----

There are three themes that come built in to the **Lists** layout mode in **RokSprocket**. 

![][default]

The first of these themes is the **Default** theme. This theme creates a standard RokSprocket Lists module, popularly used in many sites to display a lot of content in a relatively small space. It can be set to either **Collapsible** or **Static** to create a compact or standard look.

![][portrait]

The **Portrait** theme makes images the focus of your content. In addition to your item title and/or text, your images appear at all times in either the **Collapsible** or **Static** format.

![][modern]

The **Modern** theme gives you the best of both worlds. It is a modern, flat design approach that mimics the content approach of the default theme, giving you full control over hot much or how little content is featured in the module.

Setup
-----

![][lists_1]

:   1. **Title** This is the title of your module. [19%, 13%, se]
    2. **Show Title** Determines whether the title of the module will appear for visitors or remain hidden. [20%, 58%, se]
    3. **Status** Sets the publishing status for the module. [25%, 64%, sw]
    4. **Access** Sets the access level for the module. [20%, 81%, se]
    5. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [53%, 50%, sw]
    6. **Content Filter Rules** Sets the content filter rules for the module. [48%, 78%, sw]

1. The **Title** field gives you the ability to set a title for the module itself. Every module has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look. The **Position** field right below it gives you the ability to set the position within the template's layout the module should appear in.

2. The **Show Title** option gives you the ability to determine whether or not the title of the module will appear with the module on the frontend.

3.  The **Status** option allows you to determine the current publishing status of the module. An unpublished module will still appear on the backend for administrators, but will not appear on the live site.

4. The **Access** option gives you the ability to determine which user group will be able to see the module on the frontend. Someone logged in as a registered user may be able to see a module set at that level while random visitors do not see it.

5. The **Filtered Article List** gives you access to item-specific settings including:

    * **Title** - Allows you to override the article title in the module. The article title will be used if this is left at *Default*.
    * **Description** - Allows you to set a description for the item. If this is left at *Default* the introtext from the article is used. 
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the display within the module. 
    * **Link** - If set, the link will show a **Read More** button as well as link the title. On specific themes, it will link the image in the feature, as well.

6. The **Content Filter Rules** section gives you the ability to determine how the module will pull content to make up the items. For example, you can have the module pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the module.

Below the **Content Filter Rules** section are two options areas specific to the layout mode you have chosen. We have broken down the **Lists Layout Options** and **Lists Article Defaults** sections below.

![][lists_2]

:   1. **Theme** This sets the theme for displaying lists in the module. [13%, 37%, se]
    2. **Collapsible Preview** This toggle allows you to enable or disable the collapsible preview capability of the module. [15%, 50%, sw]
    3. **Display Limit** The amount of articles to show when rendering. [21%, 37%, se]
    4. **Preview Length** This option sets the amount of words you wish to limit the preview to within the module's article display. [26%, 67%, sw]
    5.  **Strip HTML Tags** This option removes HTML tags from the description of an article. [31%, 37%, se]
    6. **Preview Per Page** This option allows you to set the number of article previews that appear per page in the module. [35%, 64%, sw]
    7. **Arrow Navigation** This option determines whether you wish to show or hide the arrow navigation controls on the module. [40%, 37%, se]
    8. **Pagination** This toggle gives you control over whether or not you wish to show pagination. [44%, 48%, sw]
    9. **Autoplay** Sets whether you want the module to start rolling through lists automatically when the page loads, or to await a command from the visitor. [49%, 37%, se]
    10. **Autoplay Delay** Sets the amount of time between cycled lists in the module. The longer this delay (in seconds), the longer a single article will be featured in the module. [54%, 62%, sw]
    11. **Image Resize** This option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields. [62%, 37%, se]
    12. **Default Title** You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used. [72%, 61%, sw]
    13. **Default Article Text** This field allows you to set default article text for all lists in the module. If this is not changed from its default, then the article's introductory text is used. [77%, 37%, se]
    14. **Default Article Image** Determines which image field the module will default to when locating an image for the feature. [81%, 64%, sw]
    15. **Default Link** Determines which link field the module will default to when locating a link for the feature. [86%, 37%, se]

1.  The **Theme** option sets the theme for displaying lists in the module. These themes determine how the lists look within the module. You can choose the one that best fits your template and/or personal taste.

2. The **Collapsible Preview** toggle gives you the ability to choose whether or not the lists should include a collapsible preview feature. When enabled, only one article preview at a time will show expanded.

3.  The **Display Limit** field sets the amount of articles shown when the page is rendered.  Setting this limit to zero or infinity will allow it to cycle through all applicable items.

4. The **Preview Length** option sets the amount of words you wish to limit the preview to within the module's article display. This can help reduce occurrences of controls overlaying the description and make your lists more uniform.

5. The **Strip HTML Tags** option removes HTML tags from the description of an article.

6. The **Previews Per Page** setting allows you to determine how many previews appear per page within the module.

7.  The **Arrow Navigation** option determines whether you wish to show or hide the arrow navigation controls on the module.

8.  The **Pagination** toggle gives you control over whether or not you wish to show pagination.

9.  **Autoplay** sets whether you want the module to start rolling through lists automatically when the page loads, or to await a command from the visitor.

10. **Autoplay Delay** sets the amount of time between cycled lists in the module. The longer this delay (in seconds), the longer a single article will be featured in the module.

11.  The **Image Resize** option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields. This option is disabled by default, but can be used to fit a variety of templates which would benefit from this uniformity. In a responsive template, images will continue to expand or shrink based on the grid and browser window size.

12.  You can set a default title for all articles from the **Default Title** field. If this selection is set at **Default Article Title**, then the articles' given titles are used. 

13.  The **Default Article Text** field allows you to set default article text for all lists in the module. If this is not changed from its default, then the article's introductory text is used. You can choose full text or to pull from the meta description for each article in this field.

14.  The **Default Article Image** option gives you the ability to set a standard default image for articles. This includes: a custom image, article intro image, and article full image. Alternatively, you can leave this set to default and it will grab the global default article image.

15.  The **Default Article Link** gives you the ability to set a default link field from articles in this module. For example, if you wish to link to the link provided in the article's **Link A** or **Link B** settings, you can do so here.

[lists]: assets/lists.jpeg
[lists_link]: layout_modes.md#lists
[lists_1]: assets/lists_1.jpg
[lists_2]: assets/lists_2.jpeg
[modern]: assets/lists_modern.jpeg
[portrait]: assets/lists_portrait.jpeg
[default]: assets/lists_default.jpeg
