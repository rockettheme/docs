---
title: Panacea: Recreating the Demo - Rotator
description: Your Guide to Recreating Elements of the Panacea Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/panacea:Panacea

---

Rotator
-----

![][demo]

The most noticeable feature of the Panacea template is its Background Rotator below the header. This is a Gantry Feature which offers basic background rotator functionality with content calling controls. Load articles from a set category/section and select images from the background manager to fully control the effect, it is very simple.

>> Access the Background Rotator from **Admin → Template Manager → Panacea → Style → Rotator**. Select the images from the Background Rotator Manager, and configure the feature from the Background Rotator controls.

### Background Rotator Manager

![][rotator]

The Background Rotator Manager is the administrator based control which determines which background images appear in the rotator. Simply go to **Admin → Template Manager → Panacea → Style → Rotator** and select the Manage button to load the Background Rotator Manager. The manager operates as follows:

* **Backgrounds Available:** This is a list of all background files that are available, they are loaded from the **/templates/rt_panacea_j15/images/showcase-bgs** directory.
* **Backgrounds Set:** This is a list of all the background files that are currently in use, and will appear in the background rotator on the frontend. You set backgrounds by dragging and dropping the file names from the Backgrounds Available list.
* **Drop Preview:** This is the dashed box above the lists, simply drag and drop a file name into this *Drop Here* box and the image will be shown in the preview area.
* **Save/Cancel:** Once you have decided which backgrounds you want, simply click the *Save* button.

### Background Rotator Controls

![][style]

Other than determining what images to display, you can control various other aspects of the feature, all from the Gantry administrator: **Admin → Template Manager → rt_panacea_j15 → Settings → Rotator**

* **Enable:** Enable or Disable the Rotator feature.
* **Controls:** Set whether the controls - arrows and placement identifiers - appear at the top of the mainbody or are invisible.
* **Autoplay:** Choose whether the feature rotates automatically or via manual input.
* **Delay:** If Autoplay is enabled, set the Delay in seconds.
* **Order:** Select the order in which the rotator items will display.
* **Section/Category:** Set the Section or Category where you wish to load the rotator content from.
* **Manager:** Set which background images load.

[rotator]: assets/setrotator.jpeg
[style]: assets/setstyle.jpeg
[demo]: assets/demo_10.jpg
