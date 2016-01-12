---
title: Search Engines and Joomla Mobile Friendliness
description: Your Guide to Making Joomla More Mobile Friendly for Search
breadcrumb: /joomla:Joomla/!platform:Platform/!mobile-friendly:Mobile Friendliness

---

Introduction
-----

Google has made some changes to its search ranking algorithms and mobile friendliness is near the top of the list of things Google is taking into account when determining how to rank a website.

RocketTheme prides itself on having mobile-friendly Gantry 4 and 5 templates and themes, however there may be a case where Joomla's standard **robots.txt** file prevents Google and other search engines from accessing areas of the site that it should be able to.

With a small modification to this file, you should be able to provide access to these necessary folders and present a clean bill of health on your site's mobile friendliness. Here is an example of this file.

~~~ .txt
# If the Joomla site is installed within a folder such as at
# e.g. www.example.com/joomla/ the robots.txt file MUST be
# moved to the site root at e.g. www.example.com/robots.txt
# AND the joomla folder name MUST be prefixed to the disallowed
# path, e.g. the Disallow rule for the /administrator/ folder
# MUST be changed to read Disallow: /joomla/administrator/
#
# For more information about the robots.txt standard, see:
# http://www.robotstxt.org/orig.html
#
# For syntax checking, see:
# http://tool.motoricerca.info/robots-checker.phtml

User-agent: *
Disallow: /administrator/
Disallow: /bin/
#Disallow: /cache/
Disallow: /cli/
#Disallow: /components/
Disallow: /includes/
Disallow: /installation/
Disallow: /language/
Disallow: /layouts/
#Disallow: /libraries/
Disallow: /logs/
#Disallow: /modules/
#Disallow: /plugins/
Disallow: /tmp/
~~~

