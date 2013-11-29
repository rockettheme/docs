---
title: RokSprocket: Layout Modes
description: Your Guide to RokSprocket Layout Modes for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!roksprocket:RokSprocket

---

Introduction
------------

RokSprocket has multiple layout modes to display your content including: [Features][features_link], [Tabs][tabs_link], [Lists][lists_link], [Mosaic][mosaic_link], [Strips][strips_link], and [Headlines][headlines_link]. This guide will give you an overview of what these modes are, and how to configure them using the administrator interface.

![][roksprocket_module_1]

:   1. **RokSprocket Module** This option within the Module Manager's **New Module** type list will initiate the creation of a RokSprocket Module. [37%, 8%, se]

To start, all of the layout modes are accessible using a single module type. By selecting **RokSprocket Module** from the module type list, you'll initiate the creation of a RokSprocket Module, which can be configured to fit any of the layout modes listed below. Once you have created the new module, you'll be taken to the module manager for `mod_roksprocket` where you can configure its individual settings. 

Below, you'll see each layout mode listed along with the settings which are available for them. Not all of the modes have the same set of controls as each is intended for an entirely different look and/or purpose.

You can jump to a specific layout mode using the menu in the sidebar, or clicking the mode's name below:

* [Features][features_link]
* [Tabs][tabs_link]
* [Lists][lists_link]
* [Mosaic][mosaic_link]
* [Strips][strips_link]
* [Headlines][headlines_link]

Content Providers
-----

![][content]

RokSprocket has the ability to pull content from a number of content providers that work within Joomla. Most site administrators will use Joomla as the content provider for RokSprocket as it pulls articles from your primary Joomla install and arranges them to meet your needs. 

Alternatively, RokSprocket supports the following content providers:

* [K2][K2]
* [ZOO][zoo]
* Simple
* [ContentBuilder][contentbuilder]
* [EasyBlog][easyblog]
* [Seblod][seblod]
* [FieldsAttach][fieldsattach] 

### Using the 'Simple' Content Provider
With the introduction of RokSprocket 2, you can use another content provider named **Simple** which allows you to manually configure a RokSprocket module without having to reference any articles hosted on your site. In fact, the **Simple** content provider option gives you complete control over every aspect of your RokSprocket module's line items.

![][simple]

:   1. **Rename Item** The pencil icon gives you the ability to rename an item in your module. [21%, 13%, sw]
    2. **Item Settings** The tab label, icon, link, and description all need to be entered manually as this information is not automatically pulled from a source. [25%, 50%, sw]
    3. **Content Provider** Selecting the **Simple** content provider allows you manual control over the module and its content. [20%, 80%, sw]
    4. **Add New Item** This button adds a new blank item to the module. [35%, 81%, sw]
    5. **Delete** The circular X icon gives you the option to delete a line item. This can not be undone, and you'll need to click the icon twice to lock in the change. [21%, 33%, sw]

1. **Rename Item**: The pencil icon gives you the ability to rename an item in your module.

2. **Item Settings**: The tab label, icon, link, and description all need to be entered manually as this information is not automatically pulled from a source.

3. **Content Provider**: Selecting the **Simple** content provider allows you manual control over the module and its content.

4. **Add New Item**: This button adds a new blank item to the module.

5. **Delete**: The circular X icon gives you the option to delete a line item. This can not be undone, and you'll need to click the icon twice to lock in the change.

When using ‘Simple’ as the content provider, you can set ordering to random and/or manual. Since items are not pulled from an existing source, you can arrange them to meet your individual preferences with the option to allow visitors to activate random sorting. This is done to give you maximum control over how content is presented so the module appears the way you want it to every time a visitor loads the page.

[features_link]: features_mode.md
[lists_link]: lists_mode.md
[tabs_link]: tabs_mode.md
[mosaic_link]: mosaic_mode.md
[headlines_link]: headlines_mode.md
[strips_link]: strips_mode.md
[roksprocket_module_1]: assets/roksprocket_module_1.jpeg
[strips_demo]: assets/strips_demo.jpeg
[fieldsattach]: http://fieldsattach.com/
[seblod]: http://www.seblod.com/
[easyblog]: http://stackideas.com/easyblog.html
[contentbuilder]: http://crosstec.de/en/extensions/joomla-cck-download.html
[zoo]: http://extensions.joomla.org/extensions/authoring-a-content/content-construction/12479
[K2]: http://getk2.org/index.php
[simple]: assets/roksprocket_simple.jpg
[content]: assets/roksprocket_content.jpg