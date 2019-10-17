---
title: Galatea: FAQ
description: Your Guide to Using the Galatea Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/galatea:Galatea

---

## Is There a Way to Use a Normal Menu on the Front Page?

Absolutely! Just use a **Menu** particle or widget in place of the Overlay Toggle particle in the Navigation section.

## What is RokSprocket?

[RokSprocket][roksprocket] is a powerful content display extension for WordPress 3.x. It was designed as the successor to our legacy content extensions: RokStories, RokTabs, RokNewsPager, RokNewsflash, RokMicronews, and basically any widget in the RT arsenal that manipulates and displays posts.

## What is Gantry?

[Gantry][gantry] is, as a basic definition, a framework used for assembling, building and maintaining a RocketTheme theme. It is an advanced platform for dramatically extending the capabilities of the entire theming system of WordPress.

## Can I install RocketLauncher onto an existing WordPress! website?

No. RocketLauncher will install both WordPress and the demo sample content and images, so you will need a fresh WordPress! installation.

## I installed Galatea RocketLauncher but the images are different with the demo site.

To avoid image license copyright issues, all sample content images shown in our demo site will be replaced with blank versions in the RocketLauncher version.

## Changes I make to the slider and overlay images in the FlexSlider particle aren't appearing on the front end. What's going on?

This is a very simple fix caused by a conflict between your style settings and the `demo.css` file which is loaded through the **Custom CSS/JS** atom found in the **Page Settings** tab within the Gantry 5 Administrator. This demo file is intended to make the RocketLauncher match the demo as much as possible, giving it its unique styling. However, removing this file enables you to replace these elements.

![Fix](assets/custom_atom_1.jpeg)

Simply navigate to this tab, scroll down to the **Atoms** section, and select the **Custom CSS / JS** atom. From here, you can locate and remove the **Demo CSS** item. Once this is done, save your page settings and refresh. Your changes should now appear on the front end.

[gantry]: http://gantry.org/
[forum]: http://www.rockettheme.com/forum/wordpress-theme-galatea
[roksprocket]: http://www.rockettheme.com/wordpress/extensions/roksprocket