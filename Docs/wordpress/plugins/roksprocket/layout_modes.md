---
title: RokSprocket: Layout Modes
description: Your Guide to RokSprocket Layout Modes for WordPress
breadcrumb: /wordpress:WordPress/!plugins:Plugins/roksprocket:RokSprocket

---

Introduction
------------
RokSprocket has multiple layout modes to display your content including: [Features][features_link], [Tabs][tabs_link], [Lists][lists_link], [Mosaic][mosaic_link], [Grids][grids_link], [Quotes][quotes_link], [Sliders][sliders_link], [Tables][tables_link], [Strips][strips_link], and [Headlines][headlines_link]. This guide will give you an overview of what these modes are, and how to configure them using the RokSprocket Admin interface.

![][admin1]

To start, you can configure a new widget with your layout mode of choice by heading to the **RokSprocket Admin** tool located in the sidebar of the administrative area of WordPress. This page gives you the ability to create and manage widgets prior to placing them in the Widgets Manager.

Think of this page as a list of presets you can apply to one or more different widgets. Each preset can be set with a specific layout type.

Below, you will see each layout mode listed along with the settings which are available for them. Not all of the modes have the same set of controls as each is intended for an entirely different look and/or purpose.

![][content]

:   1. **Title** You need to assign a title to the widget in order to continue past the first setup page. [15%, 13%, se]
    2. **Layout** The layout determines how the widget will appear on the frontend. [30%, 39%, se]
    3. **Content Provider** This option allows you select from any available content providers on your Joomla site. [58%, 35%, se]
    4. **Continue** Selecting this will create the widget and take you to the next step in the setup process. Once this is clicked, the widget's content provider and layout can not be changed. [84%, 46%, se]

Once you have selected to create a new RokSprocket widget, you will be taken to a page where you can pick a **Content Provider** and a **Layout**. Once you have done this, and given the widget a **Title** you can click **Continue** to begin refining the widget on the next page.

You can jump to a specific layout mode using the menu in the sidebar, or clicking the mode's name below:

* [Features][features_link]
* [Tabs][tabs_link]
* [Lists][lists_link]
* [Mosaic][mosaic_link]
* [Strips][strips_link]
* [Headlines][headlines_link]
* [Grids][grids_link]
* [Quotes][quotes_link]
* [Sliders][sliders_link]
* [Tables][tables_link]

Content Providers
-----

Content providers determine where the content is pulled from to create the body of your RokSprocket widget. Images, links, descriptions, and titles can be pulled directly from these content providers.

RokSprocket has the ability to pull content from a number of content providers that work within WordPress. Most site administrators will use WordPress as the content provider for RokSprocket as it pulls posts from your primary WordPress install and arranges them to meet your needs. 

Alternatively, RokSprocket supports the following content providers:

* [CFS][cfs]
* [CPT][cpt]
* [Types][types]
* Simple
* PostTypes

### Using the 'Simple' Content Provider
With the introduction of RokSprocket 2, you can use another content provider named **Simple** which allows you to manually configure a RokSprocket widget without having to reference any posts hosted on your site. In fact, the **Simple** content provider option gives you complete control over every aspect of your RokSprocket widget's line items.

![][simple]

:   1. **Rename Item** The pencil icon gives you the ability to rename an item in your module. [35%, 15%, sw]
    2. **Item Settings** The tab label, icon, link, and description all need to be entered manually as this information is not automatically pulled from a source. [35%, 50%, sw]
    3. **Add New Item** This button adds a new blank item to the module. [35%, 82%, sw]
    4. **Delete** The circular X icon gives you the option to delete a line item. This can not be undone, and you will need to click the icon twice to lock in the change. [35%, 33%, sw]

1. **Rename Item**: The pencil icon gives you the ability to rename an item in your module.

2. **Item Settings**: The tab label, icon, link, and description all need to be entered manually as this information is not automatically pulled from a source.

3. **Add New Item**: This button adds a new blank item to the module.

4. **Delete**: The circular X icon gives you the option to delete a line item. This can not be undone, and you will need to click the icon twice to lock in the change.

When using ‘Simple’ as the content provider, you can set ordering to random and/or manual. Since items are not pulled from an existing source, you can arrange them to meet your individual preferences with the option to allow visitors to activate random sorting. This is done to give you maximum control over how content is presented so the widget appears the way you want it to every time a visitor loads the page.

[features_link]: features_mode.md
[lists_link]: lists_mode.md
[tabs_link]: tabs_mode.md
[mosaic_link]: mosaic_mode.md
[headlines_link]: headlines_mode.md
[strips_link]: strips_mode.md
[grids_link]: grids_mode.md
[sliders_link]: sliders_mode.md
[tables_link]: tables_mode.md
[quotes_link]: quotes_mode.md
[roksprocket_widget_1]: assets/roksprocket_widget_1.png
[strips_demo]: assets/strips_demo.png
[admin1]: assets/wp_roksprocket_admin_1.png
[features1]: assets/wp_roksprocket_features_1.png
[headlines1]: assets/wp_roksprocket_headlines_1.png
[lists1]: assets/wp_roksprocket_lists_1.png
[mosaic1]: assets/wp_roksprocket_mosaic_1.png
[tabs1]: assets/wp_roksprocket_tabs_1.png
[widget1]: assets/wp_roksprocket_widget_1.png
[widget2]: assets/wp_roksprocket_widget_2.png
[simple]: assets/roksprocket_simple.jpg
[content]: assets/roksprocket_content.jpg
[cfs]: http://wordpress.org/plugins/custom-field-suite/
[cpt]: http://wordpress.org/plugins/custom-post-type-ui/
[types]: http://wordpress.org/plugins/types/