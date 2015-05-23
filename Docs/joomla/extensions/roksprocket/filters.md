---
title: RokSprocket: Using Filters
description: A Guide to Using Filters in RokSprocket
breadcrumb: /joomla:Joomla/!extensions:Extensions/!roksprocket:RokSprocket

---

## Introduction

RokSprocket is capable of displaying content from a number of different content providers. Among them, Joomla and the Simple provider. The Simple content provider is a great way to create custom content specific to the module, but it isn't the only way to control what appears in the module.

Using filters to narrow down the content that appears in a specific RokSprocket module is a simple and easy way to control what appears in the module. They make it possible to create separate RokSprocket modules for your site's featured articles, a specific category, cherry-picked articles, and content that meets a specific set of requirements.

Filters can be as specific or as broad as you need them to be.

While not all content providers supported by RokSprocket use the same filters, the philosophy behind them remains the same. In this guide, we will go over the **Joomla** content provider, and how you can use filters to get the most out of RokSprocket.

## Add Specific Articles

![Filters](filter_1.jpeg)

The **Add Specific Articles** tool gives you the ability to cherry pick articles and have them display in the module. This is a great option if you want to have a specific article, or set of articles, appear in the module. New articles will not automatically be added, unless you have a filter added. When you add a filter, RokSprocket will pull articles that match the filter rules and display them in addition to the cherry picked articles set here.

## Add Filters

![Filters](filter_2.jpeg)

RokSprocket content filters are the primary method for adding content from a content provider (other than Simple). In order for content to appear in the **Filtered Article List**, a filter has to be set.

Filters have two variables that need to be set. The first is the filter type, and the second is the value by which the content is filtered. For example, you can filter articles that have titles (type) that contain (value) a specific word or phrase.

Here is a breakdown of the Joomla content provider's filter types and values.

| Type               | Values                                                                                                              |
| :-----             | :-----                                                                                                              |
| Title              | Contains, Begins With, Ends With, Is                                                                                |
| Alias              | Contains, Begins With, Ends With, Is                                                                                |
| Article Text       | Contains                                                                                                            |
| Published          | Yes, No                                                                                                             |
| Publish Up         | Within Last (# Days/Weeks/Months/Years), Exactly, Before, After, Today, Yesterday, This Week, This Month, This Year |
| Publish Down       | Within Last (# Days/Weeks/Months/Years), Exactly, Before, After, Today, Yesterday, This Week, This Month, This Year |
| Featured           | Yes, No                                                                                                             |
| Category           | (List of Categories)                                                                                                |
| Tag                | (List of Tags)                                                                                                      |
| Created Date       | Within Last (# Days/Weeks/Months/Years), Exactly, Before, After, Today, Yesterday, This Week, This Month, This Year |
| Last Modified Date | Within Last (# Days/Weeks/Months/Years), Exactly, Before, After, Today, Yesterday, This Week, This Month, This Year |
| Last Modified By   | (Select a User)                                                                                                     |
| Author             | (Select a User)                                                                                                     |
| Author Alias       | Contains, Begins With, Ends With, Is                                                                                |
| Rating             | Equals, Greater Than, Less Than, Is Not                                                                             |
| Hits               | Equals, Greater Than, Less Than, Is Not                                                                             |
| Language           | All, (List of Languages)                                                                                            |
| Access Level       | Public, Guest, Registered, Special, Super Users                                                                     |

![Filters](filter_3.jpeg)

Combining filters refines your article selection even further. For example, you can set the **Published** filter to **Yes** and all published articles will appear in the **Filtered Article List**. Then, if you add the **Title** filter and set it to articles that **Begin With "D"**, only published articles that have titles that begin with the letter "D" will appear.

## Sort Rules

Once you have the article filters in place, you will want to determine how articles are sorted. There are three modes of article sorting, **Automatic**, **Manual**, and **Random**. 

### Automatic Sort

![Filters](filter_5.png)

Automatic sorting uses the **Sort Rules** you select to sort articles automatically. If your RokSprocket module will have new content continuously rotating through it, this is likely to be the sorting method you will want to use.

Here is a breakdown of the types of automatic sorting, which you can set to sort either **ascending** or **descending**.

* Title
* Alias
* Category
* Ordering
* Created Date
* Last Modified Date
* Last Modified By
* Author
* Rating
* Hits

### Manual Sort

![Filters](filter_4.png)

Manual sorting is just as the name implies. You can click and drag articles in an order you wish to have them appear in the RokSprocket module. You can set new articles that are added after you perform your initial manual sort **before** or **after** the existing ones. A fall back sorting rule modeled after the automatic sorting can be created that applies to these new articles.

### Random Sort

![Filters](filter_6.png)

This is possibly the simplest sorting type. Selecting it will randomly display filtered articles. This is a useful function for small modules intended to introduce readers to random articles.
