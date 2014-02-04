---
title: How to Reindex Data in Magento
description: Reindexing data can help your Magento site(s) run smoother, faster, and more reliably.
tags: [Indexing, Tutorial, Data]
breadcrumb: /magento:Magento/!basic:Basic/

---

Introduction
-----

Magento is all about data management. When you start adding categories, attributes, products, and other information to Magento, it occasionally needs to reindex that data in order to organize it in a way that makes it easier to use. 
Magento will occasionally alert you when information needs to be reindexed by displaying a message in your Admin Panel dashboard, just below the main menu. You can certainly run a reindex process without this notification, and probably should if you are changing a lot of information on the backend.

Some updates require reindexing proper to application. This requirement is in place in order to prevent the update from breaking key functionality in your site.

How to Reindex Data
-----

![][index]

The first step to reindexing your Magento site is to visit the **Index Management** menu by navigating to **Admin Panel -> System -> Index Management**. Here, you will see a list of Indexes present in your Magento install. A status column in this list lets you know which indexes are good to go (green) or indeed of reindexing (red). 

![][index2]

You can reindex data for individual indexes by clicking the orange **Reindex Data** link on the right-hand side of the index, or by selecting the index(es) using the checkbox to the left and clicking **Submit** on the **Reindex Data** option on the upper-right area of the list.

[index]: assets/index_management_1.jpeg
[index2]: assets/index_management_2.jpeg