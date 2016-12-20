---
title: RokGallery: Widget Guide
description: Your Guide to Setting Up and Using RokGallery Widgets for Joomla
breadcrumb: /grav:Grav/!plugins:Plugins/rokgallery:RokGallery

---

Creating a Widget
-----

![][widget4]

Creating a RokGallery widget is a fairly straightforward process. You Would create it as you would any other widget by navigating to **Admin -> Appearance -> Widgets** and selecting **RokGallery** from **Available Widgets** and dragging them to the desired widget position on the right side of the page.

### Widget Configuration

For the purpose of this documentation, we will split the widget settings into multiple images, each with an explanation of the various options and what they mean. Within the Widget field of Grav, this appears as a single, continuous block.

![][widget1]

:   1. **Show Title** This is where you can insert title of your widget. If anything is written in this field, it will appear as a title for the widget. If left blank, no title will appear. [25%, 28%]
    2. **Gallery** This option allows you to assign a RokGallery tag gallery to the widget. Simply hit **Select** and choose the gallery you wish to assign to the widget. You can also assign gallery slice settings to the widget through this option. [32%, 28%]
    3. **Link Type** This option sets the action resulting from clicking the image in the gallery. You can set it to work with [RokBox](http://www.rockettheme.com/grav/plugins/rokbox) or one determined by the slice settings of the image, the full image, or do nothing at all. [38%, 28%]
    4. **Default Linked Item** If you have selected **Link in Slice** and you have not set a link within the slice, this will be the link the gallery defaults to. [45%, 28%]
    5. **Show Title** This option sets whether or not the title of a slice is shown in the gallery. [52%, 28%]
    6. **Show Caption** This option sets whether or not the caption of a slice appears in the gallery. [58%, 28%]
    7. **Sort By** This option sets the default sorting order for images in the gallery. [65%, 28%]
    8. **Sort Direction** You can choose to have items sorted in ascending or descending order based on the **Sort By** setting. [72%, 28%]
    9. **Slice Limit** You can set the limit of slices which appear in the gallery. [79%, 28%]
    10. **Gallery Style** This option allows you to choose from a light or dark gallery style, affecting the look of the gallery within the widget. [85%, 28%]

1. **Show Title**: This is where you can insert title of your widget. If anything is written in this field, it will appear as a title for the widget. If left blank, no title will appear.

2. **Gallery**: This option allows you to assign a RokGallery tag gallery to the widget. Simply hit **Select** and choose the gallery you wish to assign to the widget. You can also assign gallery slice settings to the widget through this option.

3. **Link Type**: This option sets the action resulting from clicking the image in the gallery. You can set it to work with [RokBox](http://www.rockettheme.com/grav/plugins/rokbox) or one determined by the slice settings of the image, the full image, or do nothing at all.

4. **Default Linked Item**: If you have selected **Link in Slice** and you have not set a link within the slice, this will be the link the gallery defaults to.

5. **Show Title**: This option sets whether or not the title of a slice is shown in the gallery.

6. **Show Caption**: This option sets whether or not the caption of a slice appears in the gallery.

7.  **Sort By**: This option sets the default sorting order for images in the gallery.

8. **Sort Direction**: You can choose to have items sorted in ascending or descending order based on the **Sort By** setting.

9. **Slice Limit** You can set the limit of slices which appear in the gallery.

10. **Gallery Style**: This option allows you to choose from a light or dark gallery style, affecting the look of the gallery within the widget.

#### Grid
The **Grid** layout allows you the option to choose how many columns appear in your grid, and to select a background image (if your theme allows).

![][widget5]

:   1. **Gallery Layout** The gallery can be laid out in a Grid, Slideshow, or Showcase pattern. [10%, 29%]
    2. **Grid Columns** This option sets the number of columns used to display slices in the Grid layout. [16%, 29%]
    3. **Widget Style** (Supported Gantry Themes Only) Sets the widget style for the gallery. You can choose from Flush, Flush Bottom, or Flush Top. [21%, 29%]
    4. **Box Variation** (Supported Gantry Themes Only) Sets a background look for the widget box, based on the active theme. [26%, 29%]
    5. **Title Variation** (Supported Gantry Themes Only) Allows you to choose from different title variations, based on the theme. [31%, 29%]
    6. **Shadow Variation** (Supported Gantry Themes Only) Allows you to choose from different shadow appearances, based on the theme. [37%, 29%]
    7. **Corner Variation** (Supported Gantry Themes Only) Allows you to choose from different corner appearances, based on the theme. [42%, 29%]
    8. **Align Variation** (Supported Gantry Themes Only) Allows you to choose from different alignment variations, based on the theme. [47%, 29%]
    9. **Margin Variation** (Supported Gantry Themes Only) Allows you to choose from different margin variations, based on the theme. [53%, 29%]
    10. **Padding Variation** (Supported Gantry Themes Only) Allows you to choose from different padding options. [58%, 29%]
    11. **Title Style** (Supported Gantry Themes Only) Allows for standardcase, uppercase, and lowercase titling.  [66%, 29%]
    12. **Custom Chrome** (Supported Gantry Themes Only) Allows you to decide between basic, menu, and standard custom chrome options. This is theme-specific. [71%, 29%]
    13. **Custom Variations** (Supported Gantry Themes Only) This field allows you to add custom variations, determined in the theme's primary LESS file. [77%, 29%]

1. **Gallery Layout**: The gallery can be laid out in a Grid, Slideshow, or Showcase pattern. This option more than any other impacts the way the gallery will appear within the widget block on the site. The options appearing below this are dynamically generated based on the gallery layout selected.

2. **Grid Columns**: This option sets the number of columns used to display slices in the Grid layout.
>>**Options 3-13 are specific to themes powered by the Gantry framework and will only appear when a Gantry theme is active.**

3. **Widget Style**: Sets the widget style for the gallery. You can choose from Flush, Flush Bottom, or Flush Top.

4. **Box Variation**: Sets a background look for the widget box, based on the active theme.

5. **Title Variation**: Allows you to choose from different title variations, based on the theme.

6. **Shadow Variation**: Allows you to choose from different shadow appearances, based on the theme.

7. **Corner Variation**: Allows you to choose from different corner appearances, based on the theme.

8. **Align Variation**: Allows you to choose from different alignment variations, based on the theme.

9. **Margin Variation**: Allows you to choose from different margin variations, based on the theme.

10. **Padding Variation**: Allows you to choose from different padding options.

11. **Title Style**: Allows for standardcase, uppercase, and lowercase titling.

12. **Custom Chrome**: Allows you to decide between basic, menu, and standard custom chrome options. This is theme-specific.

13. **Custom Variations**: This field allows you to add custom variations, determined in the theme's primary LESS file.

#### Slideshow Layout

The Slideshow layout allows you to determine if you wish to show arrows on either side of the image as well as set your navigation and animation types. You can also tell it whether or not you wish slideshows to autoplay, and with what delay between images.

![][widget2]

:   1. **Gallery Layout** The gallery can be laid out in a Grid, Slideshow, or Showcase pattern. [13%, 30%]
    2. **Show Arrows** This option determines if and/or when navigation arrows appear over the displayed image. [23%, 30%]
    3. **Navigation Type** If multiple navigation types are available, they will appear as an option in this list. [33%, 30%]
    4. *Slices Animation Type** This option determines what animation style (or styles) will be used to animate slices in the gallery. [43%, 30%]
    5. **Animation Duration** This field determines (in milliseconds) the duration of the animation from one slice to another. [53%, 30%]
    6. **Autoplay** Determines whether the transition between slices occurs automatically upon page load or at the selection of the visitor. [62%, 30%]
    7. **Autoplay Delay** You can set the amount of time between transitions when Autoplay is enabled. [72%, 30%]
    8. **Widget Style** (Supported Gantry Themes Only) Sets the widget style for the gallery. You can choose from Flush, Flush Bottom, or Flush Top. [79%, 30%]

1. **Gallery Layout**: The gallery can be laid out in a Grid, Slideshow, or Showcase pattern. This option more than any other impacts the way the gallery will appear within the widget block on the site. The options appearing below this are dynamically generated based on the gallery layout selected.

2. **Show Arrows**: This option determines if and/or when navigation arrows appear over the displayed image.

3. **Navigation Type**: If multiple navigation types are available, they will appear as an option in this list.

4. **Slices Animation Type**: This option determines what animation style (or styles) will be used to animate slices in the gallery.

5. **Animation Duration**: This field determines (in milliseconds) the duration of the animation from one slice to another.

6. **Autoplay**: Determines whether the transition between slices occurs automatically upon page load or at the selection of the visitor.

7. **Autoplay Delay**: You can set the amount of time between transitions when Autoplay is enabled.

8. **Widget Style**: (Supported Gantry Themes Only) Sets the widget style for the gallery. You can choose from Flush, Flush Bottom, or Flush Top.

#### Showcase

The Showcase layout works very similarly. You have the option to choose whether or not you wish to have arrows appear as a secondary navigation option, which direction the image will appear in the showcase in relation to the thumbnails, image padding, and animation options. These options remain the same for both fixed and responsive versions of the Showcase layout.

![][widget6]

:   1. **Gallery Layout** The gallery can be laid out in a Grid, Slideshow, or Showcase pattern. [10%, 30%]
    2. **Show Arrows** This option determines if and/or when navigation arrows appear over the displayed image. [17%, 30%]
    3. **Show Image on** This setting determines where within the Showcase the image will appear. [25%, 30%]
    4. **Image Padding** This option allows you to set the padding for the image (measured in pixels). [35%, 30%]
    5. **Fixed Height** Determines whether the slices will appear at a fixed or variable height. [42%, 30%]
    6. **Animate Height** This setting allows the user to choose between an animated or non-animated transition between slices of varying heights. [50%, 30%]
    7. **Slices Animation Type** Sets the animation type that occurs between slices. [58%, 30%]
    8. **Captions Animation Type** Sets the animation type that occurs during the transition of image captions. [66%, 30%]
    9. **Animation Duration** This field determines (in milliseconds) the duration of the animation from one slice to another. [74%, 30%]
    10. **Autoplay and Autoplay Delay** Determines whether the transition between slices occurs automatically upon page load or at the selection of the visitor. You can also set the amount of time between transitions when Autoplay is enabled. [82%, 30%]

1. **Gallery Layout**: The gallery can be laid out in a Grid, Slideshow, or Showcase pattern. This option more than any other impacts the way the gallery will appear within the widget block on the site. The options appearing below this are dynamically generated based on the gallery layout selected.

2. **Show Arrows**: This option determines if and/or when navigation arrows appear over the displayed image.

3. **Show Image on**: This setting determines where within the Showcase the image will appear.

4. **Image Padding**: This option allows you to set the padding for the image (measured in pixels).

5. **Fixed Height**: Determines whether the slices will appear at a fixed or variable height.

6. **Animate Height**: This setting allows the user to choose between an animated or non-animated transition between slices of varying heights.

7. **Slices Animation Type**: Sets the animation type that occurs between slices.

8. **Captions Animation Type**: Sets the animation type that occurs during the transition of image captions.

9. **Animation Duration**: This field determines (in milliseconds) the duration of the animation from one slice to another.

10. **Autoplay and Autoplay Delay**: Determines whether the transition between slices occurs automatically upon page load or at the selection of the visitor. You can also set the amount of time between transitions when Autoplay is enabled.

[rokgallery]: assets/rokgallery.jpeg
[rokgallery_component]: assets/rokgallery_component_1.jpeg
[rokgallery_component_configuration_options]: assets/rokgallery_component_configuration_opions.jpeg
[rokgallery_component_upload]: assets/rokgallery_component_upload.jpeg
[rokgallery_image_editor]: assets/rokgallery_image_editor.jpeg
[rokgallery_image_editor_2]: assets/rokgallery_image_editor_2.jpeg
[rokgallery_jobs_manager]: assets/rokgallery_jobs_manager.jpeg
[rokgallery_widget_1]: assets/rokgallery_widget_1.jpeg
[rokgallery_widget_advanced]: assets/rokgallery_widget_advanced_1.jpeg
[rokgallery_widget_basic_1]: assets/rokgallery_widget_basic_1.jpeg
[rokgallery_plugin_manager_1]: assets/rokgallery_plugin_manager_1.jpeg
[rokgallery_plugin_manager_2]: assets/rokgallery_plugin_manager_2.jpeg
[rokgallery_plugin_manager_3]: assets/rokgallery_plugin_manager_3.jpeg
[rokgallery_administrator]: assets/rokgallery_administrator.jpeg
[rokgallery_tags]: assets/rokgallery_tags.jpeg
[rokgallery_galleries_manager]: assets/rokgallery_galleries_manager.jpeg
[rokgallery_slice_editor]: assets/rokgallery_slice_editor.jpeg
[rokgallery_slice_editor_2]: assets/rokgallery_slice_editor_2.jpeg
[slideshow]: assets/rokgallery_slideshow.jpeg
[grid]: assets/rokgallery_grid.jpeg
[showcase]: assets/rokgallery_showcase.jpeg
[details]: assets/rokgallery_widget_2.jpeg
[featured]: assets/wp_rokgallery.jpeg
[rokgallery_download]: http://www.rockettheme.com/grav/plugins/rokgallery
[rokbox]: ../rokbox/
[admin1]: assets/wp_rokgallery_admin_1.jpeg
[admin2]: assets/wp_rokgallery_admin_2.jpeg
[admin3]: assets/wp_rokgallery_admin_3.jpeg
[admin4]: assets/wp_rokgallery_admin_4.jpeg
[install]: assets/wp_rokgallery_install.jpeg
[install2]: assets/wp_rokgallery_install_1.jpeg
[page1]: assets/wp_rokgallery_page_1.jpeg
[page2]: assets/wp_rokgallery_page_2.jpeg
[page3]: assets/wp_rokgallery_page_3.jpeg
[page4]: assets/wp_rokgallery_page_4.jpeg
[settings]: assets/wp_rokgallery_settings.jpeg
[widget1]: assets/wp_rokgallery_widget_1.jpeg
[widget2]: assets/wp_rokgallery_widget_2.jpeg
[widget3]: assets/wp_rokgallery_widget_3.jpeg
[widget4]: assets/wp_rokgallery_widget_4.jpeg
[widget5]: assets/wp_rokgallery_widget_5.jpeg
[widget6]: assets/wp_rokgallery_widget_6.jpeg
[widget7]: assets/wp_rokgallery_widget_7.jpeg
