---
title: Magento Hosting Guide
breadcrumb: /hosting:Hosting Help/!magento:Magento Hosting Guide/

---

Hosting
-----

Magento, like any web-based technology, needs to be hosted somewhere in order for you to use it. You can host Magento on several different platforms ranging from your personal computer to a series of redundant data centers placed strategically around the world. Most small sites opt to have Magento hosted via a shared or managed hosting plan set up with a commercial provider. These providers set up data centers, complete with server hardware, software and a user-friendly Web-based interface that enables you to manage your server from anywhere in the world. Often, this comes at a very low price, and with the option to upgrade to dedicated server hardware and redundant Internet access, at a higher cost.

If you are just wanting to get started with Magento and build your site before jumping to a publicly-accessible hosting solution, then the answer can be as simple as setting one up on your personal computer. All you need to do this is compatible hosting software and a little time to set up.

Here are a list of programs you can use to set up your own Magento-capable server at home:

* [MAMP and MAMP Pro](http://www.mamp.info/en/index.html) - Apache, PHP, MySQL on OS X
* [WAMP](http://www.wampserver.com/en/) - Apache, PHP, MySQL on Windows
* [LAMP](http://en.wikipedia.org/wiki/LAMP_%28software_bundle%29) - Apache, PHP, MySQL on Linux
* [WiNGINX](http://wiNGINX.com/) - NGINX, PHP, MySQL, Node.js, etc. for Windows

Having your own server is a great way to get started, build a site in the privacy of your own network, and avoid paying for hosting services when you are not even ready to put them to use just yet. This solution is temporary, however, as launching a site generally requires that you find some way to host it from a server located in a data center or at least connected to the Internet from a provider that allows Web hosting. Most home Internet providers have a clause that prevents you from hosting websites and services without paying extra for a commercial account.

Thankfully, remote hosting services are available for prices as low as what you might expect to spend on a cup of coffee per month. If your site expects to have a higher traffic load, or needs a more powerful server than a shared hosting solution can provide, you can opt to upgrade to a dedicated hosting plan. These usually come complete with your own remotely managed Windows or Linux server, for a reasonable fee.

If you are building a site for a business with a little more cash to spend, you could even go so far as to purchase and manage your own server. There are plenty of colocation data centers out there that will rent rack spaces to you at a reasonable fee. Doing this allows you to create and manage your server architecture entirely in-house. It can be both the most flexible and expensive solution.

Hosting Options
--------------

There are plenty of different options to consider when choosing the right hosting provider. Perhaps the most important consideration to make before looking at any of these options is in determining your site's actual needs.

Here are some questions to ask yourself prior to making any hosting decisions.
* How much traffic do I expect to receive on my site?
* How much control do I need over the hosting environment?
* Will my site require a CDN or redundant hosting?
* How many site administrators will I need to assign?
* Will my hosting provider also need to manage email for my domain?
* What type of hosting can I afford? Can I handle overage fees if my site is hit by an unexpected overflow of traffic?

You should also take in account where your main target audience are located - For example, if your customers are mainly from Europe, you should choose a Web host that is based in (or have services) in Europe. The further away you are from your customers, the slower your Web site will be in general. You will lose customers/visitors if your Web site is slow.

With these answers at the ready, choosing the right hosting provider can be a fairly easy process. The vast majority of hosts out there offer pretty much the same list of benefits, with minor differences in location, technology, traffic capabilities, and price.

### Windows Vs. Linux

While there are certainly plenty of excellent hosting technologies out there, there are very few providers that offer any alternatives to either Windows or Linux-based hosting services.

According to the official [Magento requirements list][magento], Linux is presently the only supported server-side operating environment.

#### Linux

Linux has long been the go-to platform for Web hosting. The vast majority of the sites you visit every day are hosted on a Linux distro. It is starting to lose a little ground to Windows, but it still retains the top spot as the go-to platform for anyone wanting to run a cheap, reliable server.

One of the reasons for Linux's popularity is that, for providers, it is free. You do not have to buy a new license for every instance of Linux you run in your data center. It is clean, configurable, and can be managed without ever having to load a graphical user interface. These savings are often passed on to customers.

In addition, you enjoy native support for a number of scripting languages including PHP, the language on which Magento is built.

#### Windows

Windows is given a hard time for a number of reasons unrelated to actual server performance. Windows is actually a very capable server platform, especially if you need to run ASP or ASP.NET scripting.

For the vast majority of Magento applications out there, Linux is probably going to be your safest bet.

### Apache Vs. NGINX Vs. IIS

Magento's technical requirements include two different server technologies you can choose from. Apache and NGINX are two of the most common server software solutions you will find listed in hosting provider's spec sheets.

You might be able to get Magento to run under a IIS, but it is neither supported nor recommended.

#### Apache

Apache is by far the most popular Web hosting software currently being used. It can be run in a variety of forms on virtually any operating system (including OS X and Windows).

Apache supports all of the technologies Magento requires to function natively, and is quick and easy to set up via bundle software like MAMP, LAMP, and WAMP (listed above).

#### NGINX

NGINX (pronounced "engine X") is a rising star in the world of Web servers. It is seen largely as a quick and lightweight alternative to Apache. It is a favorite among Ruby developers, and has received plenty of attention for being quick and adaptable. It currently sits neck-and-neck with Microsoft IIS in terms of market share around 12.5% (depending on which statistic you read). This means it has a smaller body of community support than Apache, which has around a 60-70% market share in 2013.

On the positive, NGINX currently powers some of the most popular sites on the Web. This includes: Netflix, Hulu, Pinterest, GitHub, Zynga, Eventbrite, Zappos, and more.


Server Requirements
--------------

In order for Magento to operate properly, there are a series of requirements that have to be met. For example, having an old version of PHP means that your server wouldn't know how to interpret some of the more modern PHP scripting commands, and this could break the site. Listed below are the requirements for [Magento][magento].

>> NOTE: Magento has an [official list][list] of recommended hosting providers that are in compliance with these requirements.

Supported Operating Systems:

* Linux x86, x86-64

Supported Web Servers:

* Apache 1.3.x
* Apache 2.0.x
* Apache 2.2.x
* Nginx (starting from Magento 1.7 Community and 1.12 Enterprise versions)

PHP Compatibility:

* 5.2.13 - 5.3.24

Required extensions:

* PDO_MySQL
* simplexml
* mcrypt
* hash
* GD
* DOM
* icony
* curl
* SOAP (if Webservices API is to be used)
* Safe_mode off
* Memory_limit no less than 256Mb (preferably 512)

MySQL:

* EE 1.13.0.0 or later: MySQL 5.0.2 or newer
* EE 1.12.0.2 or earlier: MySQL 4.1.20 or newer
* CE (all versions): MySQL 4.1.20 or newer
* Redis NoSQL (optional for CE 1.8 and later, EE 1.13 and later)
* redis-server version 2.6.9 or later
* phpredis version 2.2.2 or later

SSL:

* If HTTPS is used to work in the admin, SSL certificate should be valid. Self-signed SSL certificates are not supported

Server - hosting - setup:

* Ability to run scheduled jobs (crontab) with PHP 5
* Ability to override options in .htaccess files

If your server or hosting account does not meet the requirements above then you will be unable to install Magento.

[magento]: http://magento.com/resources/system-requirements
[list]: http://partners.magento.com/partner_locator/search.aspx?f0=Types+of+Partners&f0v0=Hosting+Partner
