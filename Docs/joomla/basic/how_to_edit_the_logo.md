---
title: Editing the Logo on a RocketTheme Template
description: How to edit the logo on a RocketTheme template powered by Gantry.
breadcrumb: /joomla:Joomla/!basic:Basic Tutorials/

---

Introduction
-----
Editing the logo on a RocketTheme template is fairly simple, and there are two primary methods of getting the job done. Either of the methods listed below will work just fine, though you'll want to decide whether you want to create a "default" logo that's easy to go back to after a seasonal or otherwise temporary logo is put in its place for a period of time.

### The Logo Picker
![][logo2]
The Logo Picker method essentially allows you to pick from any image in your Media Manager (or RokGallery) and use that in place of the logo in its associated position. The logo will continue to act the same way as it did when you first installed the RocketLauncher and/or standalone template, though its source image file will be directed to the image you've selected.

To accomplish this, you'll want to follow these steps:

1. Navigate to **Administrator → Extensions → Templates Manager** and select the Gantry-powered RocketTheme template you're currently using as your default. If you wish to change your logo in only a select number of pages, you will need to either create or choose an existing template override to apply this change to.

2. Navigate to the **Style** tab.

3. Set the **Logo** **Type** to **Custom**.

4. Select the source you would like to use for your custom logo. This can be either MediaManager or RokGallery, depending on what you have installed and are using to store the file.

5. Select your logo, click **Instert**, and **Save**.

Your logo should now be replaced by the image you've selected.

>> Note: Some templates have this option under the **Features** tab rather than **Style**.

### Manual Logo Change
![][logo1]
Let's say you want to set a primary logo that you can go back to at any given time without having to reselect it as a custom logo. This can be done fairly easily by replacing our logo image file with your own by doing a manual FTP upload to a specific directory.

Doing this makes it a little easier to revert back to the logo you wish to have after a seasonal or temporary change.

Here are the steps you'll want to follow:

1. Navigate to **Administrator → Extensions → Templates Manager** and select the Gantry-powered RocketTheme template you're currently using as your default. If you wish to change your logo in only a select number of pages, you will need to either create or choose an existing template override to apply this change to.

2. Navigate to the **Style** tab.

3. Make sure the **Logo** **Type** is set to the name of the template. For example: The Logo Type for Praxis is set to `Praxis` by default.

4. Take your custom logo and rename it to `logo.png` in your local file directory.

5. Upload the `logo.png` file to the `/templates/(your RocketTheme template)/images/logo/preset*/` directory and elect to override the existing file if prompted.

6. Clear your browser cache and refresh your site's home page to test the change.

If you can not see your new logo, ensure you have uploaded it to the right directory and the directory permissions are writable.

>> Note: Some templates have this option under the **Features** tab rather than **Style**.

[logo1]: assets/logo_1.jpeg
[logo2]: assets/logo_2.jpeg