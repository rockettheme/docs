---
title: Add a Module to an Article
description: A Quick Tutorial for Adding Modules to Articles in Joomla 2.5 and 3.x
breadcrumb: /joomla:Joomla/basic:Basic Tutorials/

---

Adding modules to articles is a useful way to get around the limitation of positions in relation to the article body. It's possible to put a module in the midst of an article's mainbody content. Here are two ways to accomplish this.

**loadposition**

By inserting the `{loadposition xxx}` command into an article, you can cause Joomla to render the module that has been preassigned to a non-template supported position.

You can do this be creating a module and assigning it to a position that is not actively supported by the current template. For example, if your template supports positions 1-10, you could assign this module to position 11, or opting to create a position value entirely different, such as a descriptive word indicating what this module is going to be used for. In this case, we'll stick with position 11.

Alternatively, you can assign this module to all **Menu Items**. Doing so does not cause the module to render by itself, but does make it available when the loadposition or loadmodule command is called.

In this example, you would add `{loadposition 11}` into your article body. The module will appear at full width of the article, with text appearing above and/or below the module, depending on where you placed the shortcode.

**loadmodule**

The `{loadmodule xxx}` command is an alternative that works by finding the first module type that matches what you've placed instead of `xxx` and injects it into the article body wherever you put the code.
