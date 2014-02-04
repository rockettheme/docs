---
title: ProductVideo
description: Your Guide to the ProductVideo Extension for Magento
tags: [Extension, Plugin, ProductVideo, Requirements, Setup, Installation]
breadcrumb: /magento:Magento/!extensions:Extensions/!productvideo:ProductVideo

---

Introduction
-----

The ProductView module can also show the output of another module, ProductVideo. This adds a page to the Product Information section of the admin (Catalog->Manage Products) that allows you to add a link for a product video, either using Google Videos, Youtube, or self hosted videos (using Flowplayer).

Once added, for YouTube and Google videos the thumbnail will be automatically created, with the video opening in a modal window. If you choose to host the videos yourself, they can be played using Flowplayer (www.flowplayer.org). If using this option, you must download the Flowplayer files and add them to the root of your site, as follows:
`magento/flowplayer/`

Then, you must manually create the thumbnails, naming them the same as the flv video files, and add them to the same folder – which should be created as follows:
`magento/flowplayer/videos/`

Setup
-----

The video links should be added in the following format:

YouTube YouTube – the full URL link from the “share” section. It should be in the following format:

~~~ .html
http://www.youtube.com/watch?v=E8bsVsb_9ug`
~~~

Google Video Google Video - the full embed code, found by expanding the "Embed video" link. It should be in the following format:

~~~ .html
<embed id=VideoPlayback src=http://video.google.com/googleplayer.swf?docid=1565217884095750297&hl=en&fs=true style=width:400px;height:326px allowFullScreen=true allowScriptAccess=always type=application/x-shockwave-flash> </embed>
~~~

Flowplayer self hosted Flowplayer self hosted - the video name, for example `product_video.flv`. You will have to upload your own video thumbnail - these should be named the same as the video (for example `product_video.jpg`), and be in either gif or jpg format (with dimensions 480px wide x 360px high).

How to Install
-----

You can download a zip package from the RokMage Extensions [downloads page][download].

Once you have downloaded and unzipped the extension package, you will notice that the folder structure for the files has been included. This means you can simply copy the files/folders over to the corresponding folder of your Magento site, if developing locally. 

If you are developing on a remote server, you can simply upload the **app** and **skin** folders to the Magento install on your server.

![][installation]

:	1. This can also be the name of your template package. [22%, 55%, sw]
	2. This can also be the name of your template package. [77%, 50%, sw]

Magento uses a hierarchy system. Adding the files in the **base** folder will work with any theme package. You can also elect to add the layout, template, and skin files to your theme package folder (instead of base) in order to have the extension apply only to that theme. Anything placed in the theme package folder will override what exists in the **base** folder. Anything in the **base** folder is accepted as default.

>> If you download a RocketTheme Magento template, the extension files will all be included in the theme package folder, not the base folder.

[installation]: assets/installation.jpg
[download]: http://www.rockettheme.com/magento/extensions/productvideo/modal/downloads