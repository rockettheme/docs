---
title: How to Create a Template Override
description: Your Guide to Creating a Template Override in Joomla
breadcrumb: /joomla:Joomla/!basic:Basic/!how_to_create_a_template_override:How to Create a Template Override

---

Introduction
-----

Joomla has an integrated tool that enables you to set base settings for your template, and duplicate them to create overrides based on the primary (referred to as Master in Joomla) template style. 

These styles can be assigned to specific Menu items, such as your blog posts or home page, giving them a unique look and/or module arrangement for these pages.

In this quick guide, we will go over the steps needed to create and customize a template style.

How to Create a New Style Override
------

Creating a new override style is very easy. All you need to do is navigate to the **Templates Manager** by going to **Admin -> Extensions -> Templates Manager**, and duplicate a base template set to create the override.

![][override1]

:   1. **Checkbox** By clicking the checkbox next to a template style, you can choose to edit, duplicate, delete, or set options for it. [67%, 22%, se]
    2. **Duplicate** This button will create a duplicate style based on the one selected. This allows you to quickly build an override. [20%, 20%, se]

In the example pictured above, we have **Nebulae** installed and activated. 

By selecting the checkbox next to the **Master** instance and selecting **Duplicate**, you can create a duplicate set of template settings based on the default set.

How to Edit the New Override
-----

![][override2]

Once the duplicate set has been created, you can edit its name and manage settings by clicking on the newly-created duplicate and/or selecting the checkbox and hitting **Edit**.

![][override3]

:   1. **Checkbox** Selecting this checkbox indicates that you wish to change a setting from its default. This creates an override that is applied to any page this style is assigned to. [72%, 7%, se]

Now, you can override specific settings to change them from the master. In the pictured example, we adjusted the module position settings for the Top module position. 

By checking the checkbox next to the **Top Positions** row and adjusting the setting, we have told Joomla that for any page this override is assigned, the Top module positions will be displayed at a ratio of 7 to 5, rather than the default setting used elsewhere.

[override1]: assets/override_1.jpeg
[override2]: assets/override_2.jpeg
[override3]: assets/override_3.jpeg