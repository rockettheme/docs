---
title: Halcyon: Recreate the Demo
description: Your Guide to Using the Halcyon Theme for Magento
tags: [Theme, Template, RokMage, Requirements, Setup, Demo, Tutorial]
breadcrumb: /magento:Magento/!themes:Themes/halcyon:Halcyon

---

Introduction
-----

You can recreate a number of different elements found on the front page of the Halcyon demo by modifying some basic extension settings. Depending on which extension you wish to recreate on the page, you may only need to add and adjust the settings of a single module.

The Halcyon theme handles most of the visual details for you.

All of the settings that need to be adjusted to match the demo can be found in the relevant sections under **System -> Configuration -> RT RokMage Modules**. Any options not mentioned below can be left at default settings.

![][rokmagelayout]

### ModalHeader

The **ModalHeader** module adds in some extra functionality to the header section of a Magento store. It connects the "Log In" link to a modal login form, and adds a text-resizer. It also adds a modal shopping cart viewer and styling to the search form and breadcrumbs.

#### GENERAL

| Option                      | Setting |  
| :-------------------------- | :------ |  
| Enable Modal Header         | Yes     |  
| Enable Custom Form Elements | Yes     |  
| Enable Custom Breadcrumbs   | Yes     |  
| Build Title Spans           | No      |  
| Disable Modal Log In        | No      |  
| Disable Text Resizer        | Yes     |  
| Disable Date                | Yes     |  

#### IE Support

| Option                  | Setting |  
| :---------------------- | :------ |  
| Redirect IE6/7 Visitors | Yes     |  
| Load IE6/7 Helper Fies  | No      |  

#### Modal Window Animation Settings

~~~ .html
overlayopacity: 0.2,overlayinspeed: 300,modalpreposition: {"top":"43%"},modalpauseb4entry: 200,modalentryanimation: {"top": "50%", "opacity": "1"},modalentryspeed: 550,modalexitanimation: {"top": "55%", "opacity": "0"},modalexitspeed: 350,pauseb4overlayfadeout: 500,overlayoutspeed: 200
~~~

### MageMenus

Replace the default Magento dropdown menu with fully configurable, animated, jQuery based top and side menus. 

#### General

| Option                 | Setting |  
| :--------------------- | :------ |  
| Enable Top Menu        | Yes     |  
| Enable Left Side Menu  | Yes     |  
| Enable Right Side Menu | No      |  

#### Top Menu Settings

| Option                     | Setting  |  
| :------------------------- | :------- |  
| Double Column Dropdown     | No       |  
| Include Home Link          | Yes      |  
| Include Catalog Categories | Yes      |  
| Slot #1 CMS Page Link      | About Us |  
| Include Contact Link       | Yes      |  

#### Top Menu Animation Settings

~~~ .html
mm_slidedownspeed: 100,mm_fadeoutspeed: 50,mm_css_pre: {left: 100, opacity: 0 },mm_animatein: {left: 165, opacity: 1},mm_animateout: {opacity: 0, left: 185},mm_animate_speed: 150,mm_pause: 0
~~~

### HomePage Grid

Set up your store homepage with just a few clicks, with a welcome message and product lists defined in the Admin Panel. 

#### General

| Option               | Setting |  
| :------------------- | :------ |  
| Enable Homepage Grid | Yes     |  

#### Product Grid Settings

| Option                               | Setting                                                         |  
| :----------------------------------- | :-------------------------------------------------------------- |  
| Product Grid Title                   | A selection of our products!                                    |  
| Product Grid Text                    | `<p>Check out a selection of our items currently for sale:</p>` |  
| Number of products to show in grid   | 6                                                               |  
| Filter Products By                   | Show All Products                                               |  
| Truncate Product Titles/Descriptions | Truncate On                                                     |  
| Max Titles Length                    | 50                                                              |  
| Max Descriptions Length              | 110                                                             |  
| Image Height                         | 300                                                             |  
| Image Width                          | 300                                                             |  

### RokMage Layouts

Configure the theme's responsive layout and/or fix to a specific width.

#### Responsive Layout Settings

| Option                    | Setting |  
| :------------------------ | :------ |  
| Enable Responsive Layouts | Yes     |  
| Fix to Specific Width     | No      |  

### ContentSlider

Add a fully configurable content slider to the homepage and category pages, choosing which products to show. 

#### General

| Option                 | Setting               |  
| :--------------------- | :-------------------- |  
| Enable Homepage Slider | Yes                   |  
| Enable Category Slider | Yes                   |  
| Homepage Content Type  | Show Catalog Products |  
| Show Prev/Next Arrows  | No                    |  
| Duration               | 4                     |  

#### Homepage Slider Products

| Option                               | Setting           |  
| :----------------------------------- | :---------------- |  
| Filter Products By                   | Show All Products |  
| Truncate Product Titles/Descriptions | Truncate On       |  
| Max Titles Length                    | 60                |  
| Max Descriptions Length              | 250               |  
| Image Size                           | 350               |  

#### Category Slider Products

| Option                               | Setting           |  
| :----------------------------------- | :---------------- |  
| Filter Products By                   | Show All Products |  
| Truncate Product Titles/Descriptions | Truncate On       |  
| Max Titles Length                    | 30                |  
| Max Descriptions Length              | 130               |  
| Hide Description                     | No                |  
| Image Size                           | 230               |  

### ProductScroller

Add a fully configurable, jQuery based, animated horizontal product scroller to the homepage and category pages.

#### General

| Option                   | Setting     |  
| :----------------------- | :---------- |  
| Enable Homepage Scroller | Yes         |  
| Enable Category Scroller | Yes         |  
| Prev/Next Function       | Page        |  
| Truncate Product Titles  | Truncate On |  
| Max Titles Length        | 32          |  
| Image Size               | 140         |  
| Speed                    | 1           |  
| Circular                 | Loop On     |  
| Products Per Page        | 6           |  
| Use Tooltip for Details  | Yes         |  
 
#### Homepage Scroller Products

| Option             | Setting           |  
| :----------------- | :---------------- |  
| Filter Products By | Show All Products |  
 
#### Category Scroller Products

| Option             | Setting           |  
| :----------------- | :---------------- |  
| Filter Products By | Show All Products |  

### CategoryView

Add the ability to truncate product titles and descriptions, and switch between grid and list views without a page refresh.

#### GENERAL

| Option                               | Setting     |  
| :----------------------------------- | :---------- |  
| Enable Category View                 | Yes         |  
| Truncate Product Titles/Descriptions | Truncate On |  
| Max Titles Length                    | 50          |  
| Max Descriptions Length              | 300         |  

 
#### PRODUCT FILTER SETTINGS

| Option               | Setting |  
| :------------------- | :------ |  
| Use Accordion Effect | Yes     |  
 
#### CATEGORY PRODUCT IMAGE SETTINGS

| Option       | Setting |  
| :----------- | :------ |  
| Image Height | 300     |  
| Image Width  | 300     |  

### ProductView

Replace the default zoom with a jQuery version, add improved thumbnails, and show additional info in switchable tabs. 

#### General

| Option              | Setting |  
| :------------------ | :------ |  
| Enable Product View | Yes     |  
| Use 2 Column Layout | Yes     |  
 
#### PRODUCT INFO SETTINGS

| Option                     | Setting                |  
| :------------------------- | :--------------------- |  
| Enable Tabbed Product Info | Yes                    |  
| Quick Info Attribute       | Short Description      |  
| Quick Info Content         | `{{value}}`            |  
| Tab #1 Attribute           | Description            |  
| Tab #1 Content             | `{{value}}`            |  
| Tab #2 Attribute           | Additional Information |  
| Tab #2 Content             | `{{value}}`            |  
| Show Product Reviews       | Yes                    |  
| Upsell Columns             | 2                      |  
 
#### PRODUCT IMAGE SETTINGS

| Option                          | Setting                             |  
| :------------------------------ | :---------------------------------- |  
| Enable RokMage media view       | Yes                                 |  
| Resize product image background | No                                  |  
| Image background location       | default/rokmage-productview/images/ |  
| Small Image Width               | 260                                 |  
| Small Image Height              | 260                                 |  
| Large Image Width               | 1000                                |  
| Large Image Height              | 1000                                |  
| Thumbnail Width                 | 78                                  |  
| Thumbnail Height                | 78                                  |  
| Disable Zoomer                  | No                                  |  
| Use Overlaid Thumb Gallery      | Yes                                 |  
| Spacing Offset                  | 20                                  |  

### CmsCallouts

Add your left and right sidebar callout content directly from the admin - no need to touch any template or layout files. 

#### GENERAL

| Option                   | Setting |  
| :----------------------- | :------ |  
| Enable Left CMS Callout  | Yes     |  
| Enable Right CMS Callout | Yes     |  
 
#### CONTENT

| Option              | Setting           |  
| :------------------ | :---------------- |  
| Left Callout Title  | Left CMS Callout  |  
| Right Callout Title | Right CMS Callout |  

**Left Callout Text** 

~~~
<p>You can add your content here by going to Admin -&gt; Config -&gt; CmsCallouts -&gt; Left Callout Text. You can also disable this box entirely.</p>
~~~

**Right Callout Text**

~~~
<p>You can add your content here by going to Admin -&gt; Config -&gt; CmsCallouts -&gt; Right Callout Text. You can also disable this box entirely.</p>
~~~

### FeaturedProducts

Define your featured products from the admin, using selected category, attribute, or multi-select product list. 

#### GENERAL

| Option                | Setting       |  
| :-------------------- | :------------ |  
| Get Featured Products | Featured List |  
 
#### SETTINGS

| Option               | Setting                                                                                                          |  
| :------------------- | :--------------------------------------------------------------------------------------------------------------- |  
| Select Featured List | Select at least 6 'Featured' products from this list. Hold **ctrl** and click to multi-select (**cmd** on a Mac) |  

### ImageBorders

Use jQuery and CSS to style your product images, giving the ability to add any border or frame you desire. 

#### General

| Option               | Setting |  
| :------------------- | :------ |  
| Enable Image Borders | No      |  

### FooterBlock

Add product lists to the footer, a text box (for disclaimers etc), styled footer menu and Cart count linked to the modal cart viewer. 

#### General

| Option                   | Setting     |  
| :----------------------- | :---------- |  
| Enable Footer Block      | Yes         |  
| Number of Items in Lists | 6           |  
| Truncate Product Titles  | Truncate On |  
| Max Titles Length        | 22          |  
 
#### Settings

| Option             | Setting                |  
| :----------------- | :--------------------- |  
| 1st Column Content | Recently Added List    |  
| 2nd Column Content | Highest Rated Products |  
| 3rd Column Content | Featured Products List |  

**Text Block Content**

~~~ .html
<h3>Disclaimer</h3>
<p><strong>Important:</strong> This demo is purely for demonstration purposes and all the content relating to products, services and events are fictional and are designed to showcase a live shopping site. All images are copyrighted to their respective owners. This is not an actual store, only representative of one.</p>
<p><strong>You can edit this text by going to Admin -&gt; Configuration -&gt; RT RokMage Modules -&gt; FooterBlock -&gt; Text Box Content.</strong></p>
~~~

### TinyMCE

Enables the Tiny MCE editor for RokMage Extensions.

#### General

| Option                                 | Setting                |  
| :------------------------------------- | :--------------------- |  
| Enable Tiny MCE for RokMage Extensions | Yes                    |  
| 2nd Column Content                     | Highest Rated Products |  
| 3rd Column Content                     | Featured Products List |  

**Textareas to enable for**

~~~ .html
#homepage_grid_settings_welcome_msg,#homepage_grid_settings_grid_text,#content_slider_settings_custom_one_slide_one_content,#content_slider_settings_custom_two_slide_two_content,#content_slider_settings_custom_three_slide_three_content,#content_slider_settings_custom_four_slide_four_content,#cms_callouts_settings_leftcallouttext,#cms_callouts_settings_rightcallouttext,#footer_block_settings_first-custom-text,#footer_block_settings_second-custom-text,#footer_block_settings_third-custom-text,#footer_block_settings_text-box
~~~

[rokmagelayout]: assets/RokMageLayout.jpg