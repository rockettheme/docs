---
title: How Joomla Works
description: Your Guide to Understanding Joomla
breadcrumb: /joomla:Joomla/!platform:Platform/!understanding.md:How Joomla Works

---

Joomla is Modular
-----

Joomla is a modular content management system. It is not limited to just what comes with the initial package. You can expand on it, customize it, and swap components with a few clicks of the mouse. It is because of this extensive amount of control that it can be a bit overwhelming to someone attempting to navigate through the administrative side for the first time. In this page, we will attempt to tackle some of the most common Joomla components and how they relate to one-another.

Some of the terms used in the Joomla ecosphere are shared with other CMS environments while others are purposely differentiated in order to maintain some separation between platforms in order to avoid confusion. For example, a template in Joomla is very similar to a theme in WordPress.

If a Joomla site were to be compared to a car, then Joomla itself would be the engine. Through a series of PHP scripts and commands (frame, cables, and wires), it pulls the data (fuel) from the database (fuel tank) requested by the user (driver), which allows the car to move.

The site's template would be the body of the car, defining its look and feel, as well as providing much of the area in which the driver operates. In many ways, it also makes up the steering wheel and gear shift, allowing the user to interact directly with the site and tell it what to do.

Plugins and modules make up additional parts like the gear shift, glove box, and mirrors. They are often helpful, and potentially essential for carrying out operations requested by the user.

Components, which are a specific type of extension, would be the materials that went into making the engine and other vital system components.

All of these components work together to ensure that your site looks and operates the way it is supposed to. If everything is set up correctly, it should be a consistent experience whether you have one visitor, or one thousand.

The Two Sides of Joomla
------

Joomla is not just a platform on which content  is displayed. It is also an incredible platform for site management and content creation. It is because of this dual-purpose nature of Joomla that much of its components are actually split between the visitors area of your site and the **Administrator** area.

Each part of Joomla has its own template. This is due to the fact that both the visitor area and the administrative areas can be customized to meet the needs of visitors and site managers alike. There are a number of different Administrator interfaces out there for you to choose from, just as there are thousands of  Joomla frontend templates for you to pick from.

The Administrator interface gives you the ability to customize your site's layout, create and manage content, upload extensions, and more. It is the primary control interface for the entire site, and as such should only be accessible by individuals you absolutely trust not to break or harm anything. This is not a place for visitors. They are generally going to stick to the frontend for everything they need to do in your site, including potentially adding articles, making comments, or submitting answers to forms.

### What is an Extension?

An extension is anything that extends the functionality of your Joomla site. It is usually a software package you can install directly to your site using the Administrator Extension Manager tool. This could be anything that is not included in the core Joomla platform. Templates, modules, plugins, and other components fall under this definition.

#### What is a Module?

Modules are extensions often used to enhance or otherwise add features and functionality to the frontend and/or backend of your site. They are used for page rendering, and are often represented as areas of a page intended to perform a specific function or duty.

A login module may allow users to access their account within your Joomla site while a weather module displays the weather in the reader's area as a value-add to the page itself. Modules can take virtually any number of shapes and sizes, but they are typically placed within a specific position in the site's template.

Modules can range from simple blocks of text to complex site components that display content from multiple sources and/or offer some level of control over the user experience to the visitor. You can assign modules to specific pages, or restrict their ability to display in various circumstances. They are flexible by nature and make up a key part of almost any Joomla site.

Templates typically have module positions assigned in order to make assigning a specific module to a particular area of the page easier on the user. For example, assigning a module to position `Header-a` will place it in the upper-left area of the page, depending on the layout permitted by the theme. If you want to move the module to the bottom-right area of the page, you can assign it to a position that is located in that area.

The Gantry framework provides some added control over the positioning of modules within a Gantry-supported template. You can [find out more about positioning modules here][modules].

#### What is a Template?

A template is an extension, much like a module, which has the greatest impact on how your site looks. It sets the font, color, background, layout, and just about any other major visual aspect of your site's design.

There are frontend and backend templates available. The frontend template affects the portion of your site visitors see, while the backend template changes the Administrator area. Joomla comes with several templates for both the visitor and Administrator areas of your site, though you can also build your own, or download a template from a third-party, like [RocketTheme][rockettheme].

#### What is a Plugin?

A plugin is a type of Joomla extension which adds functions associated with trigger events. When a trigger event occurs, any active plugins associated with that event fire, allowing you to further extend the functionality of your site. There are many trigger events included with Joomla, though an extension can add custom events of its own.

The majority of the plugins available impact behind-the-scenes activity to Joomla and are virtually invisible to the user. Google Analytics scripting is a popular example of a useful plugin. By installing a plugin to add the Google Analytics code to every page as it loads, you do not have to edit the template source files to do so.

You can find out more about installing and managing plugins [here][plugins].

[rockettheme]: http://www.rockettheme.com
[plugins]: extensions.md
[modules]: http://gantry-framework.org/documentation/joomla/configure/layouts.md