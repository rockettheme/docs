---
title: RokBooster: Frequently Asked Questions
description: Your Guide to Using RokBooster for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!rokbooster:RokBooster/!faq:FAQ/

---

#### Does RokBooster Work with Email Cloaking?

Email cloaking is an excellent way to present your email address to visitors while masking it from automatic bots and other data mining programs that scour the Web in search of contact information that can be used to send spam and/or perform other undesirable activities.

Joomla's built-in cloaking functionality does work with RokBooster, but issues can present themselves if a full page scan is being performed.

![][scan]

:   1. **Scan Method** [67%, 25%, se]

If you are experiencing issues running RokBooster with email cloaking, you can resolve this issue by navigating to **Admin -> Extensions -> Plug-in Manager -> System - RokBooster** and clicking on the **Advanced Options** tab.

From here, you can change the method by selecting the **Scan Method** dropdown and selecting either **Joomla Header Scan** or **Full Header Scan**. The **Full Page Scan** method conflicts with the mail cloak, which can break functionality.

[scan]: assets/scan.jpg