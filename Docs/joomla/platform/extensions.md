---
title:  How Joomla Extensions Work
description: Everything you need to know to get started using Joomla extensions.
breadcrumb: /joomla:Joomla/!platform:Platform/!extensions.md:Extensions

---

What is an Extension?
-----

Extensions are anything you can add to Joomla to extend its default functionality. While Joomla has plenty of useful features out of the box, it is not uncommon for someone to want to add something extra to set their site apart. 

There are five different extension types in Joomla: Components, Modules, Plugins, Templates, and Languages. These extension types can all be installed in much the same way, though they can perform incredibly different jobs for your site. For example, a plugin and a template are very different things, though each of them extend your site's inherent function and form beyond what comes with the base Joomla package.

Joomla comes with a set of core extensions that make it easy to get up and running with your site. These include any provided templates, plugins, components, and languages needed to access your site directly after installation.

### Components

Components are large, often complex extensions that act as the main functional parts of a Joomla site. They are essentially miniature applications which run in conjunction with virtually every other part of the site. Components make up the main content body of the visitor and administrator side of Joomla. Components are the applications used to render the bulk of your site's content on both the frontend and backend.

They can also serve specific purposes such as adding ReCAPTCHA to forms, providing the site's template manager, and working to render the main body of a page.

### Modules

A module is a small extension that exists within a specific position in your template, typically around a component. A weather module, for example, will sit in a designated place on the page and relay the current weather to the visitor. Modules can perform a number of different tasks ranging from simple text boxes to complex login functions.

### Plugins

A plugin is generally invisible to a visitor and runs commands in response to a trigger event. These events can either be associated with Joomla's included set of trigger events (onSubmitContact, onSave, etc.) or any event defined by other extensions. These functions might change the way a site responds, or initiate a series of actions that carry out the request of the visitor.

### Templates

Templates determine the style and general layout properties of a site. Templates are created with multiple files and file types which can include PHP, CSS, or even media files. A template is basically the skin of your site, which is then filled out by any modules or components you assign to appear in designated spaces. 

Some templates offer more control to the user than others. For more information about templates and how they work within Joomla, visit the [Understanding Joomla Templates][joomla-templates] page in our documentation.

### Languages
Languages are an essential type of extension within Joomla. They enable the site manager to configure their Joomla installation to support a variety of different languages on either the visitor side, administrator side, or both. While language support exists within the core Joomla platform, you can install third-party language packs which can provide additional support to meet your individual needs.

How to Install an Extension
-----

Installing an extension is a fairly simple process. Generally, you'll receive a ZIP file from an extension developer which contains all the necessary files needed for it to function properly.

The most common method for installing an extension (featured in images below) involves uploading the package file to your site directly and letting Joomla install the extension for you. 

Alternatively, you can opt to install directly from a folder hosted on your Web server, or from an external URL hosted elsewhere. 

![][upload_extension1]

:   1. **Extensions** This will open the Extensions drop-down menu in Administrator. [12%, 72%, nw]
    2. **Extension Manager** This will open the Extension Manager where you can install any extension packages. [17%, 65%, ne]

The first step to installing an extension using the **Upload Package File** method is to access the Extensions manager. This can be done through **Administrator > Extensions > Extension Manager** from the top menu.

If you do not see the **Install** page (see the figure below), you can navigate to it by selecting Install from the sidebar on the left-hand side of the resulting page.

![][upload_extension2]

:   1. **Upload Package File** This is the most common way to install extensions. [30%, 28%, sw]
    2. **Install from Directory** Useful if you are installing an unzipped extension from a server directory. [30%, 43%, sw]
    3. **Install from URL** Useful if you need to install from an external Web server. [30%, 55%, sw]
    4. **Browse** This will open a file manager window you can use to point to the extension package file on your hard drive. [49%, 90%, sw]
    5. **Upload and Install** Click this button after you've selected the package file from point 4. [60%, 40%, ne]

From there, you'll be able to upload the package file directly by selecting *Browse* within the *Upload Package File* tab of the Extension Manager. 

Once a file manager window appears, you'll just need to navigate to the package file you wish to install and select *Open*. Once your package file is selected, you can hit the *Upload and Install* button to initiate the upload.

Joomla will automatically install any extensions within the package file. Once this is done, you'll be taken to a page which will list the extensions and status of each installation. Some package files may update existing extensions while others install something entirely new.

![][upload_extension3]

If any of these points are colored in red, or otherwise point out an error during the installation process, you'll need to take appropriate action to resolve the issue and try again.

Sometimes, a component will be too large, and your hosting provider won't allow a direct upload. In this case, you'll need to find an alternative method for getting the component into the file system. You can unpack the package file and upload individual files to a temporary folder you create within your server's file system. Once this is done, you can use the **Upload From Directory** option after entering the file path from the root directory of your server's filesystem. 

Another alternative is installing from an external URL using the **Install from URL** feature within the Extension Manager. This is a quick and easy way around some hosting restrictions, but also useful if someone gives you a link to a package file and you just want to install it without having to handle the file locally. Mobile users might find this option particularly useful while working on their site from the road.


How to Update an Extension
-----

Updating an extension is a pretty simple process. Extension developers frequently update their offerings to meet the needs of the latest Joomla version, fix any bugs that appear after the previous version released, or enhance the extension's functionality. 

To access the Update menu, navigate to **Administrator > Extensions > Extension Manager** and select **Update** in the sidebar on the left side of the Extension Manager page (point 1 in figure below).

![][update_extension1]

:   1. **Update** Navigate to the Update menu from within the Extension Manager. [40%, 11%, nw]
    2. Select the extension(s) you wish to update. [49%, 25%, ne]
    3. **Update** This button applies the discovered updates to selected extensions. [22%, 11%, nw]
    4. **Find Updates and Purge Cache* This will scan your extensions for available updates. Purge cache will refresh your update cache. [22%, 20%, nw]
    5. **Options** Allows you to set update permissions and cache cycle times. [22%, 41%, nw]

From there, you'll want to hit the **Find Updates** button (point 4) to get a complete list of extensions.

Once a list of available updates appears, you can select them (point 2) and click **Update** (point 3).

This should automatically update the selected extensions.

If you have any extensions that are not compatible with the automatic update menu within Joomla, you'll want to consult the developer's site for instructions on how to manually update them.

[joomla-templates]: templates.md
[upload_extension1]: assets/upload_extension1.png
[upload_extension2]: assets/upload_extension2.png
[upload_extension3]: assets/upload_extension3.png
[update_extension1]: assets/update_extension1.png