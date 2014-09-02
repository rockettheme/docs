---
title: Nuance: Recreating the Demo - About Nuance
description: Your Guide to Recreating Elements of the Nuance Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/nuance:Nuance

---

About Nuance
-----

![][demo]

We used a **Custom HTML** module to create this area of the front page. You will find the settings used in our demo below.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :----------    |
| Title       | `About Nuance` |
| Show Title  | Show           |
| Position    | bottom-a       |
| Status      | Published      |
| Access      | Public         |

### Custom Output

~~~ .html
<hr />
<div><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Basic support for third party Content Control Kit (CCK) extension, K2</a></div>
<div><small><i class="fa fa-file-text-o"></i> Separate disablable CSS file</small></div>
<hr />
<div><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">Disable the Mainbody or Component areas on a per menu item basis</a></div>
<div><small><i class="fa fa-file-text-o"></i> Template manager toggles</small></div>
<hr />
<div><a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111">A separate, togglable LESS file for demo frontpage specific CSS</a></div>
<div><small><i class="fa fa-file-text-o"></i> Optimize page load size</small></div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting       |
| :----------         | :----------   |
| Module Class Suffix | `fp-bottom-a` |

[demo]: assets/demo_11.jpeg
[demo2]: assets/demo_11a.jpeg
[demo3]: assets/demo_11b.jpeg
[demo4]: assets/demo_11c.jpeg
