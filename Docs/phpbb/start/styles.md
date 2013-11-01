---
title: How to Install a RocketTheme phpBB Style
description: This document will guide you through the process of installing a new phpBB3 style.
breadcrumb: /phpbb:phpBB/!start:Getting Started/

---

Introduction
-----

In phpBB3, **styles** are made up of three components: **templates**, **themes**, and **imagesets**. These components work together to create a unique user experience for members of your board. A style can be altered after installation, and you can freely switch between styles in the backend of your phpBB site.

Installing a new style in phpBB requires you to upload files to your site. We recommend using [FileZilla][filezilla], though any dedicated or Web-based file transfer solution that allows you to transfer files to your server should work.

Secondly, you'll want to familiarize yourself with the **Administration Control Panel (ACP)** in order to complete installation once uploading is complete. You can access the **Styles** area of the ACP by navigating to **Admin -> Styles** in the backend. You can typically find a direct link to the ACP by navigating to the very bottom of the front page of your phpBB installation and clicking **Administration Control Panel**. 

### Step 1: Download the Style

Downloading a RocketTheme phpBB style is pretty simple. All you need to do is navigate to the desired style of your choice on RocketTheme.com and click the **Download** link. From here, you'll be taken to a page with three primary download options, along with the image sources you can use as a reference to customize images used in the style. These packages include:

* **Style**: This is a style package that includes just the files needed to install the style on your existing site. Only choose this option if you  already have the latest RokBB installed. It's most commonly selected by users that are switching from one RocketTheme phpBB style to another.
* **Bundle**: This package includes the style and the latest RokBB version. It's the preferred download option if you are installing a RocketTheme style for the first time.
* **RocketLauncher**: This package contains a full latest version of phpBB3 install, as well as the style, latest RokBB, and demo sample content allowing you to easily deploy your chosen forum with a few clicks. This should only be used if you are creating a new phpBB install. Existing sites should be created using either the **Style** or **Bundle** options.

>> NOTE: We always recommend installing a RocketLauncher first to trial and understand the style more efficiently. It contains sample content and initial configuration. It's ready for further customizations. It must be installed as new, and not over an existing phpBB install.

### Step 2: Unzip and Upload

Once you've downloaded your selected package, you can unzip it locally or choose to do so after the initial upload. In the case of the **Bundle** package, the unzipped package will include two additional zip files. One includes the style itself, and the other RokBB.

Uploading the new Style involves moving the folder containing the style into the **Style** folder within your main phpBB directory. For example, if you are installing the Acacia style, you'll place the **Acacia** folder (and its associated contents) into the **pbpBB -> Styles** directory where the phpBB directory is whichever directory on your server that acts as the root folder for your phpBB installation.

>> You can upload all the files via FTP, or use cPanel or SSH to upload the zip and unzip directly onto the server. Inquire with your hosting provider.

### Step 3: Activation

![][style2]

:	1. **Install** Select this link to initiate the installation process for the new phpBB style. [53%, 75%, se]

Once your style is uploaded, you can activate it and set it to default by accessing the **Administration Control Panel (ACP)**. From there, navigate to the **Styles** tab and select **Install** next to the style you've just uploaded. If your style does not appear in this list, it may have been placed in the wrong folder.

![][style3]

:	1. **Active** Select this option to activate the new style. [68%, 47%, se]
	2. **Make Default Style** If this option is set to **Yes**, the new style will be set as your default. [73%, 52%, se]

After you've set these options, simply select **Submit** to complete installation.

Installing Administrative Modules
-----

![][rokbb]

Whether you're installing RokBB or RokNavMenu, the contents of the downloaded zip file you receive from RocketTheme can be uploaded directly to your phpBB installation. Here is a quick list of critical files.

* **menunav.php** upload to → **phpBB root directory **
* **rokbb.php** upload to → **phpBB root directory **
* **adm/rokbb** folder upload to → **your_phpbb_root/adm/ **
* **adm/style/acp_rokbb.html** upload to → **your_phpbb_root/adm/style/ **
* **includes/rokbb** upload upload to → **your_phpbb_root/includes/ **
* **includes/acp/acp_rokbb.php** upload to → **your_phpbb_root/includes/acp/ **
* **includes/acp/info/acp_rokbb.php** upload to → **your_phpbb_root/includes/acp/info/ **
* **language/en/acp_rokbb.php** upload to → **your_phpbb_root/language/en/ **

After this this done, log in to the **phpBB Administration Control Panel** and change the following settings:

* **General → Server configuration → Load settings** → Recompile stale style components to **Yes**
* **General → Server configuration → Security Settings** → Allow php in templates to **Yes**

**Purge the cache** in General tab. After emptying cache complete following steps:

* Go to the **System tab → Module Management category → Administration Control Panel**.
* Select **Styles** in the Module management list.
* At the bottom-left module creation field, type `RocketTheme Styles` then press the **Create new module** button.
* Make sure **Module** is enabled and **Module Type - Category** is selected. 
* Press **Submit**.
* Click on the newly created **RocketTheme Styles** category.
* Now we can add the style and other templates for configuration. There is a dropdown list at the bottom right where you can browse and select the module. Find the style to add it for configuration. 
* Press **Add module**.
* Do the same with **Global Configuration**.
* After adding it. Press **Enable** to make the module active.
* Now go to the **Styles** tab at the top. **RocketTheme Styles** category is third in a row. You can now select the Acacia style and configure it's options.

>> Tip: You can add as many style modules as you want.

Don't be worried concerning the installation process as we only need this operation to be executed once. After that, to upgrading RokBB will only involve replacing files.

[filezilla]: https://filezilla-project.org/download.php
[rokbb]: assets/rokbb.jpg
[style2]: assets/style_2.jpeg
[style3]: assets/style_3.jpeg