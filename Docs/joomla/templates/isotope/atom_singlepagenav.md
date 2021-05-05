---
title: Isotope: Single Page Nav
description: Your Guide to Using Single Page Nav
breadcrumb: /joomla:Joomla/!templates:Templates/isotope:Isotope

---

Single Page Nav Atom
---------

![](assets/singlepagenav.gif)

<a href="https://github.com/ChrisWojcik/single-page-nav">Single Page Nav</a> is a JS library that scrolls to a section on your one page website when you click on a menu item. 

For a demonstration, please visit our <a href="https://getgrav.org/#why_grav">GetGrav.org website</a>.

To initialize the library, go to your Base Outline > Page Settings and drag the Single Page Nav atom into the dock. You can then save the Page Settings.

![](assets/spn1.jpg)

>> NOTE: This atom works best with the Fixed Header atom so as to allow the user to visit additional sections on the page by clicking on each menu item.

By clicking on the atom's cog icon, you will find the Global settings to be used for the Single Page Nav atom:

![](assets/spn2.jpg)

| Option           | Description                                                                                             |
| :-----           | :-----                                                                                                  |
| Section          | Define the ID or class of the section or menu where you want to target the single page nav. 			 |
| Offset           | Enable or disable offset (best used for fixed header nav).	                      	                     |
| Current Class    | The class to apply to the menu item link corresponding to the active section on the page.               |
| Update Hash      | Update URL with Hash in address bar when item is selected.                    						     |
| Speed            | Speed of the scroll on click (ms).                                                                      |
| Filter Class(es) | Name of selector in section or menu that should NOT use the Single Page Nav atom (separate multiple selectors by commas).     |

For this atom to work properly, please ensure that the JavaScript Frameworks atom is loaded and the jQuery Framework and UI Core are enabled within that atom as shown:

![](assets/spn8.jpg)

Setting Up
---------
Once the atom is in place, and you have decided what section you want to use (in this case we use the navigation section), then you can start setting up the menu items (or logo) with the corresponding sections on the page.

In this case, I've set the logo to the **#g-slideshow** section:

![](assets/spn3.jpg)

And I've set all the Menu Items to **System Links -> URL** with the appropriate section as shown:

![](assets/spn4.jpg)

Try to ensure that the menu items associated with the sections on the page are in the correct order (sections from top to bottom correspond with menu items left to right), otherwise unwanted results may occur.

Once everything is set up accordingly, you should see the menu function as shown from the GIF at the beginning of this doc.

Mobile Setup
-------------

Since the Single Page Nav should also function in the mobile view, we would encourage you to remove the mobile menu particle from the Offcanvas section:

![](assets/spn6.jpg)

Then your menu will then display similarly in the mobile view:

![](assets/spn7.jpg)


Filter Class
---------

As shown in the settings screenshot, I've set `.g-social a` as one of the Filter Classes, so the social particle links will still work. Any link in the section that is not used for the purpose of this atom should be filtered.

Current Class
---------

The Current Class setting will specifically add a class to the menu item link when you are currently visting that section. By default, we use the `current` class:

![](assets/spn5.jpg)

You can change the class name to whatever you want and then add any specific styling you would like to it.