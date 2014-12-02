---
title: Nuance: Recreating the Demo - Main Top
description: Your Guide to Recreating Elements of the Nuance Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/nuance:Nuance

---

Main Top Section
-----

![][demo]

Here is the widget breakdown for the Main Top section:

#### RokSprocket (Grids)

You will need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you will need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Grids** widget.

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation](../../plugins/roksprocket/).

##### Simple Provider

We used the **Simple Provider** to enable us to create custom RokSprocket content without having to create separate articles or pages to do so. Here are the details of one of the **Simple Items** in the **Featured Article List**.

| Option      | Setting     |
| :---------- | :---------- |
| Title       | `Grids`     |
| Link        | None        |

**Description**

~~~ .html
<span class="rt-grids-heading1"><a href="#">A content block layout <span class=
"hidden-tablet">with dynamic distribution</span>.</a></span><span class=
"rt-grids-heading2"><span>Present with images, text overlays, content or with
all. <span class="visible-large">Grids is configurable up to 10 columns and has
one built-in theme.</span></span></span><span class=
"rt-grids-heading3"><a class="largemarginright" href="#"><i class=
"fa fa-quote-right fa-fw"></i> Read More</a> <a href="#"><i class=
"fa fa-cloud-download fa-fw"></i> Download</a></span>
~~~

Here is a look at the **Grids Layout Options** for this widget.

| Option           | Setting     |
| :----------      | :---------- |
| Theme            | Basic       |
| Display Limit    | ∞           |
| Columns          | 3           |
| Preview Length   | ∞           |
| Strip HTML Tags  | No          |
| Arrow Navigation | Show        |
| Animation        | Fade        |
| Autoplay         | Disable     |
| Autoplay Delay   | 5           |
| Image Resize     | Disable     |

You can set the RokSprocket filters to include any category, specific posts, or otherwise you would like to have featured in this widget.

Once you have created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you have done this, you will need to complete the following.

* Enter `RokSprocket[span class="rt-title-tag"]Multiple Layouts & Themes[/span]` in the **Title** field.
* Select your RokSprocket Headlines widget in the **Choose Widget** field.
* Enter `fp-roksprocket-grids-maintop rt-title-center rt-large-title` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[demo]: assets/demo_5.jpeg
[roksprocket]: ../../plugins/roksprocket/
