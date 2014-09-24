---
title: Syndicate: Recreating the Demo - Content Top
description: Your Guide to Recreating Elements of the Syndicate Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/syndicate:Syndicate

---

Content Top Section
-----

![][demo]

:   1. **RokNewsFlash** [6%, 10%, se]
    2. **RokStories** [10%, 10%, se]
    3. **RokMicroNews** [38%, 10%, se]
    4. **RokMicroNews** [54%, 10%, se]
    5. **RokMicroNews** [70%, 10%, se]
    6. **Text** [86%, 10%, se]

Here is the widget breakdown for the Content Top section:

* RokNewsFlash
* RokStories
* RokMicroNews
* RokMicroNews
* RokMicroNews
* Text

#### RokNewsFlash, RokStories, and RokMicroNews

This area of the demo is made up of a RokNewsFlash, RokStories, and three RokMicroNews widgets. These plugins are considered legacy and no longer supported by RocketTheme. Many of their features and functionality have been integrated into [RokSprocket][roksprocket].

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<div class="imu-wrapper">
  <div class="box1 floatleft imu-banner468"><p class="imu-caption imu-banner60">468x60 IMU</p></div>
  <div class="box1 floatleft imu-banner120"><p class="imu-caption imu-banner60">120x60 IMU</p></div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Switch the **Widget Style** option to **Flush**.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_4.jpeg
[rokgallery]: ../../plugins/rokgallery/
[roksprocket]: ../../plugins/roksprocket/
