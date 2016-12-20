---
title: RokStock: Setup Guide
description: Your Guide to Using RokStock for Grav
breadcrumb: /grav:Grav/!plugins:Plugins/rokstock:RokStock

---

User Controls
-----
![][rokstock]

Users have the ability to add their own stocks to the widget from the frontend without having to have administrative access. You can define what, exactly, users can and can not do with the widget in cases where you want to display only what you have pre-selected to appear on RokStock.

Users can add new stocks, remove the default ones (configured by you on the backend), and refresh the widget to pull the most current information available.

A cookie enables users to maintain their specific settings after leaving the page so their experience picks up where they left off upon returning.

Widget Options
-----
You can access RokStock's main widget settings by navigating to **Admin -> Plugins -> RokStock**. Any changes you make here will be reflected in any occurrences of the RokStock widget on the frontend of your site.

![][settings]

:   1. **Default Stocks** The widget displays the stock information of a valid stock title. This option decides what stock information is displayed in the widget. Separate stock titles by a comma to show multiple stocks. For example, .DJI, .INX, .IXIC will display stock information from Dow Jones Industrial Average, S&P 500 INDEX, and NASDAQ COMPOSITE. [33%, 25%, ne]
    2. **User Interaction** You can set this parameter to allow the user to interact with RokStock in the frontend. If enabled, the user can add, remove, reorder the stocks. All modifications will be visible to the user only. [39%, 25%, ne]
    3. **Save/Restore Status** When enabled, this option stores the users modification in the frontend, like the stock index they added, remove, or reordered details in a cookie. It changes when the cookie has expired. [44%, 25%, ne]
    4. **Store Duration (days)** This parameter is self explanatory. You can set the duration in days for the cookie to be kept.  [49%, 25%, ne]
    5. **Open links in new page** You can set this parameter to define whether the stock information page should be opened in a new window or the same window, when the user clicks on the stock index title. [55%, 25%, ne]
    6. **Show main chart** At the top of the widget, you can see the graphic chart. When enabled, the widget will display the graphic chart.  [60%, 25%, ne]
    7. **Tooltips Details** If this parameter is enabled, when the users hovers over the stock index title, it will show its details. [65%, 25%, ne]
    8. **Show Main Chart (Hours)** This parameter controls whether the time format, that appears via tooltips, is in the 12h or the 24hr format.  [70%, 25%, ne]

1. **Default Stocks**: The widget displays the stock information of a valid stock title. This option decides what stock information is displayed in the widget. Separate stock titles by a comma to show multiple stocks. For example, .DJI, .INX, .IXIC will display stock information from Dow Jones Industrial Average, S&P 500 INDEX, and NASDAQ COMPOSITE. 

2. **User Interaction**: You can set this parameter to allow the user to interact with RokStock in the frontend. If enabled, the user can add, remove, reorder the stocks. All modifications will be visible to the user only.

3. **Save/Restore Status**: When enabled, this option stores the users modification in the frontend, like the stock index they added, removed, or reordered details in a cookie. It changes when the cookie has expired. 

4. **Store Duration (days)**: This parameter is self explanatory. You can set the duration in days for the cookie to be kept. 

5. **Open links in new page**: You can set this parameter to define whether the stock information page should be opened in a new window or the same window, when the user clicks on the stock index title.

6. **Show main chart**: At the top of the widget you can see the graphic chart. When enabled, the widget will display the graphic chart. 

7. **Tooltips Details**: If this parameter is enabled, when the users hovers over the stock index title, it will show its details. 

8. **Tooltips time axis hours**: This parameter controls whether the time format, that appears via tooltips, is in the 12h or the 24hr format. 

[rokstock]: assets/rokstock.png
[rokstock_setup_1]: assets/rokstock_setup_1.png
[rokstock_setup_2]: assets/rokstock_setup_2.png
[rokstock_setup_3]: assets/rokstock_setup_3.png
[rokstock_setup_4]: assets/rokstock_setup_4.png
[settings]: assets/wp_rokstock_settings.png