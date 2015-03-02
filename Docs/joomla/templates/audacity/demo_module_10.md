---
title: Audacity: Recreating the Demo - Breaking News
description: Your Guide to Recreating Elements of the Audacity Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/audacity:Audacity

---

Breaking News
-----

![demo](assets/demo_10.jpeg)

We used a **RokSprocket** module with the **Lists** layout to make up this area of the front page. You will find the settings used in our demo below.

We utilized the **Simple** Content Provider, linking each item in the RokSprocket module to an article. You can find examples of the **Simple** items used in this module in the **Filtered Article List** section below.


### Details

![demo2](assets/demo_10a.jpeg)

| Option           | Setting         |
| :----------      | :----------     |
| Title            | `Breaking News` |
| Show Title       | Show            |
| Access           | Public          |
| Position         | bottom-a        |
| Status           | Published       |
| Content Provider | Simple          |
| Type             | Lists           |

### Filtered Article List

#### Article 1

| Option | Setting |
| :----- | :------ |
| Image  | None    |
| Link   | Custom  |

**Title**

~~~ .html
<span>The RocketLauncher <span class="hidden-tablet">package </span>installs a demo <span class="hidden-large">copy</span><span class="visible-large">equivalent</span> onto your site</span>
~~~

**Description**

~~~ .html
<span>A default Joomla package with custom sample data and images from the demo.<span class="visible-large"> Content images are replaced with sample tiled substitutes due to copyright.</span></span>
~~~

#### Article 2

| Option | Setting |
| :----- | :------ |
| Image  | None    |
| Link   | Custom  |

**Title**

~~~ .html
<span>Adobe&reg; Fireworks PNG sources are provided<span class="hidden-tablet"> to facilitate customization</span></span>
~~~

**Description**

~~~ .html
<span>Editable and layered image sources are provided, alongside any necessary fonts<span class="visible-large">, such as for the logo or other elements</span>.</span>
~~~

#### Article 3

| Option | Setting |
| :----- | :------ |
| Image  | None    |
| Link   | Custom  |

**Title**

~~~ .html
<span>Custom notice pages with integrated template styling<span class="visible-large"> for offline and error displays</span></span>
~~~

**Description**

~~~ .html
<span>Audacity has a custom offline page with an optional countdown feature<span class="visible-large"> to inform visitors of when your site will launch</span>.</span>
~~~

### Layout Options

![demo3](assets/demo_10b.jpeg)

| Option              | Setting     |
| :----------         | :---------- |
| Theme               | Default     |
| Display Limit       | 6           |
| Collapsible Preview | Enable      |
| Preview Length      | ∞           |
| Strip HTML Tags     | No          |
| Previews Per Page   | `5`         |
| Arrow Navigation    | Show        |
| Pagination          | Show        |
| Autoplay            | Disable     |
| Autoplay Delay      | 5           |
| Image Resize        | Disable     |

### Advanced

![demo4](assets/demo_10c.jpeg)

| Option              | Setting                       |
| :----------         | :----------                   |
| Module Class Suffix | `fp-roksprocket-lists-bottom` |
