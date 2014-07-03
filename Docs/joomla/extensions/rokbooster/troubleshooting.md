---
title: RokBooster: Troubleshooting
description: Your Guide to Using RokBooster for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!rokbooster:RokBooster/!faq:FAQ/

---

Troubleshooting RokBooster Issues
-----

Like any optimization extension for Joomla, RokBooster may need to be tuned to meet the needs of your specific site. Other extensions, theme properties, JavaScript, and other elements need to be taken into account whenever RokBooster is being used. 

RokBooster's job is to compress a lot of these elements to make them easier to pull up and display for the user. If this compression causes an issue, you can often solve the problem after a little troubleshooting.

Every site is different, and it is impossible to account for the millions of different script and caching configurations out there. We highly recommend doing any tuning on a separate development server apart from your live site, and test these settings thoroughly prior to taking them to your production server.

## Clear RokBooster Cache

If you are making changes to your site, remember to clear the RokBooster cache. This is best done in plugin settings to remove the files. You can find this option by navigating to **Administrator > Extensions > Plugin Manager > System - RokBooster > Core Options** and selecting **Clear All Cached Files**.

Alternatively, you can clear the cache through Joomla by navigating to **Administrator > System > Clear Cache**.

## Check to Make Sure RokBooster is Firing Consistently

If you are having intermittent problems, you always want to check if RokBooster is firing, or firing properly. We generally do this using the **Web Inspector** in **Google Chrome**. In the inspector, go to **Resources > Frames > (Site name) > Scripts : Stylesheets** and look for a file with a similar name to `8914890328409324.php`. If this PHP file is present, RokBooster is firing properly.

If the problem is intermittent, and doesn't present itself with each refresh, check this multiple times to determine if RokBooster is firing each time. It's always useful to know per refresh if the right files have actually been compressed to identify whether RokBooster is the cause of the issue.

## Determine if a Single File is Causing the Issue

It is useful to use the same process mentioned in the last section to figure out if its just a single file that is causing the problem. The **Resources** tab will give you a list of all the scripts and stylesheets that are called on the page. 

You can add these files (one by one) to the **Ignored Files** setting in RokBooster's **Advanced Settings** found by navigating to **Administrator > Extensions > Plugin Manager > System - RokBooster > Advanced** and test to see which one (or which ones) are creating conflict.

Once the problem is resolved, simply keep it as a permanent exception.

## Change the Permissions Setting

If you get a page with no styling, just content, there may be an issue with the permission settings. These settings can be altered using the **Advanced** tab in the RokBooster settings. Toggle the option between **Group Can Write (0664)** and **Only User Can Write (0644)** and test to see if the issue has been resolved.

## Gradually Test RokBooster

If you continue to have issues, you can try turning off RokBooster entirely (no files are altered by RokBooster) and turn it back on, piece by piece. 

Try just turning on CSS compression, then go through the various settings (JS, Font, etc.) to see if it's just a specific category that is causing a problem.