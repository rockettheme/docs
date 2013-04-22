---
title: Getting Started

---

Getting Started
===============
Getting started with RocketTheme


How to install a Joomla! template
----------------------------------
There are several different ways to install a Joomla template from RocketTheme. You can start your Joomla install from scratch (including building a new database) by downloading the RocketLauncher for your desired template. This will give you everything you need to hit the ground running, including a preconfigured version of the demo for the specific theme, the Gantry framework, and any extensions required for the theme's demo build to work. 

If you have an existing site, but haven't yet installed the Gantry library, you can grab a bundle download that takes the standalone version a bit further by adding Gantry framwork.

If you have an existing site running a Gantry-enabled template, you need but to download and install the standalone template along with any required/recommended extensions listed on the template's product page.

### Installing a Template Using RocketLauncher
RocketLauncher is a bundle of everything you need to have what you see on the demo live within minutes. This is essentially a demo replica which you can modify to create a robust site that fits your individual needs. RocketLaunchers are not available with all of the older RocketTheme templates, but it will be listed prominantly on the template's downloads page when it is available.

You can find the RocketLauncher file by visiting the main template page and selecting **Download**. RocketLauncher packages may be avaiable for different versions of Joomla. This gives you a choice between the slightly older yet more widely supported Joomla 2.5 (J25) or the newer and slightly less extension-supported Joomla 3.0+. If you have a set of extensions in mind that you wish to use on your site that don't presently support the latest version of Joomla, then packages labeled J25 in the download page will probably be the best choice for you. You can always update your Joomla installation, as well as other components of the site, within the Administrator area.

(image)

After you download the RocketLauncher zip file, you can unpack it. This will give you a directory filled with the files you'll need to install Joomla and the RocketTheme template on your site.

(image)

Simply upload these files and subdirectories to your server's root web hosting directory. This is usually done via FTP/SFTP though your individual host may have other options available to you. 

(image)

Once these files are in place, you can finish installation using your browser by visiting the URL you have elected to have your Joomla installation installed. This could be the root of your domain (http://example.com) or a subdirectory (http://example.com/joomla) depending on where you placed it in your server's file system.

(image)

The first step in browser-based installation using the Joomla! Web Installer is to name your site and give it a description. This description will be used by search engines as a reference to what it is your site is about. Ideally, it'll be the cached description Google displays when people search for something that can be found at the root of your site. See the example below.

(image)

Next, you'll need to give yourself an administrative user name and password. This will allow you to receive email updates from the site as well as log in to the Administrator area, also known as the backend where you can configure site settings, layout, user properties, and customize the site to meet your specific needs. You can also opt to have the site remain offline (available only with an administrator's user name and password) until you're ready to switch it on later. You can have the site go live right away, but this means the public will see the demo duplicate as your home page until you've finished configuring your options. Once you're done with this page, hit the *Next* button.

(image)

The next step in installation concerns the database you wish to use. If Joomla is your content management system, then your database is where this content is stored and made available. Joomla will actually create a database for you so you don't have to bother with setting this up on your end. Some Web hosts don't allow this feature, so you may have to create it yourself using Cpanel or another administrative tool your provider gives you to create a MySQL, MySQLi, or PostgreSQL database.

The **Database Type** option gives you the ability to choose which type of database you wish to link to your Joomla site. You can find a complete breakdown of the differences between these database types here (link). For most users, MySQLi is the database type you'll want to select.

You'll then be asked for your database's host name. This should be provided by your Web host. It's usually `localhost` but can be different, depending on how your server is set up. Your username, password, and database name are all up to you to choose, though you might not want these to match what you use for your Joomla administrative account for security reasons. This information may also be provided by your host.

The table prefix is used to differentiate your Joomla data from other data stored in the database. One will be randomly generated in this space, though you can change it to whatever you'd like.

If you're using a pre-created database, you'll want to pay close attention to the backup option. This will allow you to either back up any data presently stored there in the event that something goes wrong with your installation. If you have an existing Joomla install on the database, it will be removed by this process. If it's a fresh install with a new database, this option really isn't going to help or hinder you moving forward. Click the *Next* button to continue.

(image)

The final installation page will go over your email address, confirm your database configuration, and alert you to any server-side settings which might conflict with the use of Joomla. You can see a detailed list of these settings and what they mean here (link). Only the settings listed under **Pre-Installation Check** are mandatory in order for Joomla to function properly.

### Installing a Template Bundle


### Installing a Standalone Template

### Other Files and Options
