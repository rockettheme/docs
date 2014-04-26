---
title: How to Update a RocketTheme Template
description: Your Guide to Updating a Template from RocketTheme
breadcrumb: /joomla:Joomla/!platform:Platform/!update_templates:Update a RocketTheme Template

---

Introduction
-----

RocketTheme's templates continue to receive updates long after the initial release. Bug fixes, additional features, and other minor adjustments come in the form of updates that are made available to active Joomla Club members and purchasers of the template.

One of the most common questions we receive concerning the process of updating a template by RocketTheme is whether or not any special precaution has to be taken, or if any additional steps are required.

This guide will cover the necessary steps and precautions involved with updating a theme from RocketTheme.

We highly recommend, as a first step to any update or change to your site, that you **perform a full backup**. Doing this will ensure that no matter what happens, you will be able to restore your site back to the way it was prior to the update. While we do not anticipate any issues involving our products, there is no reason to leave room for error.

If No Changes Have Been Made to Template Files
-----

If you have made no changes to the existing template files (not including customization done on the backend of Joomla using the Template Manager) you should be able to update using the **Joomla Extension Manager** as you would any other Joomla template or extension.

If you have added any additional files (custom CSS files, images, etc.) they will not be affected by the update. Only files included with the core template as received by RocketTheme are at risk of being overwritten.

Here are the step-by-step instructions for updating a Joomla template in this scenario.

![][update1]

* Download the new Standalone template ZIP file from [RocketTheme.com](http://rocketthme.com) as seen in the image above.
* Navigate to the **Extension Manager** in the Joomla Administrator as seen in the image below.
* Select **Upload Package File**.
* Select the ZIP file (without unzipping).
* Click **Upload and Install**.

![][update2]

Once this is done, a notice should appear indicating that the template has been successfully updated.

At this point, you should be able to test your site for any issues and operate as normal.

If Changes Have Been Made to Template Files
-----

If you have made changes directly to the template files, you will need to take extra caution while updating. Any files changed by the update will likely overwrite any of these existing modifications. You should make a note of any and all of these changes so you can reapply them after the update.

The rest of the update process should proceed as described in the previous section. Make sure to test all of your custom code to ensure that they work as expected with the updated template.

### Difference / Merge Tools

If you do not have a list of the custom changes made to your template files, but need to make the update anyway, a difference / merge tool can come in handy.

These applications allow you to compare, contrast and merge changes in both files and folders. There are a variety of different tools available for both Windows and OS X, both free and commercial. All are based on the same foundation of difference and merge but have different UIs (user interfaces) and tools to perform the task. 

Here are a few tools to consider:

* [Araxis Merge][araxis] - Windows / OS X - Commercial
* [DiffMerge][diffmerge] - Windows / OS X - Free
* [WinMerge][winmerge] - Windows - Free

These tools will make it easier to identify changes and compare files as they existed before and after the update. 

[araxis]: http://www.araxis.com/merge/
[diffmerge]: http://www.sourcegear.com/diffmerge/downloads.php
[winmerge]: http://winmerge.org/
[update1]: assets/update_1.jpeg
[update2]: assets/update_2.jpeg
