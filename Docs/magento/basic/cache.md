---
title: How to Work with Cache in Magento
description: Disabling the caching feature in Magento is a great first step during initial setup.
tags: [Cache, Tutorial, Setup]
breadcrumb: /magento:Magento/!basic:Basic/

---

Introduction
-----

Magento uses cache in many different ways, so you'll notice several various caching features that you can enable or disable. If you are working on customizing your site and getting it set up, it's best to **disable** all the cache settings. This allows you to work and check your site routinely without having to wait for cache to catch up with any changes you've made.

![][cache]

:	1. **Cache Management** This menu option brings you to Magento's primate Cache Management menu. [63%, 37%, se]

You can access the primary cache controls by navigating to **System -> Cache Management**. 

Enabling, Disabling, and Refreshing the Cache
-----

![][cache2]

:	1. **Flush Magento Cache** This option flushes the main cache items for page display purposes. [13%, 71%, se]
	2. **Flush Cache Storage** This option is a more complete cache flush that includes items in Magento's cache directory. [13%, 84%, se]
	3. **Flush Catalog Images Cache** Refreshes cache related to catalog images. [76%, 6%, se]
	4. **Flush Javascript/CSS Cache** Deals with page styling cache. [83%, 6%, ne]

There are four big buttons located above and below the itemized list in the main **Cache Management** menu. It's recommended that you work with the individual line items listed as a first step in troubleshooting before hitting the larger buttons (detailed below).

If you want to disable your site's cache entirely, simply check all of the boxes listed to the left of this itemized menu and select **Disable** in the **Actions** dropdown. You can repeat the same process to enable the cache by selecting **Enable**, instead.

The **Refresh** option flushes the cache for all of these components while the larger **Flush Magento Cache** button may not actually fully flush all aspects of Magento's cache. If you're troubleshooting an issue, we recommend doing the line-item refresh prior to hitting the **Flush Magento Cache** and **Flush Cache Storage** buttons.

#### Flush Magento Cache

This button deals with the main cache items for page display purposes. It can safely be used if you want to refresh your page. 

#### Flush Cache Storage

This option is a more complete cache flush and includes more items in Magento's cache directory.

#### Flush Catalog Images Cache

The **Flush Catalog Images Cache** option is just what it says. It deals with the catalog images. If you are changing images on products, and not seeing the new images on your site, you can try flushing this and refreshing your page.

#### Flush Javascript/CSS Cache

This option involves a lot of the page styling cache and can be flushed when you are making updates. It's not needed regularly, but it's best to do if you want to see any recent changes.

Flat Catalog Data
-----


Flat Product Data
-----


Merge CSS
-----


Merge JS
-----



[cache]: assets/cache_1.jpeg
[cache2]: assets/cache_2.jpeg