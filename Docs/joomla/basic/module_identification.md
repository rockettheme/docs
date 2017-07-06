---
title: How to Identify Specific Modules
description: Your Guide to identifying specific modules from the frontend of Joomla
breadcrumb: /joomla:Joomla/!basic:Basic Tutorials/!module_identification:Module Identification

---

Introduction
-----

Identifying modules that appear on your site from the frontend can be very useful, and important when you are attempting to edit content that already exists. In the case of a RocketLauncher, this can be a great way to quickly identify a module and find it in the backend without having to dig through the browser's inspector.

Joomla 3.2+
-----

### Frontend Edit Buttons and Tooltips

![Frontend Editing](assets/id_1.jpeg)

Joomla 3.2 introduced a very useful feature that makes this very easy.

If you log in on frontend of the site, as someone with edit rights (example: Super Admin), you can actually hover over any part of the site and a little edit icon will appear for each module or article. 

If you then hover over the edit icon, it will show you a tooltip of what is what and you can click it to get into the right location in your admin (either the article or the module manager) to edit that specific item. The tooltip includes both the title of the module, and its assigned position.

This may not appear if you are only logged in to the administrator side of the site. You may need to log in on the frontend, separately.

### Preview Module Positions

Another helpful option would be to load the frontend URL with an appended `?tp=1`. This will pull up a preview of the module positions. To make this work you have to go first navigate to **Administrator > Extensions > Template Manager > Options > Preview Module Positions** and set it to **enabled**.

For the purpose of simplicity, we try to name modules in a way that makes them easier to identify from the backend. We use abbreviations like **FP** for modules that appear exclusively on the front page of the site, and/or name them after the title or content that appears within them.
