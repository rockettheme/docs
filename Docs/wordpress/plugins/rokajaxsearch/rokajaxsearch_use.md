---
title: RokAjaxSearch
description: Your Guide to Using RokAjaxSearch for WordPress
breadcrumb: /wordpress:WordPress/plugins:Plugins/!!rokajaxsearch:RokAjaxSearch

---

Plugin Settings
-----
Getting to the primary RokAjaxSearch settings menu is fairly straightforward. While RokAjaxSearch is identified as a widget, it is centrally managed via its Plugins page which can be found (once it is activated) under the Plugins area of the main Admin menu on the backend of WordPress. This settings page has a variety of different customization commands and options for you to choose from.

![][plugin2]

All settings set through this page affect every instance of the RokAjaxSearch widget. The widget itself can only be given a custom title by default, with other display options available via a separate plugin (such as Gantry).

![][plugin1]

:   1. **Preset Themes** Only applicable if using a non-formatted template, but you can select between a Blue, Light or Dark theme for the search module. [12%, 51%, se]
    2. **Load Default CSS** The module has inbuilt module styling so set this to Yes if you wish for it to work standalone. As we override this file from the template, you still need to set this to Yes for the styling to work. [15%, 60%, sw]
    3. **Google API** This field needs to be completed in order for the various Google search options to work. Please see [this site][googleapi] to retrieve an API Key. [19%, 51%, se]
    4. **Show Description** Set to yes to show a description with each search result. [22%, 60%, sw]
    5. **Show Read More** Set whether the Read More link should be display. [27%, 51%, se]
    6. **Read More Label** Set a label you'd like to have displayed for the **Read More** link. [30%, 71%, sw]
    7. **Hide Divs** This option allows you to set which elements of your site you wish to be excluded from searching. Enter the ID names separated by a comma such as: *logo-module, side-column,* and *maincontent*. [34%, 51%, se]
    8. **Display Content** Gives you access to item-specific settings for the articles title, description, image, and link. [38%, 59%, sw]
    9. **Order** Set the order of the search results. For example, if you set to Oldest First then the oldest item will be loaded in the search result. There are a variety of options to chose from. [41%, 51%, se]
    10. **Items Per Page** Set the limit for the number of search result pages, whether: 3, 5, 10, 15, 20, 25, 30 or 50 [45%, 58%, sw]
    11. **Limit Items** Set the limit for the number of search results per page, whether: 3, 5, 10, 15, 20, 25, 30 or 50 [49%, 51%, se]
    12. **Google Web Search** When enabled, an option will appear in the module to search Google Web Search. The API key needs to be correctly completed for this to work. [52%, 58%, sw]
    13. **Google Blog Search** When enabled, an option will appear in the module to search Google Blog Search. The API key needs to be correctly completed for this to work. [56%, 51%, se]
    14. **Google Image Search** When enabled, an option will appear in the module to search Google Images Search. The API key needs to be correctly completed for this to work. [60%, 58%, sw]
    15. **Google Video Search** When enabled, an option will appear in the module to search Google Videos Search. The API key needs to be correctly completed for this to work. [63%, 51%, se]
    16. **Image Size to Search** Select the image search size preference for Google Search, either Small, Medium, Large or Extra Large. [67%, 58%, sw]
    17. **Safe Search** Choose between the different Google preferences, either Strict, Moderate or Off. [71%, 51%, se]
    18. **Show Pagination** Set to Yes to show pagination for search results. [74%, 58%, sw]
    19. **Show Category** Sets the content filter rules for the widget. [78%, 51%, se]
    20. **Show Estimated** Show the estimated result for Google searches. [82%, 58%, sw]
    21. **Include Link** Set to yes to show a link to all search results. [85%, 51%, se]

1. **Preset Themes**: Only applicable if using a non-formatted template, but you can select between a Blue, Light or Dark theme for the search module.

2. **Load Default CSS**: The module has inbuilt module styling so set this to Yes if you wish for it to work standalone. As we override this file from the template, you still need to set this to Yes for the styling to work.

3. **Google API**: This field needs to be completed in order for the various Google search options to work. Please see [this site][googleapi] to retrieve an API Key.

4. **Show Description**: Set to yes to show a description with each search result.

5. **Show Read More**: Set whether the Read More link should be display.

6. **Read More Label**: Set a label you'd like to have displayed for the **Read More** link.

7. **Hide Divs**: This option allows you to set which elements of your site you wish to be excluded from searching. Enter the ID names separated by a comma such as: *logo-module, side-column,* and *maincontent*.

8. **Display Content**: Gives you access to item-specific settings for the articles title, description, image, and link.

9. **Order**: Set the order of the search results. For example, if you set to Oldest First then the oldest item will be loaded in the search result. There are a variety of options to chose from.

10. **Items Per Page**: Set the limit for the number of search result pages, whether: 3, 5, 10, 15, 20, 25, 30 or 50.

11. **Limit Items**: Set the limit for the number of search results per page, whether: 3, 5, 10, 15, 20, 25, 30 or 50.

12. **Google Web Search**: When enabled, an option will appear in the module to search Google Web Search. The API key needs to be correctly completed for this to work.

13. **Google Blog Search**: When enabled, an option will appear in the module to search Google Blog Search. The API key needs to be correctly completed for this to work.

14. **Google Image Search**: When enabled, an option will appear in the module to search Google Image Search. The API key needs to be correctly completed for this to work.

15. **Google Video Search**: When enabled, an option will appear in the module to search Google Videos Search. The API key needs to be correctly completed for this to work.

16. **Image Size to Search**: Select the image search size preference for Google Search, either Small, Medium, Large or Extra Large.

17. **Safe Search**: Choose between the different Google preferences, either Strict, Moderate or Off.

18. **Show Pagination**: Set to Yes to show pagination for search results.

19. **Show Category**: Sets the content filter rules for the widget.

20. **Show Estimated**: Show the estimated result for Google searches.

21. **Include Link**: Set to yes to show a link to all search results.

Widget Settings
-----
![][gantrywidget]

:   1. **Title** If a title is present in this field, it will appear along with the RokAjaxSearch widget. If left blank, no title will propagate. [15%, 20%, se]

1. **Title**: If a title is present in this field, it will appear along with the RokAjaxSearch widget. If left blank, no title will propagate.

All other options listed in the above image are added via Gantry. If you are using a theme build on [Gantry framework][gantry], then these options may allow you some additional variations on the widget's appearance and positioning. Here is a quick look at these options:

* **Widget Style**: Sets the widget style for the gallery. You can choose from Flush, Flush Bottom, or Flush Top.
* **Box Variation**: Sets a background look for the widget box, based on the active theme.
* **Title Variation**: Allows you to choose from different title variations, based on the theme.
* **Shadow Variation**: Allows you to choose from different shadow appearances, based on the theme.
* **Corner Variation**: Allows you to choose from different corner appearances, based on the theme.
* **Align Variation**: Allows you to choose from different alignment variations, based on the theme.
* **Margin Variation**: Allows you to choose from different margin variations, based on the theme.
* **Padding Variation**: Allows you to choose from different padding options.
* **Title Style**: Allows for standardcase, uppercase, and lowercase titling. 
* **Custom Chrome**: Allows you to decide between basic, menu, and standard custom chrome options. This is theme-specific.
* **Custom Variations**: This field allows you to add custom variations, determined in the theme's primary LESS file.


[featured]: assets/rokajaxsearch.png
[rokajaxsearch-download]: http://www.rockettheme.com/wordpress-downloads/plugins/free/rokajaxsearch/2629-rokajaxsearch-plugin/download
[plugin1]: assets/wp_rokajaxsearch_plugin_1.png
[plugin2]: assets/wp_rokajaxsearch_plugin_2.png
[gantrywidget]: assets/wp_rokajaxsearch_gantrywidget.png
[googleapi]: http://code.google.com/apis/ajaxsearch/signup.html
[gantry]: http://gantry-framework.org