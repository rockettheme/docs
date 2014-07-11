---
title: How to Create a Multilingual Site in Joomla
description: How to create a multilingual site in Joomla 2.5 and 3.x.
breadcrumb: /joomla:Joomla/!basic:Basic Tutorials/!how_to_create_a_multilingual_site:How to Create a Multilingual Site

---

Introduction
---------

Multilingual support in websites opens them up to a considerably larger audience than a single-language site might be able to. Developing a site with multilingual support takes a little know-how, and we have put together this guide to help you get through it.

Everything written here can be applied to any of the templates provided by RocketTheme.

Prerequisites
-----

* Joomla 2.5.7+, Joomla 3.x
* RocketTheme Template
* RokNavMenu Extension

>> NOTE: This process is much easier when it's being done on a new website. You can accomplish this on an existing site using the same steps, but you may need to work a lot harder during menu configuration to achieve the desired result.

Setup
-----

## Step 1: Install Additional Languages

![][joomla_25_1]

First thing that you should do is to install additional languages that will be used on the web site. You can do this by navigating to **Extensions Manager -> Install Languages**, selecting the language(s) you wish to install, and clicking the yellow **Install** button in the upper-right area of the page.

When you installed all the required languages go to **Language Manager** which can be reached by going to **Administrator -> Extensions -> Language Manager**. On the **Installed - Site** tab, you will see the list of all installed languages on the web site. Now, we just need to add content languages.

## Step 2: Create New Content Languages

![][joomla_25_2]

You can do this by selecting the **Content** tab and then selecting **New**. This will take you to a page that enables you to set up a new content language for your site.
 
![][joomla_25_3]

Fill out the required information in this page. This information includes:

* **Title**: The Name of the language as it will appear on the site.
* **Title Native**: Title in its native language.
* **URL Language Code**: The language code is appended to the site URL. (Example: http://mysite.com/sp/)
* **Image Prefix**: Prefix of the image file for this language when using the *Use image flags* Language Switcher basic option. (Example: enus for enus.gif)
* **Language Tag**: Enter the exact prefix used for the language installed (or to be installed). (Example: en-GB)

Once you have filled in this information, click **Save and Close**. This will take you back to the **Content Languages** page where you will see your new language(s) listed along with any pre-existing content languages.

## Step 3: Configure and Enable the Language Filter Plugin
 
![][joomla_25_5]

The next step requires you to navigate to **Extensions -> Plug-in Manager** in order to configure Joomla multilingual plugins. The plugin you need to find here is **System - Language Filter**. 

Click the plugin to access the configuration page. Here, you can set the **Basic Options** as you see fit. Here are some example settings which should work in most cases.

| Option                              | Setting     |
| :----------                         | :---------- |
| Language Selection for New Visitors | Browser     |
| Automatic Language Change           | Yes         |
| Menu Associations                   | Yes         |
| Remove URL Language Code            | Yes         |
| Add Alternate Meta Tags             | No          |

Once this is configured, activate the plugin by switching the **Status** to **Enabled**.

## Step 4: Create New Content Categories for Each Language

![][joomla_25_6]

The next step is to create a new category for each language you wish to use. You can do this by navigating to **Administrator -> Content -> Category Manager -> Create New Category**.

Each category should have a language assigned. You can title this category after the name of the language you intend to use. Once you have done this, you can click **Save and Close**.

![][joomla_25_7]

You can then create content categories and assign their **Parent** category to the base category you have created for the language. For example, you can create a category called *Blog* and assign it the **English (USA)** category as a parent.

## Step 5: Enable Unicode URL Aliases

![][joomla_25_8]

The next thing you may want to do is to navigate to the **Global Configuration** page and access **SEO Settings**. This area of the administrator can be accessed by navigating to **Administrator -> Site -> Global Configuration**. 

You will likely want to turn on Unicode URL aliases, especially if you have special characters in one of the selected language, for example letter 'čćšđž' in the Croatian language.
 
## Step 6: Create a Menu for Each Language

In order for everything to work and look correctly, you will want to add menus that belongs to each language in **Menu Manager**. This step will enable each user to not only access a menu that is available in their preferred language, but also to filter the site experience itself by content language.

![][joomla_25_9]

You can add a new menu by navigating to **Administrator -> Menus -> Menu Manager -> Add New Menu**. 

![][joomla_25_10]

Once you have created the menu, you can then go into that menu's **Menu Manager** page, filter menu items by one of the language-related menus, and select **New**.

![][joomla_25_11]

When you create the new menu item, you can do so as you would normally. The only additional steps required is that you set the **Menu Location** and **Language** to your desired language-specific menu and language. You may also want to create a home page menu item for that individual language, as this will make each visitor's landing page appear in their native language.

One thing that you need to set (if you want specific article for example to change depending on selected language) is Menu Item Associations section's parameters.

When you add all menus and you define **Default Page** parameter for each language you should have situation similar to the following:

![][joomla_25_12]

## Step 7: Create a Template Override for Each Language
 
At the end, you have to assign template copy for each language installed. That is necessary so you can load different menus, depending on the selected language. You can do this by going to **Administrator -> Extensions -> Template Manager**, selecting the template you have as default, and selecting **Duplicate**. 

![][joomla_25_13]

This will create a duplicate of your template, which you can modify to include the language-specific menu and set assign a language to the override.
 
To do this, you will want to set the **Default** language to the language you wish to have this style assigned. You can do this in the **Overview** area of the **Template Settings**.

![][joomla_25_14]

Next, you will want to change the main menu to the one you created for the language. For example, if this template style is assigned to English (USA), then you will want to select the English (USA) menu.

## Step 8: Create a Language Selector Module

This step is useful if you want to give your visitors the option to switch between languages as they please. You can do this by creating a **Language Selector** module and publishing it on the page.

You can do this as you would create any other module. By navigating to **Administrator -> Extensions -> Module Manager** and selecting **New**. Choose **Language Switcher** as the **Module Type** and configure it as you prefer.
 
![][joomla_25_15]

Once this is done, you should see both the language selector module and the language-specific menu appear as expected. Your visitors can switch between languages by clicking its associated flag.

[joomla_25_1]: assets/multi_1.jpeg
[joomla_25_2]: assets/multi_2.jpeg
[joomla_25_3]: assets/multi_3.jpeg
[joomla_25_4]: assets/multi_4.jpg
[joomla_25_5]: assets/multi_5.jpeg
[joomla_25_6]: assets/multi_6.jpeg
[joomla_25_7]: assets/multi_7.jpeg
[joomla_25_8]: assets/multi_8.jpeg
[joomla_25_9]: assets/multi_9.jpeg
[joomla_25_10]: assets/multi_10.jpeg
[joomla_25_11]: assets/multi_11.jpeg
[joomla_25_12]: assets/multi_12.jpg
[joomla_25_13]: assets/multi_13.jpeg
[joomla_25_14]: assets/multi_14.jpeg
[joomla_25_15]: assets/multi_15.jpeg
