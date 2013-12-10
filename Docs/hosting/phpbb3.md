---
title: phpBB3 Hosting Guide
breadcrumb: /hosting:Hosting Help/!phpbb3:phpBB3 Hosting Guide/

---

Hosting
-----

phpBB3, like any web-based technology, needs to be hosted somewhere in order for you to use it. You can host phpBB3 on several different platforms ranging from your personal computer to a series of redundant data centers placed strategically around the world. Most small sites opt to have phpBB3 hosted via a shared or managed hosting plan set up with a commercial provider. These providers set up data centers, complete with server hardware, software and a user-friendly Web-based interface that enables you to manage your server from anywhere in the world. Often, this comes at a very low price, and with the option to upgrade to dedicated server hardware and redundant Internet access, at a higher cost.

If you are just wanting to get started with phpBB3 and build your site before jumping to a publicly-accessible hosting solution, then the answer can be as simple as setting one up on your personal computer. All you need to do this is compatible hosting software and a little time to set up. 

Here are a list of programs you can use to set up your own phpBB3-capable server at home:

* [MAMP and MAMP Pro](http://www.mamp.info/en/index.html) - Apache, PHP, MySQL on OS X
* [Microsoft IIS7](http://www.iis.net/)
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

#### Linux

Linux has long been the go-to platform for Web hosting. The vast majority of the sites you visit every day are hosted on a Linux distro. It is starting to lose a little ground to Windows, but it still retains the top spot as the go-to platform for anyone wanting to run a cheap, reliable server.

One of the reasons for Linux's popularity is that, for providers, it is free. You do not have to buy a new license for every instance of Linux you run in your data center. It is clean, configurable, and can be managed without ever having to load a graphical user interface. These savings are often passed on to customers.

In addition, you enjoy native support for a number of scripting languages including PHP, the language on which phpBB3 is built.

#### Windows

Windows is given a hard time for a number of reasons unrelated to actual server performance. Windows is actually a very capable server platform, especially if you need to run ASP or ASP.NET scripting.

For the vast majority of phpBB3 applications out there, Linux is probably going to be your safest bet.

### Apache Vs. NGINX Vs. IIS

phpBB3's technical requirements include three different server technologies you can choose from. Apache, NGINX, and Microsoft IIS are three of the most common server software solutions you will find listed in hosting provider's spec sheets.

#### Apache

Apache is by far the most popular Web hosting software currently being used. It can be run in a variety of forms on virtually any operating system (including OS X and Windows).

Apache supports all of the technologies phpBB3 requires to function natively, and is quick and easy to set up via bundle software like MAMP, LAMP, and WAMP (listed above).

#### Microsoft IIS7

Microsoft's IIS server software is robust and capable. It is also the second most readily available hosting option aside from Linux-based Apache solutions. If you plan on running ASP or ASP.NET applications as part of your overall Web hosting needs, then this may well be the best option for you. You can run these through Apache with the help of extensions. phpBB3 does not require either to operate.

#### NGINX

NGINX (pronounced "engine X") is a rising star in the world of Web servers. It is seen largely as a quick and lightweight alternative to Apache. It is a favorite among Ruby developers, and has received plenty of attention for being quick and adaptable. It currently sits neck-and-neck with Microsoft IIS in terms of market share around 12.5% (depending on which statistic you read). This means it has a smaller body of community support than Apache, which has around a 60-70% market share in 2013.

On the positive, NGINX currently powers some of the most popular sites on the Web. This includes: Netflix, Hulu, Pinterest, GitHub, Zynga, Eventbrite, Zappos, and more.


Server Requirements
--------------

In order for phpBB3 to operate properly, there are a series of requirements that have to be met. For example, having an old version of PHP means that your server wouldn't know how to interpret some of the more modern PHP scripting commands, and this could break the site. Listed below are the requirements for [phpBB3][phpreqs].

* A webserver or web hosting account running on any major Operating System with support for PHP
* A SQL database system, one of:
	* MySQL 3.23 or above (MySQLi supported)
	* PostgreSQL 7.3+
	* SQLite 2.8.2+ (SQLite 3 is not supported)
	* Firebird 2.1+
	* MS SQL Server 2000 or above (directly or via ODBC or the native adapter)
	* Oracle
* PHP (**>=4.3.3**, **>=4.4.0**, **>=5.0.0**) with support for the database you intend to use.
* getimagesize() function must be enabled.
* Presence of the following modules within PHP will provide access to additional features, but they are not required:
	* zlib Compression support
	* Remote FTP support
	* XML support
	* Imagemagick support
	* GD Support

If your server or hosting account does not meet the requirements above then you will be unable to install phpBB 3.0.x.

[phpreqs]: https://www.phpbb.com/community/docs/INSTALL.html#require