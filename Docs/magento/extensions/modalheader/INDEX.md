---
title: ModalHeader
description: Your Guide to the ModalHeader Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!modalheader:ModalHeader

---

Introduction
-----

![][demo]

The ModalHeader module adds in some extra functionality to the header section of a Magento store. It connects the "Log In" link to a modal login form, and adds a text-resizer. It adds a modal shopping cart viewer, and adds styling to the search form and breadcrumbs. The modal window animation parameters can be tweaked from the admin config.

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Enable Modal Header** Enables or disables the modal header module. [15%, 38%, se]
	2. **Enable Custom Form Elements** Allows you to enable or disable the present of form elements in the modal header. [20%, 38%, se]
	3. **Enable Custom Breadcrumbs** Enables or disables the custom breadcrumbs element. [24%, 38%, se]
	4. **Build Title Spans** Allows you to build spans around the first word of titles for special styling. [29%, 38%, se]
	5. **Classes to Build Spans for** Classes you want to have spans built for. [35%, 38%, se]
	6. **Disable Modal Log In** Disables just the modal log in. [70%, 38%, se]
	7. **Disable Modal Cart** Disables just the modal cart. [75%, 38%, se]
	8. **Disable Text Resizer** Turns off the text resizer element in the header. [80%, 38%, se]
	9. **Disable Date** Disables the date display in the header. [85%, 38%, se]

1. **Enable Modal Header**: Enables or disables the modal header module.

2. **Enable Custom Form Elements**: Allows you to enable or disable the present of form elements in the modal header.

3. **Enable Custom Breadcrumbs**: Enables or disables the custom breadcrumbs element.

4. **Build Title Spans**: Allows you to build spans around the first word of titles for special styling.

5. **Classes to Build Spans for**: Classes you want to have spans built for.

6. **Disable Modal Log In**: Disables just the modal log in.

7. **Disable Modal Cart**: Disables just the modal cart.

8. **Disable Text Resizer**: Turns off the text resizer element in the header.

9. **Disable Date**: Disables the date display in the header.

![][extension2]

:	1. **Additional jQuery Scripts** This field enables you to add additional jQuery scripts before the body end. Use $j instead of $j (for noConflict mode). [15%, 39%, se]
	2. **Additional CSS** Allows you to add any additional CSS elements. [52%, 39%, se]

1. **Additional jQuery Scripts**: This field enables you to add additional jQuery scripts before the body end. *Use $j instead of $j (for noConflict mode)*.
2. **Additional CSS**: Allows you to add any additional CSS elements.

![][extension4]

:	1. **Animation Settings** This field contains jQuery variables for modal window animations. Supported variables are listed below. [25%, 39%, se]

1. **Animation Settings**: This field contains jQuery variables for modal window animations. Supported variables are listed below.

**Option Examples**

* **overlayopacity**: 0.2 ⇒ Sets the opacity of the overlay window.
* **overlayinspeed**: 300 ⇒ Sets the speed in which the overlay will appear.
* **modalpreposition**: {"top":"43%"} ⇒ Sets the position of the modal window before it is visible.
* **modalpauseb4entry**: 200 ⇒ Sets the pause before the modal window comes into view.
* **modalentryanimation**: {"top": "50%", "opacity": "1"} ⇒ Defines the animation for the modal window coming into view.
* **modalentryspeed**: 550 ⇒ Sets the speed for the modal window coming into view.
* **modalexitanimation**: {"top": "55%", "opacity": "0"} ⇒ Defines the animation for the modal window going out of view.
* **modalexitspeed**: 350 ⇒ Sets the speed for the modal window going out of view.
* **pauseb4overlayfadeout**: 500 ⇒ Sets the pause before the overlay fades out, after the modal window is hidden.
* **overlayoutspeed**: 200 ⇒ Sets the speed in which the overlay will disappear.

![][extension3]

:	1. **Add Classes for PIE** This field allows you to enter a comma separated list of IDs/classes to apply PIE.js to. [12%, 38%, se]
	2. **Redirect IE6/7 Visitors** Enables IE6/7 redirection to the **Unsupported Browser** warning page. [42%, 38%, se]
	3. **Load IE6/7 Helper Files** Enables or disables helper files and CSS/JavaScript fixes for sites that wish to continue IE 6/7 support. [52%, 38%, se]
	4. **Add Classes for IE6 PNG Fix** This field allows you to enter a comma separated list of IDs/classes to apply the PNG fix to. [60%, 38%, se]

1. **Add Classes for PIE**: This field allows you to enter a comma separated list of IDs/classes to apply PIE.js to.

2. **Redirect IE6/7 Visitors**: Enables IE6/7 redirection to the **Unsupported Browser** warning page.

3. **Load IE6/7 Helper Files**: Enables or disables helper files and CSS/JavaScript fixes for sites that wish to continue IE 6/7 support.

4. **Add Classes for IE6 PNG Fix**: This field allows you to enter a comma separated list of IDs/classes to apply the PNG fix to.

How to Install
-----

You can download a zip package from the RokMage Extensions [downloads page][download].

Once you've downloaded and unzipped the extension package, you'll notice that the folder structure for the files has been included. This means you can simply copy the files/folders over to the corresponding folder of your Magento site, if developing locally. 

If you are developing on a remote server, you can simply upload the **app** and **skin** folders to the Magento install on your server.

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
[demo]: assets/demo_modalheader.jpeg