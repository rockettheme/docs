---
title: Lumiere: Recreating the Demo: Special Features
description: Your Guide to Recreating Elements of the Lumiere Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lumiere:Lumiere

---

HTML5 Video in the Lumiere Header
-----
Lumiere, uses HTML5 to offer video functionality in the header, to create a dynamic and interactive user experience. 

Lumiere RocketLauncher is packaged with all videos and poster images included. All videos and poster images within this package or directory are the copyright of Downloops.com. They are licensed exclusively for use with the Lumiere template by RocketTheme Club Members. There is no right of modification, distribution or reuse with another template. 


#### Setting Up the Header Background

You can choose the background style you would like to use on the template manager.

1. Go to **Extensions** → **Template Manager** and click **rt_lumiere**.

2. There are two options for the background style, Image or Video Background. 

2. a. If you choose Image Background, then you can use the default template images or your own custom images, via RokGallery or Media Manager. The default template images are located at `<Joomla Root>/templates/rt_lumiere/images/backgrounds/` directory.

![][demo]

2. b. If you choose Video Background, then you can use the included videos and posters which are located at `<Joomla Root>/templates/rt_lumiere/videos/` directory. The Videos parameter comes with loop setting, pause and mute buttons, and the option to enable or disable the videos on mobile.

![][demo2]

If you don't want to use RocketLauncher and just want to install the standalone Lumiere template, the videos are not included. Just download the video files from [Lumiere Download Area][lumiere], unpack it and upload the videos to <Joomla Root>/templates/rt_lumiere/videos/ directory. You could also upload your own videos in this directory.


#### HTML5 Video Format

Lumiere uses HTML5 `<video>` element to to embed the video as the header background. There are 3 supported video formats for the element, MP4, WebM, and Ogg. Currently, Firefox, Chrome, Safari, Opera, and Internet Explorer 9 support this element.

![][demo3]


#### Video Conversion

If you don't have any supported format for your videos, you can use video conversion tool to convert your videos. On Lumiere, we use [Miro Video Converter][miro] to convert and compress the videos. It offers a beautiful, simple way to convert almost any video to MP4, WebM, Ogg Theora, as well as batch conversion, custom sizing, and more!

![][demo4]

Please visit MiroVideoConverter.com to download the converter. It's available for Mac and Windows, and it's 100% FREE and open-source.


#### MIME Types for Video Formats

As mentioned above, HTML5 video uses MP4, WebM and Ogg formats. While most servers have been configured for MP4, some servers will not run WebM and Ogg well if the mime types are not configured well.

In case you couldn't see your video plays, and if you are using Apache webserver you will need to add the following code to an .htaccess file in the directory where your video files are located. 

LINE NUMBER ON/OFF | EXPAND/CONTRACT | SELECT ALL
 
AddType video/ogg .ogv
AddType video/mp4 .mp4
AddType video/webm .webm


You can download the following htaccess.txt, rename it to .htaccess, and put it inside your video folder.
 htaccess.txt
(70 Bytes) Downloaded 474 times


For MAMP users, you can edit the /Applications/MAMP/conf/apache/mime.types by adding the following at the bottom. Please create a backup of that file (mime.types) first before editing it.
LINE NUMBER ON/OFF | EXPAND/CONTRACT | SELECT ALL
 
video/ogg                   ogv
video/mp4                   mp4
video/webm                  webm

![][demo5]

For XAMPP users, you can edit the /XAMPP/apache/conf/mime.types by adding the following. Please create a backup of that file (mime.types) first before editing it.
LINE NUMBER ON/OFF | EXPAND/CONTRACT | SELECT ALL
 
video/ogg                   ogv
video/mp4                   mp4
video/webm                  webm

![][demo6]

If you have any questions regarding this tutorial, please post in [Lumiere Forum][forum].

[demo]: assets/video_1.jpg
[demo2]: assets/video_2.jpg
[demo3]: assets/video_3.jpg
[demo4]: assets/video_4.jpg
[demo5]: assets/video_5.jpg
[demo6]: assets/video_6.jpg
[lumiere]: http://www.rockettheme.com/joomla-downloads/club/3333-lumiere
[miro]: http://www.mirovideoconverter.com/
[forum]: http://www.rockettheme.com/forum/index.php?f=703&rb_v=viewforum