---
title: How to Install a phpBB RocketLauncher
description: This document will guide you through the process of installing a phpBB RocketLauncher from RocketTheme.
breadcrumb: /phpbb:phpBB/!start:Getting Started/!install.md:How to Install phpBB
tags: [RocketLauncher, Base, Platform, Tutorial]

---

Introduction
-----

RocketTheme provides RocketLaunchers to make installing a brand new phpBB site, complete with a pre-installed RocketTheme Style, as easy as possible. You can use RocketLaunchers to hit the ground running in minutes.

Installation can be quick and easy, as long as the server you are hosting it from meets all the requirements needed to run phpBB. You will find these requirements listed in the [Requirements Check][requirements] portion of this guide.

The majority of the installation process takes place in your browser, though you will need some way to move the zipped or unzipped files to your server. One popular option is [FileZilla][filezilla], though any compatible FTP, SFTP, or web-based file management solution will work just fine.

You will also need to have a compatible database set up and ready to go. Options for this database can be found in the [Requirements Check][requirements] area of this tutorial.

>> NOTE: This tutorial focuses on the installation process of phpBB v3.

### Step 1: Upload phpBB to Your Server

![][rocketlauncher1]

The first thing you will need to do is download a RocketLauncher. 

You can either keep the zip file compressed and upload it directly to your server via FTP. Once this is done, you can uncompress the file and move the resulting folder's contents to the directory you wish your phpBB site to run from. Doing it this way reduces the chance for file corruption during transfer as you are moving a single file from your local machine to the host.

If your hosting provider does not allow you to uncompress zip files on the server, you can do so locally and move the contents of the resulting folder directly to the directory you want phpBB to run from.

>> NOTE: Make sure the permissions for **config.php** are set to writable by all (666 or -rw-rw-rw-). Additionally, the **store/**, **cache/**, **files/** and **images/avatars/upload/** directories should be set to writable and executable by all (777 or -rwxrwxrwx). You can usually do this directly through your FTP client.

As an example, if you want your forums to launch from *http://(your domain name).com/forum/* you will place the uncompressed directory in the **forum** folder found in your site's main HTML directory.

Once this is done, you should be able to navigate your browser to the URL you placed phpBB in and see an **Introduction** page similar to the one pictured below.

### Step 2: Introduction

![][rocketlauncher2]

In order to install phpBB, you will need to hit the **Install** tab from the main introduction page. This will initiate the installation process, starting with the page pictured above. You are not required to take any action on this page. It is simply there to prepare you for the steps to come.

This is a good time to write down your database username and password, as well as think of your desired admin username and password for phpBB. We recommend using different sets for each for security purposes.

Once you are ready to move on, select the **Proceed to next step** button at the bottom of the page.

### Step 3: Requirements Check

![][rocketlauncher3]

The requirements page checks your current hosting account against the requirements needed to run phpBB. If your host meets the minimum requirements, you will be able to proceed to the next step.

The current requirements for phpBB v3 are listed below:

* A webserver or web hosting account running on any major operating system with support for PHP
* A SQL database system, **one of**:
	* MySQL 3.23 or above (MySQLi supported)
	* PostgreSQL 7.3+
	* SQLite 2.8.2+ (SQLite 3 is not supported)
	* Firebird 2.1+
	* MS SQL Server 2000 or above (directly or via ODBC or the native adapter)
	* Oracle
* **PHP (>=4.3.3, >=4.4.0, >=5.0.0)** with support for the database you intend to use.
* getimagesize() function must be enabled.
* Presence of the following modules within PHP will provide access to additional features, but they are **not required**:
	* zlib Compression support
	* Remote FTP support
	* XML support
	* Imagemagick support
	* GD Support

If you are unable to proceed, you can check the page for any missing options and check with your hosting provider for ways to meet these requirements.

### Step 4: Database Configuration

![][rocketlauncher4]

:	1. **Database Type** Select which type of database you will be connecting phpBB to. [32%, 73%, sw]
	2. **Database Server Hostname or DSN** The server hostname or DSN of your database. This is usually `localhost`. [37%, 57%, se]
	3. **Database Server Port** The port on which phpBB can communicate with the database. If you do not know (or if your hosting provider does not indicate any) this can be left blank. [49%, 57%, se]
	4. **Database Name** Enter the unique name of your database as it appears on your host. [57%, 57%, se]
	5. **Database Username** This is the username used to manage the database, and will generally be different from the one you use to manage phpBB on the backend. [61%, 71%, sw]
	6. **Database Password** This is the password linked to the administrative database username. [65%, 57%, se]
	7. **Prefix for Tables in the Database** This prefix appears prior to tables used for phpBB in the database. This is done to keep your phpBB data separate from any other data being used for other areas of your site (for example: a Joomla or WordPress installation). [71%, 57%, ne]

The **Database Configuration** page establishes a connection to the database on which phpBB will be hosted. This database does not have to be exclusive to phpBB, though it certainly can be.

1. **Database Type** Select which type of database you will be connecting phpBB to.

2. **Database Server Hostname or DSN** The server hostname or DSN of your database. This is usually `localhost`.

3. **Database Server Port** The port on which phpBB can communicate with the database. If you do not know (or if your hosting provider does not indicate any) this can be left blank.

4. **Database Name** Enter the unique name of your database as it appears on your host.

5. **Database Username** This is the username used to manage the database, and will generally be different from the one you use to manage phpBB on the backend.

6. **Database Password** This is the password linked to the administrative database username.

7. **Prefix for Tables in the Database** This prefix appears prior to tables used for phpBB in the database. This is done to keep your phpBB data separate from any other data being used for other areas of your site (for example: a Joomla or WordPress installation).

![][rocketlauncher5]

Once you have filled out the required information, click **Proceed to the next step** to initiate a connection to the database. If successful, a message similar to the one pictured above should appear.

### Step 5: Administrator Configuration

![][rocketlauncher6]

:	1. **Default Board Language** Set the default language you wish to have the board use on the front and backend. Additional languages can be downloaded from the main phpBB site. [35%, 57%, se]
	2. **Administrator Username** This is the username assigned to the main administrative account on the site. [40%, 71%, sw]
	3. **Administrator Password** This will be the password for the main administrative account. [49%, 57%, se]
	4. **Confirm Administrator Password** Enter the password used above again to confirm. [56%, 71%, sw]
	5. **Contact Email Address** This email address is used by phpBB to send messages and alerts to the administrator. [62%, 57%, se]
	6. **Confirm Contact Email Address** Enter the email address used above again to confirm. [67%, 71%, sw]

The **Administrator Configuration** page is where you can set the primary language used in the board, as well as the administrator name, password, and contact email address.

1. **Default Board Language** Set the default language you wish to have the board use on the front and backend. Additional languages can be downloaded from the main phpBB site.

2. **Administrator Username** This is the username assigned to the main administrative account on the site.

3. **Administrator Password** This will be the password for the main administrative account.

4. **Confirm Administrator Password** Enter the password used above again to confirm.

5. **Contact Email Address** This email address is used by phpBB to send messages and alerts to the administrator. It is also used in the event that the password is forgotten for the main administrative account.

6. **Confirm Contact Email Address** Enter the email address used above again to confirm.

Once you have entered the required information, select **Proceed to the next step** to continue. phpBB will then test your administrative options before allowing you to proceed.

![][rocketlauncher7]

Once the test has been run and you click to proceed again, a configuration file will be written and a confirmation page (similar to the one pictured below) will appear.

![][rocketlauncher8]

### Step 6: Email Settings

![][rocketlauncher9]

:	1. **Enable Board-wide Emails** Enables or disables email sent by the board. Emails are used to notify users of direct messages, comments on followed threads, etc. [18%, 47%, se]
	2. **Use SMTP for Email** If you have a named server you would like to have email sent through (as opposed to the local mail function) then you will want to select **Yes**. To use the local mail function, leave this option at its default setting. [35%, 47%, se]
	3. **SMTP Server Address** This is the server address for your SMTP server. Only required if you choose to send mail through SMTP. [44%, 65%, sw]
	4. **Authentication Method for SMTP** Only used if a username/password is set. Ask your provider if you are unsure. [50%, 47%, se]
	5. **SMTP Username** Enter the username for your SMTP account. This should only be entered if the server requires it. [59%, 65%, sw]
	6. **SMTP Password** A password should only be entered if the SMTP server requires it. The password will be stored as plain text in the database. This is visible to anyone with access to the database. [66%, 47%, se]

The **Email Settings** page is where you can configure the primary email settings for the entire phpBB site. Most of the time, these settings can be left at default and you can just click **Proceed to the next step**. If you have specific requirements for email created by the phpBB site, you can set this up here.

1. **Enable Board-wide Emails** Enables or disables email sent by the board. Emails are used to notify users of direct messages, comments on followed threads, etc.

2. **Use SMTP for Email** If you have a named server you would like to have email sent through (as opposed to the local mail function) then you will want to select **Yes**. To use the local mail function, leave this option at its default setting.

3. **SMTP Server Address** This is the server address for your SMTP server. Only required if you choose to send mail through SMTP.

4. **Authentication Method for SMTP** Only used if a username/password is set. Ask your provider if you are unsure.

5. **SMTP Username** Enter the username for your SMTP account. This should only be entered if the server requires it.

6. **SMTP Password** A password should only be entered if the SMTP server requires it. The password will be stored as plain text in the database. This is visible to anyone with access to the database.

### Step 7: Server URL Settings

![][rocketlauncher10]

:	1. **Cookie Secure** Select this option as enabled if your site is running via SSL. If not, leave this as disabled. [18%, 62%, sw]
	2. **Force Server URL Settings** Select **Yes** if server settings defined on this page should override default settings. [29%, 56%, sw]
	3. **Server Protocol** This sets the protocol type for the server (**http://** vs. **https://**). You should generally select a secured protocol if **Cookie Secure** is enabled. [38%, 55%, sw]
	4. **Domain Name** This is where you enter the primary domain name for your server. [49%, 73%, sw]
	5. **Server Port** This is the port from which the server is running. This is usually 80. [58%, 51%, sw]
	6. **Script Path** This is the directory path phpBB is installed on. In our example, phpBB is installed in */phpbb/site1/* and is accessible by going to *http://(your domain)/phpbb/site1/*. [68%, 61%, sw]

The **Server URL Settings** page is where miscellaneous server-specific data can be entered. This includes cookies, server protocol type, port numbers, and script paths.

1. **Cookie Secure** Select this option as enabled if your site is running via SSL. If not, leave this as disabled.

2. **Force Server URL Settings** Select **Yes** if server settings defined on this page should override default settings.

3. **Server Protocol** This sets the protocol type for the server (**http://** vs. **https://**). You should generally select a secured protocol if **Cookie Secure** is enabled.

4. **Domain Name** This is where you enter the primary domain name for your server.

5. **Server Port** This is the port from which the server is running. This is usually 80.

6. **Script Path** This is the directory path phpBB is installed on. In our example, phpBB is installed in */phpbb/site1/* and is accessible by going to *http://(your domain)/phpbb/site1/*.

![][rocketlauncher11]

Once you have entered the information, you can select **Proceed to next step** to lock the settings in and finalize installation. From here, you will be given the option to log in to the backend of your site and begin using it.

[rocketlauncher1]: assets/rocketlauncher_1.jpeg
[rocketlauncher2]: assets/rocketlauncher_2.jpeg
[rocketlauncher3]: assets/rocketlauncher_3.jpeg
[rocketlauncher4]: assets/rocketlauncher_4.jpeg
[rocketlauncher5]: assets/rocketlauncher_5.jpeg
[rocketlauncher6]: assets/rocketlauncher_6.jpeg
[rocketlauncher7]: assets/rocketlauncher_7.jpeg
[rocketlauncher8]: assets/rocketlauncher_8.jpeg
[rocketlauncher9]: assets/rocketlauncher_9.jpeg
[rocketlauncher10]: assets/rocketlauncher_10.jpeg
[rocketlauncher11]: assets/rocketlauncher_11.jpeg
[requirements]: rocketlauncher.md#step-3:-requirements-check
[phpBB]: https://www.phpbb.com/downloads/
[filezilla]: https://filezilla-project.org/download.php
[languages]: https://www.phpbb.com/languages/
