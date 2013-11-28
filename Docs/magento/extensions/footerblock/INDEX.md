---
title: FooterBlock
description: Your Guide to the FooterBlock Extension for Magento
tags: [Extension, Plugin, RokMage, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!footerblock:FooterBlock

---

Introduction
-----

![][demo]

The FooterBlock module overrides the default Magento footer with one configurable from the admin. It adds in three list columns and one text box (for disclaimers etc), in addition to styling the footer menu.

The 3 list columns can be configured from the admin to show a variety of different product lists. From the admin you can decide how many products to include in the lists, whether or not to truncate the titles, and whether to display them randomly or by catalog order (this only applies to Featured Products). 

Each column has its own configuration section. First, you can choose which product list to show. You can choose from: **Best-Selling**, **Featured Products**, **Recently Added**, **Most Viewed**, and **Highest Rated**. You also have the option of choosing **Custom Text** (input below) which allows you to add your own content in the space provided.

>> NOTE:  If you wish to use dynamically updating lists (﻿Best-Selling, Recently Added, Most Viewed, & Highest Rated﻿)﻿ you will need to disable the cache for **Blocks HTML output** by going to **System -> Cache Management** in the admin. If not, the lists won't be updated and the cached version will be displayed. 

Setup
-----

RokMage Modules can be managed via the configuration interface accessible by navigating to **Admin -> System -> Configuration** and clicking on the corresponding extension in the sidebar under **RokMage Modules**. 

You will want to make sure that the **Configuration Scope** is set to the theme you wish to modify the settings unless you wish to change the default for all scopes.

![][extension1]

:	1. **Enable Footer Block** Enables or disables the footer block module in the store view. [20%, 39%, se]
	2. **Number of Items in Lists** Sets the number of items that appear in the list columns. [26%, 39%, se]
	3. **Truncate Product Titles** Truncates long product titles so they fit in the block. [32%, 39%, se]
	4. **Max Titles Length** Sets the maximum length (in characters) of titles that appear in the footer. [45%, 39%, se]
	5. **Randomize Products** Randomizes products that appear in the footer with each page load. [59%, 39%, se]
	6. **Show Recently Viewed in Footer** Shows recently viewed products in the footer. This is a useful tool when you want to encourage buyers that may be thinking about a product they viewed previously. [72%, 39%, se]

1. **Enable Footer Block**: Enables or disables the footer block module in the store view.

2. **Number of Items in Lists**: Sets the number of items that appear in the list columns.

3. **Truncate Product Titles**: Truncates long product titles so they fit in the block.

4. **Max Titles Length**: Sets the maximum length (in characters) of titles that appear in the footer.

5. **Randomize Products**: Randomizes products that appear in the footer with each page load.

6. **Show Recently Viewed in Footer**: Shows recently viewed products in the footer. This is a useful tool when you want to encourage buyers that may be thinking about a product they viewed previously.

![][extension2]

:	1. **Column Content** Sets the type of content that appears in the column. [23%, 39%, se]
	2. **Column Custom Text** Allows you to enter a block of text that appears in the column. [30%, 39%, se]
	3. **Column Cms Block** Select a CMS block to include in custom content. [74%, 39%, se]

These options remain constant throughout all of the column settings (1st, 2nd, 3rd).

1. **Column Content**: Sets the type of content that appears in the column.

2. **Column Custom Text**: Allows you to enter a block of text that appears in the column.

3. **Column Cms Block**: Select a CMS block to include in custom content.

![][extension3]

:	1. **Text Box Content** Allows you to enter text to appear in the text box. This can include HTML for a more refined look. [8%, 38%, se]
	2. **Text Box Column Cms Block** Select a CMS block to include in the text box. Select **Disabled** for none. [30%, 38%, se]
	3. **Footer CMS Links** You can slect CMS page links to show in the footer by choosing them from this list. [35%, 38%, se]
	4. **Include 'Cart' Link** Includes a link to the cart. [62%, 38%, se]
	5. **Include 'Sitemap' Link** Includes a link to the sitemap. [68%, 38%, se]
	6. **Include 'Search Terms' Link** Includes a link to the Search Terms page. [73%, 38%, se]
	7. **Include 'Advanced Search' Link** Includes a link to the Advanced Search page. [78%, 38%, se]
	8. **Include 'Contact Us' Link** Includes a link to the Contact page. [83%, 38%, se]
	9. **Disable Footer Logo** Disables or enables the presence of the logo in the footer. [88%, 38%, se]

1. **Text Box Content** Allows you to enter text to appear in the text box. This can include HTML for a more refined look

2. **Text Box Column Cms Block** Select a CMS block to include in the text box. Select **Disabled** for none.

3. **Footer CMS Links** You can slect CMS page links to show in the footer by choosing them from this list.

4. **Include 'Cart' Link** Includes a link to the cart.

5. **Include 'Sitemap' Link** Includes a link to the sitemap.

6. **Include 'Search Terms' Link** Includes a link to the Search Terms page.

7. **Include 'Advanced Search' Link** Includes a link to the Advanced Search page.

8. **Include 'Contact Us' Link** Includes a link to the Contact page.

9. **Disable Footer Logo** Disables or enables the presence of the logo in the footer.

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
[demo]: assets/demo_footerblock.jpeg