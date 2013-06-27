---
title: RokStock: Setup Guide
description: Your Guide to Using RokStock for Joomla
breadcrumb: /joomla:Joomla/extensions:Extensions/rokstock:RokStock

---

User Controls
-----
![][rokstock]

Users have the ability to add their own stocks to the module from the frontend without having to have administrative access. You can define what, exactly, users can and can't do with the module in cases where you want to display only what you have pre-selected to appear on RokStock.

Users can add new stocks, remove the default ones (configured by you on the backend), and refresh the module to pull the most current information available.

A cookie enables users to maintain their specific settings after leaving the page so their experience picks up where they left off upon returning.

Administrator Options
-----

### Details
![][rokstock_setup_2]

:   1. **Title** This is the title of your module. [24%, 39%, sw]
    2. **Show Title** Determines whether the title of the module will appear for visitors or remain hidden. [31%, 30%, sw]
    3. **Position** Sets the publishing status for the module. [37%, 43%, sw]
    4. **Status** Determines the publishing status of the module. [47%, 43%, sw]
    5. **Access** Sets the access level for the module. [54%, 38%, sw]
    6. **Ordering** Sets the ordering for the module. [60%, 22%, se]
    7. **Start Publishing** Determines when the module should be published on your site. [66%, 38%, sw]
    8. **Finish Publishing** Sets an end date/time for your module to appear on the frontend. [73%, 22%, se]
    9. **Language** Allows you to pick a language for your module. This list is determined by the supported languages installed on your Joomla site. [79%, 38%, sw]
    10. **Note** A place to jot down a note which appears in the module list on the backend. [86%, 22%, se]

1. The **Title** field gives you the ability to set a title for the module itself. Every module has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look.

2. The **Show Title** option gives you the ability to determine whether or not the title of the module will appear with the module on the frontend.

3. The **Position** option allows you to determine where in your layout the module will appear.

4. **Status** option allows you to determine the current publishing status of the module. An unpublished module will still appear on the backend for administrators, but will not appear on the live site.

5. The **Access** option gives you the ability to determine which user group will be able to see the module on the frontend. Someone logged in as a registered user may be able to see a module set at that level while random visitors don't see it.

6. **Ordering** gives you the ability to set the ordering for the module. 

7. **Start Publishing** determines when the module should be published on your site. This is useful in cases where you want to have the module appear at specific times of the day. For RokStock, this might be during business hours, or when the market is open.

8. You can use **Finish Publishing** to set an end date/time for your module to appear on the frontend.

9. **Language** allows you to pick a language for your module. This list is determined by the supported languages installed on your Joomla site. 

10. You can use the **Note** field to jot down a note which appears in the module list on the backend.

### Basic Options
![][rokstock_setup_3]

:   1. **Default Stocks** The module displays the stock information of a valid stock title. This option decides what stock information is displayed in the module. Separate stock titles by a comma to show multiple stocks. For example, .DJI, .INX, .IXIC will display stock information from Dow Jones Industrial Average, S&P 500 INDEX, and NASDAQ COMPOSITE.  [24%, 65%, sw]
    2. **User Interaction** You can set this parameter to allow the user to interact with RokStock in the frontend. If enabled, the user can add, remove, reorder the stocks. All modifications will be visible to the user only. [32%, 32%, se]
    3. **Save/Restore Status** When enabled, this option stores the users modification in the frontend, like the stock index they added, remove, or reordered details in a cookie. It changes when the cookie has expired.  [40%, 32%, se]
    4. **Store Duration (days)** This parameter is self explanatory. You can set the duration in days for the cookie to be kept.  [48%, 32%, se]
    5. **Open links in new page** You can set this parameter to define whether the stock information page should be opened in a new window or the same window, when the user click on the stock index title. [54%, 32%, se]
    6. **Show main chart** At the top of the module you can see the graphic chart. When enable, the module will display the graphic chart.  [62%, 32%, se]
    7. **Tooltips Details** If this parameter is enabled, when the users hovers over the stock index title, it will show its details. [71%, 32%, se]
    8. **Tooltips time axis hours** This is the parameter controls whether the time format, that appears via tooltips, is in the 12h or the 24hr format. [79%, 32%, se]

RokStock is a highly configurable module that allows you to control the various aspects of its appearance and functions. Details of each options are as follows:-

1. **Default Stocks**: The module displays the stock information of a valid stock title. This option decides what stock information is displayed in the module. Separate stock titles by a comma to show multiple stocks. For example, .DJI, .INX, .IXIC will display stock information from Dow Jones Industrial Average, S&P 500 INDEX, and NASDAQ COMPOSITE. 

2. **User Interaction**: You can set this parameter to allow the user to interact with RokStock in the frontend. If enabled, the user can add, remove, reorder the stocks. All modifications will be visible to the user only.

3. **Save/Restore Status**: When enabled, this option stores the users modification in the frontend, like the stock index they added, remove, or reordered details in a cookie. It changes when the cookie has expired. 

4. **Store Duration (days)**: This parameter is self explanatory. You can set the duration in days for the cookie to be kept. 

5. **Open links in new page**: You can set this parameter to define whether the stock information page should be opened in a new window or the same window, when the user click on the stock index title.

6. **Show main chart**: At the top of the module you can see the graphic chart. When enable, the module will display the graphic chart. 

7. **Tooltips Details**: If this parameter is enabled, when the users hovers over the stock index title, it will show its details. 

8. **Tooltips time axis hours**: This is the parameter controls whether the time format, that appears via tooltips, is in the 12h or the 24hr format. 

### Advanced Options
![][rokstock_setup_4]

:   1. **Module Class Suffix** This is a suffix applied to the CSS class of the module. This allows for individual module styling. [34%, 61%, sw]
    2. **Caching** Selects whether or not to cache the content of this module. [44%, 35%, se]
    3. **Cache Time** This option sets the time between module recaching. [51%, 60%, sw]
    4. **Module Tag** This sets the HTML tag for the module. [58%, 34%, se]
    5. **Bootstrap Size** This option specifies how many columns the module will use. [64%, 60%, sw]
    6. **Header Tag** This field sets the HTML tag for the module header/title. [70%, 34%, se]
    7. **Header Class** This field sets the CSS class for the module header/title. [77%, 60%, sw]
    8. **Module Style** This option allows for an override of the template style for its position. [83%, 34%, se]

1. **Module Class Suffix**: A suffix applied to the CSS class of the module. This allows for individual module styling.

2. **Caching**: Selects whether or not to cache the content of this module.

3. **Cache Time**: Sets the time between module recaching.

4. **Module Tag**: Sets the HTML tag for the module.

5. **Bootstrap Size**: Specifies how many columns the module will use.

6. **Header Tag**: Sets the HTML tag for the module header/title.

7. **Header Class**: Sets the CSS class for the module header/title.

8. **Module Style**: Allows for an override of the template style for its position.

[rokstock]: assets/rokstock.jpeg
[rokstock_setup_1]: assets/rokstock_setup_1.jpeg
[rokstock_setup_2]: assets/rokstock_setup_2.jpeg
[rokstock_setup_3]: assets/rokstock_setup_3.jpeg
[rokstock_setup_4]: assets/rokstock_setup_4.jpeg