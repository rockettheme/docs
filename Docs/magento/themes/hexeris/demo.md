---
title: Hexeris: Recreate the Demo
description: Your Guide to Using the Hexeris Theme for Magento
tags: [Theme, RokMage, Requirements, Setup, Demo, Tutorial]
breadcrumb: /magento:Magento/!themes:Themes/hexeris:Hexeris

---

Introduction
-----

You can recreate a number of different elements found on the front page of the Hexeris demo by modifying some basic extension settings. Depending on which extension you wish to recreate on the page, you may only need to add and adjust the settings of a single module.

The Hexeris theme handles most of the visual details for you.

All of the settings that need to be adjusted to match the demo can be found in the relevant sections under **System -> Configuration -> RT RokMage Modules**. Any options not mentioned below can be left at default settings.

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

#### Modal Window Animation Settings

**Additional Settings**

~~~ .html
overlayopacity: 0.2,overlayinspeed: 300,modalpreposition: {"top":"43%"},modalpauseb4entry: 200,modalentryanimation: {"top": "50%", "opacity": "1"},modalentryspeed: 550,modalexitanimation: {"top": "55%", "opacity": "0"},modalexitspeed: 350,pauseb4overlayfadeout: 500,overlayoutspeed: 200
~~~

#### IE Support

| Option                  | Setting |  
| :---------------------- | :------ |  
| Redirect IE6/7 Visitors | Yes     |  
| Load IE6/7 Helper Fies  | No      |  

**Add Classes for PIE**

~~~ .html
#homepage-contentslider-container .images button.button, #homepage-contentslider-container .backward, #homepage-contentslider-container .forward, .arrow-box, #search_mini_form input, ul#magemenu-top > li.active, ul#magemenu-top li ul, .cms-index-index .surround
~~~

### MageMenus

Replace the default Magento dropdown menu with fully configurable, animated, jQuery based top and side menus. 

#### General

| Option                          | Setting |  
| :------------------------------ | :------ |  
| Enable Top Menu                 | Yes     |  
| Enable Left Side Menu           | Yes     |  
| Enable Right Side Menu          | No      |  
| Enable Top Menu lavalamp effect | No      |  

#### Top Menu Settings

| Option                     | Setting                     |  
| :------------------------- | :-------------------------- |  
| Double Column Dropdown     | No                          |  
| Apply Right Offset Fix     | No                          |  
| Include Home Link          | Yes                         |  
| Include Catalog Categories | Yes - as standard dropdowns |  
| Slot #1 CMS Page Link      | About Us                    |
| Slot #1 sub-menu items     |                             |  
| Slot #2 CMS Page Link      | Customer Service            |
| Slot #2 sub-menu items     | enable-cookies              |  
| Include Contact Link       | Yes                         |  

#### Top Menu Animation Settings

~~~ .html
mm_slidedownspeed: 100,mm_fadeoutspeed: 50,mm_css_pre: {left: 100, opacity: 0 },mm_animatein: {left: 165, opacity: 1},mm_animateout: {opacity: 0, left: 185},mm_animate_speed: 150,mm_pause: 0
~~~

#### Top "MageMenu" Settings

| Option                       | Setting |  
| :--------------------------- | :------ |  
| Mega Dropdown Width          | 400     |  
| Visible Sub-categories Depth | 4       |  
| Number of Inner Columns      | 3       |  
| Inner Column Width           | 133     |  
| Enable Static Blocks         | Yes     |  

#### Side Menu Left Settings

| Option                          | Setting                      |  
| :------------------------------ | :--------------------------- |  
| Menu Title                      | ProductCatalog               |  
| Include Catalog Categories      | Yes - as standard accordions |  
| Visible Categories Depth        | 4                            |  
| Collapse 1st Level Parents      | No                           |  
| Default to open accordion state | no                           |  
| Show Item Count                 | Yes                          |  
| Include Contact Link            | Yes                          |  

#### Side Menu Right Settings

| Option                          | Setting          |  
| :------------------------------ | :--------------- |  
| Menu Title                      | Customer Service |  
| Include Catalog Categories      | No               |  
| Visible Categories Depth        | 4                |  
| Collapse 1st Level Parents      | No               |  
| Default to open accordion state | no               |  
| Show Item Count                 | No               |  
| Slot #1 CMS Page Link           | About Us         |  
| Slot #1 sub-menu items          |                  |  
| Slot #2 CMS Page Link           | Customer Service |  
| Slot #2 sub-menu items          |                  |  
| Include Contact Link            | Yes              |  

### HomePage Grid

Set up your store homepage with just a few clicks, with a welcome message and product lists defined in the Admin Panel. 

#### General

| Option               | Setting |  
| :------------------- | :------ |  
| Enable Homepage Grid | Yes     |  

#### Product Grid Settings

| Option                               | Setting                                                  |  
| :----------------------------------- | :------------------------------------------------------- |  
| Product Grid Title                   | Latest products                                          |  
| Product Grid Text                    | `Check out a selection of our items currently for sale:` |  
| Number of products to show in grid   | 6                                                        |  
| Default Products Layout              | Grid                                                     |  
| Filter Products By                   | Recently Added Products                                  |  
| Randomize Products                   | Off                                                      |  
| Truncate Product Titles/Descriptions | Truncate On                                              |  
| Max Titles Length                    | 50                                                       |  
| Max Descriptions Length              | 110                                                      |  
| Image Height                         | 300                                                      |  
| Image Width                          | 300                                                      |  
| Disable Ribbons                      | Yes                                                      |  

**Welcome Message**

~~~ .html
<div class="page-title">
<h1>Welcome</h1>
</div>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec pellentesque consectetur nunc, id aliquet libero tempor id. Vestibulum bibendum congue nunc, id vulputate diam. Proin commodo vitae odio ut commodo. Integer porta dolor sed molestie ullamcorper.</p>
~~~

### RokMage Layouts

Configure the theme's responsive layout and/or fix to a specific width.

#### Store Layout Overrides 

| Option                  | Setting |  
| :---------------------- | :------ |  
| Enable Layout Overrides | Yes     |  
| Use 2 Column Layout     | No      |  
| Layout Update XML       | Blank   |  

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
| Autoplay               | On                    |  
| Show Prev/Next Arrows  | Yes                   |  
| Duration               | 4                     |  
| Disable Ribbons        | Yes                   |  

#### Homepage Slider Products

| Option                               | Setting                 |  
| :----------------------------------- | :---------------------- |  
| Filter Products By                   | Recently Added Products |  
| Number of Products                   | 4                       |  
| Truncate Product Titles/Descriptions | Truncate On             |  
| Max Titles Length                    | 350                     |  
| Max Descriptions Length              | 60                      |  
| Image Size                           | 250                     |  
| Randomize Products                   | Off                     |  

#### Category Slider Products

| Option                               | Setting                 |  
| :----------------------------------- | :---------------------- |  
| Filter Products By                   | Recently Added Products |  
| Number of Products                   | 4                       |  
| Truncate Product Titles/Descriptions | Truncate On             |  
| Max Titles Length                    | 30                      |  
| Max Descriptions Length              | 130                     |  
| Hide Description                     | No                      |  
| Image Size                           | 230                     |  
| Randomize Products                   | On                      |  

#### Homepage Slide #1 Custom Content

| Option                   | Setting               |  
| :----------------------- | :-------------------- |  
| Slide #1 Title           | Integrated Extensions |  
| Use Image as Background  | Yes                   |  
| Slide #1 Button Text     |                       |  
| Slide #1 Button/Link URL | #                     |  
| Full Size Link           | Yes                   |  

**Slide #1 Content**

~~~ .html
<p>A full width slider for your homepage, letting your showcase your products, or add custom slides. RokMage ContentSlider gives you the tools you need to get people's attention.</p>
~~~

#### Homepage Slide #2 Custom Content

| Option                   | Setting                |  
| :----------------------- | :--------------------- |  
| Slide #2 Title           | Homepage ContentSlider |  
| Use Image as Background  | Yes                    |  
| Slide #2 Button Text     |                        |  
| Slide #2 Button/Link URL | #                      |  
| Full Size Link           | Yes                    |  

**Slide #2 Content**

~~~ .html
<p>Hexeris comes with 12 of our Magento extensions, integrated seamlessly with the design. These allow you to customize your store with just a few clicks.</p>
~~~

### ProductScroller

Add a fully configurable, jQuery based, animated horizontal product scroller to the homepage and category pages.

#### General

| Option                              | Setting     |  
| :---------------------------------- | :---------- |  
| Enable Homepage Scroller            | No          |  
| Enable Category Scroller            | Yes         |  
| Prev/Next Function                  | Page        |  
| Enable Scroll Button Fade Animation | No          |  
| Truncate Product Titles             | Truncate On |  
| Max Titles Length                   | 32          |  
| Image Size                          | 160         |  
| Speed                               | 1           |  
| Circular                            | Loop On     |  
| Enable Autoscroll                   | No          |  
| Autoscroll Level                    | 3           |  
| Products Per Page                   | 6           |  
| Use Tooltip for Details             | Yes         |  
| Use Tooltip Animations              | No          |  
| Set Tooltip Offset                  | 10,2        |  
| Disable Ribbons                     | Yes         |  
 
#### Homepage Scroller Products

| Option             | Setting                |  
| :----------------- | :--------------------- |  
| Number of Products | 16                     |  
| Filter Products By | Highest Rated Products |  
| Randomize Products | Off                    |  

#### Category Scroller Products

| Option             | Setting           |  
| :----------------- | :---------------- |  
| Number of Products | 16                |  
| Filter Products By | Show All Products |  
| Randomize Products | Off               |  

### CategoryView

Add the ability to truncate product titles and descriptions, and switch between grid and list views without a page refresh.

#### General

| Option                               | Setting     |  
| :----------------------------------- | :---------- |  
| Enable Category View                 | Yes         |  
| Use 2 Column Layout                  | No          |  
| Truncate Product Titles/Descriptions | Truncate On |  
| Max Titles Length                    | 50          |  
| Max Descriptions Length              | 300         |  
| Default Products Layout              | Grid        |  

#### Product Filter Settings

| Option                          | Setting |  
| :------------------------------ | :------ |  
| Use Accordion Effect            | Yes     |  
| Product Filter Title            |         |  
| Open First Accordion by Default | No      |  
 
#### Category Product Image Settings

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
| Use 2 Column Layout | No      |  
 
#### Product Info Settings

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
| Equalize Tab Heights       | No                     |  
| Upsell Columns             | 2                      |  
 
#### Product Image Settings

| Option                          | Setting                             |  
| :------------------------------ | :---------------------------------- |  
| Enable RokMage media view       | Yes                                 |  
| Resize product image background | No                                  |  
| Image background location       | default/rokmage-productview/images/ |  
| Small Image Width               | 260                                 |  
| Small Image Height              | 260                                 |  
| Large Image Width               | 800                                 |  
| Large Image Height              | 800                                 |  
| Thumbnail Width                 | 78                                  |  
| Thumbnail Height                | 78                                  |  
| Disable Zoomer                  | No                                  |  
| Enable Lightbox                 | No                                  |  
| Original Size Lightbox Images   | No                                  |  
| Use Overlaid Thumb Gallery      | Yes                                 |  
| Spacing Offset                  | 20                                  |  

### CmsCallouts

Add your left and right sidebar callout content directly from the admin - no need to touch any template or layout files. 

#### General

| Option                   | Setting |  
| :----------------------- | :------ |  
| Enable Left CMS Callout  | Yes     |  
| Enable Right CMS Callout | Yes     |  
 
#### Content

| Option              | Setting           |  
| :------------------ | :---------------- |  
| Left Callout Title  | Left CMS Callout  |  
| Right Callout Title | Right CMS Callout |  

**Left Callout Text** 

~~~
You can add your content here by going to Admin -> Config -> CmsCallouts -> Left Callout Text. You can also disable this box entirely.
~~~

**Right Callout Text**

~~~
You can add your content here by going to Admin -> Config -> CmsCallouts -> Right Callout Text. You can also disable this box entirely.
~~~

### FeaturedProducts

Define your featured products from the admin, using selected category, attribute, or multi-select product list. 

#### General

| Option                | Setting           |  
| :-------------------- | :---------------- |  
| Get Featured Products | Featured Category |  
 
#### Settings

| Option                    | Setting                                                                                                          |  
| :------------------------ | :--------------------------------------------------------------------------------------------------------------- |  
| Select Featured Category  | Root Catalog                                                                                                     |  
| Select Featured Attribute | featured                                                                                                         |  
| Select Featured List      | Select at least 6 'Featured' products from this list. Hold **ctrl** and click to multi-select (**cmd** on a Mac) |  
| Filter By Store Root      | No                                                                                                               |  

### ImageBorders

Use jQuery and CSS to style your product images, giving the ability to add any border or frame you desire. 

#### General

| Option               | Setting |  
| :------------------- | :------ |  
| Enable Image Borders | No      |  

### FooterBlock

Add product lists to the footer, a text box (for disclaimers etc), styled footer menu and Cart count linked to the modal cart viewer. 

#### General

| Option                         | Setting     |  
| :----------------------------- | :---------- |  
| Enable Footer Block            | Yes         |  
| Number of Items in Lists       | 6           |  
| Truncate Product Titles        | Truncate On |  
| Max Titles Length              | 22          |  
| Randomize Products             | Off         |  
| Show Recently Viewed in Footer | Yes         |  
 
#### Settings

| Option             | Setting                |  
| :----------------- | :--------------------- |  
| 1st Column Content | Recently Added List    |  
| 2nd Column Content | Highest Rated Products |  
| 3rd Column Content | Most Viewed Products   |  

**Text Block Content**

~~~ .html
<h3>Disclaimer</h3><p><strong>Important:</strong> This demo is purely for demonstration purposes and all the content relating to products, services and events are fictional and are designed to showcase a live shopping site. All images are copyrighted to their respective owners. This is not an actual store, only representative of one.</p><p><strong>You can edit this text by going to Admin -&gt; Config -&gt; FooterBlock -&gt; Text Box Content.</strong></p>
~~~

### TinyMCE

Enables the Tiny MCE editor for RokMage Extensions.

#### General

| Option                                 | Setting                |  
| :------------------------------------- | :--------------------- |  
| Enable Tiny MCE for RokMage Extensions | Yes                    |  

**Textareas to enable for**

~~~ .html
#homepage_grid_settings_welcome_msg, #homepage_grid_settings_grid_text, #content_slider_settings_custom_one_slide_one_content, #content_slider_settings_custom_two_slide_two_content, #content_slider_settings_custom_three_slide_three_content, #content_slider_settings_custom_four_slide_four_content, #cms_callouts_settings_leftcallouttext, #cms_callouts_settings_rightcallouttext, #footer_block_settings_first-custom-text, #footer_block_settings_second-custom-text, #footer_block_settings_third-custom-text, #footer_block_settings_text-box
~~~
