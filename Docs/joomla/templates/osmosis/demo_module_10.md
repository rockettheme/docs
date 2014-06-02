---
title: Osmosis: Recreating the Demo - SidePanel
description: Your Guide to Recreating Elements of the Osmosis Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/osmosis:Osmosis

---

SidePanel
-----

![][demo]

:  1. **Logo** When toggled on, the site logo appears dynamically as you scroll down the page. [6%, 20%, se]
  2. **SidePanel Menu** When toggled on, this menu appears as you scroll down the page. [15%, 20%, se]
  3. **Custom HTML - FP SidePanel Info** This is a **Custom HTML** module assigned to the **sidepanel** position. [35%, 20%, se]
  4. **Custom HTML - FP Sidepanel Social Icons** This is a **Custom HTML** module assigned to the **sidepanel** position. [83%, 20%, se]

1. **Logo**: When toggled on, the site logo appears dynamically as you scroll down the page.
2. **SidePanel Menu**: When toggled on, this menu appears as you scroll down the page.
3. **[Custom HTML - FP SidePanel Info](demo_module_10.md#fp-sidepanel-info)**: This is a **Custom HTML** module assigned to the **sidepanel** position.
4. **[Custom HTML - FP Sidepanel Social Icons](demo_module_10.md#fp-sidepanel-social-icons)**: This is a **Custom HTML** module assigned to the **sidepanel** position.

The SidePanel featured in Osmosis gives you the ability to dynamically reveal modular content along the side of the page. In the home page of our demo, we used a collection of modules and features that appear and/or move as you scroll down the page.

The SidePanel position can be home to any module type. Any modules you assign to the position will be static, while you have the option of adding the logo and sidepanel menu as dynamic elements that appear as you scroll down the page. This ensures that your visitors will be able to see your logo and access the main menu from anywhere on the page.

![][sidepanelsettings]

You can turn the SidePanel on and off via the template settings menu. You can reach these settings by navigating to **Administrator > Extensions > Template Manager > Osmosis > Style** and toggling the **SidePanel Style** setting.

This is also where you can turn the **SidePanel Logo** and **SidePanel Menu** on or off. By turning them on, they will appear as dynamic elements once you scroll far enough down the page.

### Static Modules

There are two static modules assigned to the **SidePanel** position. Both are **Custom HTML** module types.

#### FP SidePanel Info

This is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

| Option     | Setting             |
| :--------- | :---------          |
| Title      | `FP SidePanel Info` |
| Show Title | Hide                |
| Position   | sidepanel           |
| Status     | Published           |
| Access     | Public              |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<span>You can publish any module type into the sidepanel position.</span>
~~~

### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `box2`      |

#### FP Sidepanel Social Icons

This is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

| Option     | Setting                     |
| :--------- | :---------                  |
| Title      | `FP Sidepanel Social Icons` |
| Show Title | Hide                        |
| Position   | sidepanel                   |
| Status     | Published                   |
| Access     | Public                      |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-facebook-square"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-twitter-square"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-google-plus-square"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-flickr"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-github-square"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-linkedin-square"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-pinterest-square"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-instagram"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-tumblr-square"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-trello"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-xing-square"></span></a>
<a href="#" class="fp-sidepanel-social-icon"><span class="fa fa-skype"></span></a>
~~~

### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

| Option              | Setting                               |
| :----------         | :----------                           |
| Module Class Suffix | `rt-sidepanel-bottom fp-sidepanel-03` |

[demo]: assets/demo_10.jpeg
[demo2]: assets/demo_10a.jpeg
[demo3]: assets/demo_10b.jpeg
[demo4]: assets/demo_10c.jpeg
[sidepanelsettings]: assets/sidepanelsettings.jpeg
[positions]: positions.md
