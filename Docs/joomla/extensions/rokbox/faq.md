---
title: RokBox: FAQ
description: Your Guide to Using RokBox for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!rokbox:RokBox

---

#### Only Audio Plays on YouTube Videos

Unfortunately, this issue isn't specific to (or caused by) RokBox. It is typically linked to YouTube's Flash player, and can be resolved by the viewer by enabling the HTML5 player through [YouTube](http://youtube.com/html5).

![][html5]

By enabling the HTML5 player, a Flash-free player is loaded in its place on any embedded instance. This is a client-side change, as there is no presently supported method of forcing the HTML5 player from YouTube. Not all videos are currently playable with the HTML5 player, do there may still be instances where the Flash version will continue to appear.

This problem is typically temporary, as YouTube is quick to spot the issue and fix the player to keep up with any changes made to the latest version of Flash.

#### Video Plays in Some Browsers, but Not All

Not all browsers support the same audio/video formats. This is one of the biggest frustrations facing media sites today. A video that plays fine on Firefox or Safari might completely fail on IE or Chrome, and vice versa.

[Mozilla provides a useful guide][mozilla] to finding the right media formats for the largest variety of current browsers.

[html5]: assets/html5.jpg
[mozilla]: https://developer.mozilla.org/en-US/docs/HTML/Supported_media_formats