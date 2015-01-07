---
title: Understanding Responsive Support Classes
description: Your guide to using responsive support classes in RocketTheme themes.
breadcrumb: /wordpress:WordPress/!start:Start/!responsive_support_classes:Responsive Support Classes

---

Another useful feature available, via Bootstrap, is the collection of responsive utility classes that can be used to help tweak layouts by providing a simple method of showing or hiding widgets. Insert the following custom variations into your widget settings to show/hide a widget for a particular mode.

|       Class       | Phones (<= 767px) | Tablets (768-959px) | Desktops (960-1199px) | Desktops (>= 1200px) |
| :---------------- | :---------------- | :------------------ | :-------------------- | :------------------- |
| `visible-phone`   | **Visible**       | Hidden              | Hidden                | Hidden               |
| `visible-tablet`  | Hidden            | **Visible**         | Hidden                | Hidden               |
| `visible-desktop` | Hidden            | Hidden              | **Visible**           | **Visible**          |
| `visible-large`   | Hidden            | Hidden              | Hidden                | **Visible**          |
| `hidden-phone`    | Hidden            | **Visible**         | **Visible**           | **Visible**          |
| `hidden-tablet`   | **Visible**       | Hidden              | **Visible**           | **Visible**          |
| `hidden-desktop`  | **Visible**       | **Visible**         | Hidden                | **Visible**          |
| `hidden-large`    | **Visible**       | **Visible**         | **Visible**           | Hidden               |

As an example, if you wish to have a login widget appear on desktop and tablet devices, but not necessarily phones, you can place `hidden-phone` in the **Custom Variations** field in the widget's settings. This will allow the widget to remain visible on any device displaying the page at a width above 768, allowing you to maintain the look you wish to achieve across multiple device types.

This feature enables you to make the most of your site without sacrificing its clean appearance due to limitations in screen size.