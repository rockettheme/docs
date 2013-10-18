---
title: CmsCallouts
description: Your Guide to the CmsCallouts Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!cmscallouts:CmsCallouts

---

Introduction
-----

![][demo]

The CmsCallouts module overrides the default left and right 'callouts' that appear in the side bars. The default callouts require editing of layout XML files in order to add content to them. With this module, you can add content straight from the admin.

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Enable Left CMS Callout** Activates or deactivates the left CMS callout. [40%, 28%, se]
	2. **Enable Right CMS Callout** Activates or deactivates the right CMS callout. [60%, 28%, ne]

1. **Enable Category View**: Sets whether you wish to enable or disable the Category View extension.

2. **Use 2 Column Layout**: Allows you to choose between the default column layout or a two column layout.

![][extension2]

:	1. **Left Callout Title** This title will appear at the top of the left callout module. [14%, 28%, se]
	2. **Left Callout Text** This text appears under the title in the left callout module. [20%, 28%, se]
	3. **Include CMS Block** Allows you to include a CMS block in the left callout module. [45%, 28%, se]
	4. **Right Callout Title** This title will appear at the top of the right callout module. [52%, 28%, se]
	5. **Right Callout Text** This text appears under the title in the right callout module. [58%, 28%, se]
	6. **Include CMS Block** Allows you to include a CMS block in the right callout module. [83%, 28%, se]

1. **Left Callout Title** This title will appear at the top of the left callout module.

2. **Left Callout Text** This text appears under the title in the left callout module.

3. **Include CMS Block** Allows you to include a CMS block in the left callout module.

4. **Right Callout Title** This title will appear at the top of the right callout module.

5. **Right Callout Text** This text appears under the title in the right callout module.

6. **Include CMS Block** Allows you to include a CMS block in the right callout module.

How to Install
-----

You can download a zip package from the RokMage Extensions [downloads page][download].

Once you've downloaded and unzipped the extension package, you'll notice that the folder structure for the files has been included. This means you can simply copy the files/folders over to the corresponding folder of your Magento site, if developing locally. 

If you're developing on a remote server, you can simply upload the **app** and **skin** folders to the Magento install on your server.

![][installation]

:	1. This can also be the name of your template package. [22%, 55%, sw]
	2. This can also be the name of your template package. [77%, 50%, sw]

Magento uses a hierarchy system. Adding the files in the **base** folder will work with any theme package. You can also elect to add the layout, template, and skin files to your theme package folder (instead of base) in order to have the extension apply only to that theme. Anything placed in the theme package folder will override what exists in the **base** folder. Anything in the **base** folder is accepted as default.

>> If you download a RocketTheme Magento template, the extension files will all be included in the theme package folder, not the base folder.

[installation]: assets/installation.jpg
[download]: http://www.rockettheme.com/magento-downloads/1807-extension
[extension1]: assets/extension_1.jpeg
[extension2]: assets/extension_2.jpeg
[extension3]: assets/extension_3.jpeg
[extension4]: assets/extension_4.jpeg
[demo]: assets/demo_cmscallouts.jpeg