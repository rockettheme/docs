---
title: Diametric: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Diametric Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/diametric:Diametric

---

Bottom Section
-----
![][demo1]

Here's the widget breakdown for the Footer section:

* Text
* RokGallery

#### Text
The Text widget in the section is pretty simple and straightforward. You'll need to enter the following in the main text field.

~~~
<span class="paneltitle">Latest Pictures</span>
<span class="panelsubtitle">Powered by RokGallery</span>
~~~

Here is a breakdown of options changes you'll want to make to match the demo.

* Enter `nomarginbottom nopaddingbottom` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### RokGallery
This RokGallery widget utilizes RokBox to display images in a way that does not distract from the visual elements of the theme. RokBox is required for this feature to work.

Here's a breakdown of the widget options: 

| Option            |                    Setting |  
| :---------------- | -------------------------: |  
| Link Type         |  Link to RokBox Full Image |  
| Show Title        |                         No |  
| Show Caption      |                         No |  
| Sort By           |                      Order |  
| Sort Direction    |                  Ascending |  
| Slice Limit       |                         10 |  
| Gallery Style     |                       Dark |  
| Gallery Layout    |                Grid Layout |  
| Grid Columns      |                          5 |  
| Custom Variations | `nopaddingall nomargintop` |  

This will create the widget, but you'll need to actually build the gallery using RokGallery. We go into detail on [how to use RokGallery in our official guide][rokgallery].

[demo1]: assets/demo_5.jpeg
[rokgallery]: ../../plugins/rokgallery