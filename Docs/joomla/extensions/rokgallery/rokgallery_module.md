---
title: RokGallery: Module Guide
description: Your Guide to Setting Up and Using RokGallery Modules for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/rokgallery:RokGallery

---

Creating a Module
-----
Creating a RokGallery module is a fairly straightforward process. You Would create it as you would any other module by navigating to **Administrator -> Extensions -> Module Manager** and selecting the green **New** button in the upper-left region of the page.

![][rokgallery_module_1]

Once there, you'll be asked which type of module you wish to create. RokGallery has its own module type listed as **RokGallery Module**.  Simply select that from the list (pictured above) and you can begin initial configuration.

### Module Configuration

#### Details
![][details]

:   1. **Title** This is the title of your module. [24%, 44%, sw]
    2. **Show Title** Determines whether the title of the module will appear for visitors or remain hidden. [30%, 34%, sw]
    3. **Position** Sets the publishing status for the module. [36%, 48%, sw]
    4. **Status** Determines the publishing status of the module. [46%, 23%, se]
    5. **Access** Sets the access level for the module. [53%, 43%, sw]
    6. **Ordering** Sets the ordering for the module. [59%, 23%, se]
    7. **Start Publishing** Determines when the module should be published on your site. [65%, 42%, sw]
    8. **Finish Publishing** Sets an end date/time for your module to appear on the frontend. [72%, 23%, se]
    9. **Language** Allows you to pick a language for your module. This list is determined by the supported languages installed on your Joomla site. [79%, 43%, sw]
    10. **Note** A place to jot down a note which appears in the module list on the backend. [85%, 23%, se]

1. The **Title** field gives you the ability to set a title for the module itself. Every module has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look.

2. The **Show Title** option gives you the ability to determine whether or not the title of the module will appear with the module on the frontend.

3. The **Position** option allows you to determine where in your layout the module will appear.

4. **Status** option allows you to determine the current publishing status of the module. An unpublished module will still appear on the backend for administrators, but will not appear on the live site.

5. The **Access** option gives you the ability to determine which user group will be able to see the module on the frontend. Someone logged in as a registered user may be able to see a module set at that level while random visitors do not see it.

6. **Ordering** gives you the ability to set the ordering for the module. 

7. **Start Publishing** determines the start date/time when the module should be published on your site. 

8. You can use **Finish Publishing** to set an end date/time for your module to appear on the frontend.

9. **Language** allows you to pick a language for your module. This list is determined by the supported languages installed on your Joomla site. 

10. You can use the **Note** field to jot down a note which appears in the module list on the backend.

#### Basic
![][rokgallery_module_basic_1]

:   1. **Gallery** This option allows you to assign a RokGallery tag gallery to the module. Images with tags matching that of this gallery are displayed with the gallery's image preferences. [30%, 72%, sw]
    2. **Link Type** This option sets the action resulting from clicking the image in the gallery. You can set it to work with RokBox or RokBox2, a link determined by the slice settings of the image, the full image, or do nothing at all. [34%, 32%, se]
    3. **Default Linked Item** If you've selected **Link in Slice** and you haven't set a link within the slice, this will be the link the gallery defaults to. [39%, 60%, sw]
    4. **Show Title** This option sets whether or not the title of a slice is shown in the gallery. [44%, 32%, se]
    5. **Show Caption** This option sets whether or not the caption of a slice appears in the gallery. [49%, 60%, sw]
    6. **Sort By** This option sets the default sorting order for images in the gallery. [53%, 32%, se]
    7. **Sort Direction** You can choose to have items sorted in ascending or descending order based on the **Sort By** setting. [58%, 60%, sw]
    8. **Slice Limit** You can set the limit of slices which appear in the gallery. [63%, 32%, se]
    9. **Gallery Style** This option allows you to choose from a light or dark gallery style, affecting the look of the gallery within the module. [67%, 60%, sw]
    10. **Gallery Layout** Galleries can be laid out in a Grid, Slideshow, or Showcase pattern. [72%, 32%, se]

1. **Gallery**: This option allows you to assign a RokGallery tag gallery to the module. Images with tags matching that of this gallery are displayed with the gallery's image preferences.

2. **Link Type**: This option sets the action resulting from clicking the image in the gallery. You can set it to work with RokBox or RokBox2, a link determined by the slice settings of the image, the full image, or do nothing at all.

3. **Default Linked Item**: If you've selected **Link in Slice** and you haven't set a link within the slice, this will be the link the gallery defaults to.

4. **Show Title**: This option sets whether or not the title of a slice is shown in the gallery.

5. **Show Caption**: This option sets whether or not the caption of a slice appears in the gallery.

6. **Sort By**: This option sets the default sorting order for images in the gallery.

7. **Sort Direction**: You can choose to have items sorted in ascending or descending order based on the **Sort By** setting.

8. **Slice Limit**: You can set the limit of slices which appear in the gallery.

9. **Gallery Style**: This option allows you to choose from a light or dark gallery style, affecting the look of the gallery within the module.

10. **Gallery Layout**: Galleries can be laid out in a Grid, Slideshow, or Showcase pattern.

Each layout option comes with one or more specific settings. These settings appear at the bottom of the **Basic** module options, depending on which **Gallery Layout** you've selected.

![][grid]

For example, the **Grid** layout allows you the option to choose how many columns appear in your grid, and to select a background image (if your template allows). 

![][slideshow]

The Slideshow layout allows you to determine if you wish to show arrows on either side of the image as well as set your navigation and animation types. You can also tell it whether or not you wish slideshows to autoplay, and with what delay between images.

![][showcase]

The Showcase layout works very similarly. You have the option to choose whether or not you wish to have arrows appear as a secondary navigation option, which direction the image will appear in the showcase in relation to the thumbnails, image padding, and animation options. These options remain the same for both fixed and responsive versions of the Showcase layout.

#### Advanced
![][rokgallery_module_advanced]

:   1. **Module Class Suffix** This is a suffix applied to the CSS class of the module. This allows for individual module styling. [40%, 60%, sw]
    2. **Caching** Selects whether or not to cache the content of this module. [48%, 60%, sw]
    3. **Cache Time** This option sets the time between module recaching. [54%, 33%, se]
    4. **Module Tag** This sets the HTML tag for the module. [62%, 60%, sw]
    5. **Bootstrap Size** This option specifies how many columns the module will use. [68%, 33%, se]
    6. **Header Tag** This field sets the HTML tag for the module header/title. [73%, 60%, sw]
    7. **Header Class** This field sets the CSS class for the module header/title. [79%, 33%, se]
    8. **Module Style** This option allows for an override of the template style for its position. [84%, 60%, sw]

1. **Module Class Suffix**: A suffix applied to the CSS class of the module. This allows for individual module styling.

2. **Caching**: Selects whether or not to cache the content of this module.

3. **Cache Time**: Sets the time between module recaching.

4. **Module Tag**: Sets the HTML tag for the module.

5. **Bootstrap Size**: Specifies how many columns the module will use.

6. **Header Tag**: Sets the HTML tag for the module header/title.

7. **Header Class**: Sets the CSS class for the module header/title.

8. **Module Style**: Allows for an override of the template style for its position.

[rokgallery]: assets/rokgallery.jpeg
[rokgallery_component]: assets/rokgallery_component_1.jpeg
[rokgallery_component_configuration_options]: assets/rokgallery_component_configuration_opions.jpeg
[rokgallery_component_upload]: assets/rokgallery_component_upload.jpeg
[rokgallery_image_editor]: assets/rokgallery_image_editor.jpeg
[rokgallery_image_editor_2]: assets/rokgallery_image_editor_2.jpeg
[rokgallery_jobs_manager]: assets/rokgallery_jobs_manager.jpeg
[rokgallery_module_1]: assets/rokgallery_module_1.jpeg
[rokgallery_module_advanced]: assets/rokgallery_module_advanced_1.jpeg
[rokgallery_module_basic_1]: assets/rokgallery_module_basic_1.jpeg
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
[details]: assets/rokgallery_module_2.jpeg
