---
title: RokBooster
description: Your Guide to Using RokBooster for Joomla
breadcrumb: /joomla:Joomla/extensions:Extensions/!rokbooster:RokBooster

---

Introduction
-----
Increase the speed of your site by enabling the RokBooster plugin. This advanced extension will compress and combine your CSS and JavaScript into as few files as possible each. RokBooster can also convert page and background images to data URLs for increased performance.

In the chart below, we detail some of the performance increases possible with RokBooster using our free template, [Afterburner2][afterburner]:

![][RokBooster]

RokBooster can dramatically reduce the number of HTTP calls a browser has to make, and sending those compressed files GZipped means your pages will load faster with less load on your server.

Looking beyond Afterburner2, RokBooster can benefit just about any updated Joomla site. Here, we'll break down how exactly RokBooster can benefit your site. For the interest of comparison, we've tested with both Afterburner2 and our default Gantry template.

|          | Afterburner2* | + RokBooster | Gantry | + RokBooster |  
| :------- | :------------ | :----------- | :----- | :----------- |  
| Requests | 12            | 5            | 18     | 7            |  
| Time     | 428ms         | 342ms        | 555ms  | 375ms        |  
| Size     | 510KB         | 173KB        | 640KB  | 219KB        |  

>> *All statistics use Afterburner2 in 960Fixed mode.

**Requests**: Requests are the number of items that are loaded on a page. Reducing the number of requests improves performance. With RokBooster enabled, which we recommend once you have finished development, the total requests are 5: 1 CSS, 1 Javascript, 1 Font, 1 Image and Text/HTML data; an incredibly low count.

**Time**: The time, in milliseconds, for the page to finish loading all requests. In local tests, the template with RokBooster enabled is about 1/3 of a second.

**Size**: The size, in kilobytes, of all requested items. Smaller file sizes lead to speedier loading. The necessary files have been optimized to reduce their overall footprint, for example, the logo is only 1.5KB, the only image file loaded by Afterburner2. With RokBooster enabled, the footprint is 173KB which is a significant reduction.

### What Does RokBooster Do?

RokBooster takes what would otherwise be a bulky and complex site and compresses it down to make it lighter and easier to serve. 

Think of your site as a grocery store. All of the individual files that go into it are items in that store. Your visitors will have a hard time shopping if they have to grab every item on the shelf with each trip. RokBooster acts like a shopping cart, making it possible to easily and quickly grab the items you need and get out the door. It groups useful data together from various different sources to make it easier for your browser to download and render.

When you're working with a template that has many different built-in features, it could be pulling from a great deal of different CSS and JavaScript sources. This means your visitor's browsers are making many different independent requests which can drag down load times. 

This is where RokBooster comes in. It combines and compresses CSS and JavaScript into as few files as possible. This is done using GZip compression, which is used to send CSS and JavaScript files. 

#### CSS
With RokBooster, all of these separate CSS files are combined into as few files as possible. This reduces the number of requests, and optimizes page loading. If you're using a template with several different header, body, footer, background, etc. options to choose from, there's no sense in having to load CSS calls to components and options you aren't actively using at the time.

#### JavaScript
The same goes for JavaScript files. Sites that feature a lot of functionality are often heavily reliant on scripts and other miscellaneous blocks of code to create a smooth and useful user experience. Unfortunately, this results in an increase in individual requests to the site, increasing the size and frequency of data that has to be transferred with each page view. RokBooster compresses and combines these files in order to streamline the process. The visitor can experience faster load times due, in part, to the browser having to download and render less individual blocks of data.

#### Images
Images are another area that RokBooster comes in handy. It's capable of converting inline and background images below a certain file size into data so they are loaded faster and smoother. This data is placed directly into the HTML, replacing the call to an external file.

### A Note About RokBooster as a Solution
RokBooster was created to help solve an issue facing site administrators responsible for sites in a variety of different situations. Whether your site is hosted on multiple servers and/or CDNs internationally, or sitting on a shared server hosted by a busy hosting provider, its intention is to assist in streamlining your site by reducing the number of requests made by visitors, compressing CSS and JavaScript, and the optimization of image files.

It's important to note that RokBooster is just one piece of the optimization puzzle. Site speed ranking tools like YSlow and Google PageSpeed don't tell the full story of your site's real-world experience with users. While these rankings are often considered important for SEO (some search engines consider site speed in page rank) there is much more you can do to improve your site that a single extension can't do.

Optimizing your MySQL database, finding a good hosting provider and spending the extra money for a dedicated server, keeping your sites free of extension crawl, reducing the amount of information you pull from external sources for each page view, and implementing site caching are just some of the ways you can incrementally improve site performance for your visitors. 

RokBooster is there to assist in optimization where it can. While useful, this is still no magic bullet. It's just one part of a larger optimization strategy.

Requirements
------------
RokBooster has the following requirements in order to operate:

* Joomla 2.5 or 3.x - ensure you are using the latest version.

>> NOTE: Internet Explorer 7 and before are not supported

>> ALSO: Gzip must be installed on your server and enabled in PHP in order to function.

Key Features
------------
* Combine and compress CSS and JavaScript into as few files as possible
* GZip compression used to send CSS and JavaScript files
* Compress In-line CSS and JavaScript
* Compress Inline and Background Images
* Customizable cache timeout
* Background rendering, so initial file processing won't slow your users down
* Full page scan allows for non-header JavaScript and CSS to be included
* Ability to ignore specific CSS and JavaScript files
* Configurable permissions settings
* Exempted individual CSS/JS files
* Option to ignore partial URLs and Paths for JS and CSS
* Page-specific exemptions

>> NOTE: If your site's CSS goes blank when you activate RokBooster, there is a permission problem on your server. Please change the Cache File Permissions settings in the Advanced settings inside the RokBooster plugin settings.

How to install
--------------
Installing RokBooster takes just a matter of few minutes.

The first thing you’ll need to do is [download][download] the latest version of RokBooster. The package you will download contains everything to get RokBooster up and running and it is compatible with both Joomla 2.5 and Joomla 3.x. It does not need to be uncompressed. 

Once you've downloaded the package, go into the Joomla Administrator and:

From Joomla 2.5 and 3.x:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `RokBooster.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

>> NOTE: For additional information on installing extensions, visit our detailed extensions installation guide located [here][install].

Once installation is complete, a message highlighted in green should indicate its successful completion.

### Accessing the Plugin Page
You can access the RokBooster configuration page by navigating to **Extensions -> Plugin Manager**. In the list, you will find **System - RokBooster**. Click the name in order to enter RokBooster's Plugin Manager. The plugin needs to be set to **Enabled** to operate.

[featured]: assets/roksprocket-layout.jpeg
[download]: http://www.rockettheme.com/extensions-downloads/club/2937-rokbooster
[install]: ../../platform/extensions.md#how-to-install-an-extension
[rokbooster]: assets/rokbooster.jpeg
[details]: assets/RokStock_details.jpeg
[afterburner]: https://www.rockettheme.com/joomla-templates/afterburner2
