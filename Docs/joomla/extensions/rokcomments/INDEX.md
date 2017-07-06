---
title: RokComments
description: Your Guide to Using RokComments for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!rokcomments:RokComments

---

Introduction
-----

![][featured]

RokComments is a complete rewrite of the ever-popular RokIntenseDebate plugin. We have added support for Disqus and JS-Kit, as well as the original IntenseDebate support. RokComments can be enabled via menu item, Joomla category, or even a RokComments editor button for complete control.

The RokComments plugin allows for easy integration of third-party JavaScript-based comment systems, such as: IntenseDebate, Facebook, Disqus, Livefyre, and JS-Kit.

Requirements
-----

RokComments has the following requirements in order to operate:

* Joomla 3.x - ensure you are using the latest version.

>> NOTE: Internet Explorer 11+ and Edge are supported, but versions 8, 9, and 10 are no longer supported by Microsoft and while they may work, are not recommended.

>> NOTICE: RokComments requires Joomla SEF to be turned on for this plugin to function properly, and interact reliably with these comment systems. This is due to the comments being associated with the URL, and non-SEF URLs with and in them are truncated by these systems.

Key Features
-----

### Supported Systems

* [IntenseDebate][id]
* [Facebook][fb]
* [Disqus][dq]
* [Livefyre][lf]
* JS-Kit **DEPRECATED**

### Typical Comment System Features

The following are features that are found in some or all of the supported content systems listed in the previous section. RokComments integrates with these services, and can benefit from these features (as provided by the services).

* Comment Threading
* Reply-By-Email
* Importing/Exporting
* Commenter Profiles
* Reputation Points & Comment Voting
* Moderation/Blacklisting
* Widgets
* RSS Readers & Tracking
* Twitter
* FriendFeed
* OpenID
* Gravatar
* HTML Formatting

How to Install
--------------

Installing RokComments takes just a matter of few minutes.

The first thing you’ll need to do is [download][download] the latest version of RokComments. The package you will download contains everything to get RokComments up and running and it is compatible with both Joomla 2.5 and Joomla 3.x. It does not need to be uncompressed. 

Once you have downloaded the package, go into the Joomla Administrator and:

From Joomla 2.5 and 3.x:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `rokcomments.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

>> NOTE: For additional information on installing extensions, visit our detailed extensions installation guide located [here][install].

Once installation is complete, a message highlighted in green should indicate its successful completion.

[featured]: assets/rokcomments.jpg
[download]: http://www.rockettheme.com/extensions-downloads/free/1061-rokcomments
[id]: http://www.intensedebate.com
[fb]: http://developers.facebook.com
[dq]: http://www.disqus.com
[lf]: http://www.livefyre.com
[jk]: http://js-kit.com/comments/
[install]: ../../platform/extensions.md
