---
title: RokSprocket: Headlines Layout Mode
description: Your Guide to the Headlines RokSprocket Layout Mode for Joomla
breadcrumb: /joomla:Joomla/extensions:Extensions/!roksprocket:RokSprocket

---

Headlines
-----
![][headlines]
Headlines is a content ticker layout mode. It can displays lines of text in succession.

![][headlines_1]

:   1. **Title** This is the title of your module. [19%, 14%, se]
    2. **Show Title** Determines whether the title of the module will appear for visitors or remain hidden. [19%, 59%, se]
    3. **Status** Sets the publishing status for the module. [26%, 63%, nw]
    4. **Access** Sets the access level for the module. [19%, 85%, sw]
    5. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [53%, 50%, sw]
    6. **Layout Type** This is where you will select the Layout Mode you wish to use for your RokSprocket Module. [51%, 83%, sw]
    7. **Content Filter Rules** Sets the content filter rules for the module. [61%, 79%, sw]

1. The **Title** field gives you the ability to set a title for the module itself. Every module has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look. The **Position** field right below it gives you the ability to set the position within the template's layout the module should appear in.

2. The **Show Title** option gives you the ability to determine whether or not the title of the module will appear with the module on the frontend.

3. The **Status** option allows you to determine the current publishing status of the module. An unpublished module will still appear on the backend for administrators, but will not appear on the live site.

4. The **Access** option gives you the ability to determine which user group will be able to see the module on the frontend. Someone logged in as a registered user may be able to see a module set at that level while random visitors don't see it.

5. The **Filtered Article List** gives you access to item-specific settings including:
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the headline. 
    * **Link** - If set, the link will show a **Read More** button as well as link the title. On specific themes, it will link the image in the headline, as well.
    * **Description** - Allows you to set a description for the headline. If this is left at *Default* the introtext from the article is used. 

6. The **Content Provider and Layout Type** section gives you the ability to set the Layout Mode you wish to use for the module. This is often the first setting you want to pay attention to when creating a new RokSprocket module. The Content Provider can vary, but in most Joomla instances, this will default to Joomla.

7. The **Content Filter Rules** section gives you the ability to determine how the module will pull content to make up the headlines. For example, you can have the module pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the module.

![][headlines_2]

:   1. **Theme** This sets the theme for displaying headlines in the module. [15%, 48%, sw]
    2. **Display Limit** The amount of articles to show when rendering. [19%, 69%, sw]
    3. **Label Text** This is where you input the text you wish to appear as the label preceding the headlines text. [25%, 42%, se]
    4. **Preview Length** This option sets the amount of words you wish to limit the preview to within the module's article display. [31%, 69%, sw]
    5. **Arrow Navigation** This option configures the arrow navigation behavior in the module. [36%, 49%, sw]
    6. **Animation**  This dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next. [42%, 62%, sw]
    7. **Autoplay** Sets whether you want the module to start rolling through headlines automatically when the page loads, or to await a command from the visitor. [47%, 42%, se]
    8. **Autoplay Delay** Sets the amount of time between cycled headlines in the module. The longer this delay (in seconds), the longer a single article will be featured in the module. [53%, 65%, sw]
    9. **Image Resize** This option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields. [62%, 43%, se]
    10. **Default Article Text** This field allows you to set default article text for all headlines in the module. If this is not changed from its default, then the article's introductory text is used. [74%, 66%, sw]
    11. **Default Article Image** Determines which image field the module will default to when locating an image for the feature. [80%, 43%, se]
    12. **Default Link** Determines which link field the module will default to when locating a link for the feature. [85%, 66%, sw]

1. The **Theme** option sets the theme for displaying headlines in the module. These themes determine how the headlines look within the module. You can choose the one that best fits your template and/or personal taste.

2. The **Display Limit** field sets the amount of articles shown when the page is rendered.  Setting this limit to zero or infinity will allow it to cycle through all applicable items.

3. **Label Text** is where you input the text you wish to appear as the label preceding the headlines text.

4. **Preview Length** sets the amount of words you wish to limit the preview to within the module's article display. 

5. **Arrow Navigation** configures the arrow navigation behavior in the module.

6. The **Animation** dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next.

7. **Autoplay** sets whether you want the module to start rolling through headlines automatically when the page loads, or to await a command from the visitor.

8. **Autoplay Delay** sets the amount of time between cycled headlines in the module. The longer this delay (in seconds), the longer a single article will be featured in the module.

9. **Image Resize** is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields.

10. The **Default Article Text** field allows you to set default article text for all headlines in the module. If this is not changed from its default, then the article's introductory text is used.

11. **Default Article Image** determines which image field the module will default to when locating an image for the feature. 

12. **Default Link** determines which link field the module will default to when locating a link for the headline. 

[headlines]: assets/headlines.jpeg
[headlines_link]: headlines_mode.md
[headlines_1]: assets/headlines_1.jpeg
[headlines_2]: assets/headlines_2.jpeg
