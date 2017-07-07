---
title: How to Install Joomla 3.x
description: Your Guide to Installing a Joomla 3.x
breadcrumb: /joomla:Joomla/!platform:Platform/!install_joomla_3x.md:How to install Joomla! 3.x

---

How to Install
-----

Installing Joomla is a fairly straightforward process. There are several ways to do it, and all of them offer their own benefits depending on the individual needs of the user. The preferred method depends on a number of factors, including whether you are installing to a localhost or remote hosting environment.

### Technical Requirements

Before installing Joomla, you should make sure that your server meets the minimum requirements for the Joomla release you wish to use. These requirements are made available on [Joomla.org](http://www.joomla.org/technical-requirements.html) and can be checked against your existing server version, PHP, and MySQL (or supported alternatives). For most users with remotely hosted sites, Cpanel provides this information on the left-hand sidebar.

Currently, the Joomla requirements are as follows:

#### Joomla 3.x

| Software      | Minimum        | Recommended    |  
| :------------ | :------------- | :------------- |  
| MySQL         | 5.1 +          | 5.4 +          |  
| MSSQL         | 10.50.1600.1 + | 10.50.1600.1 + |  
| PostgreSQL    | 8.3.18 +       | 8.3.18 +       |  
| PHP           | 5.3.1 +        | 5.3.1          |  
| Apache        | 2.x +          | 2.x +          |  
| Nginx         | 1.0            | 1.1            |  
| Microsoft IIS | 7              | 7              |  

For users on a non-Microsoft server architecture, MSSQL will not appear under the database options during installation. Instead, you will be able to choose between PostgreSQL, MySQL, and MySQLi. MySQLi is the recommended database type for Joomla 3.x due to its native support and enhanced performance.

### Downloading and Installing

There are several ways to install Joomla! Finding the right method for you depends on a number of factors, but We have listed some of the more common installation types below.

#### One-Click Install

Many hosting companies provide a quick and easy method known as a one-click installation. This is often provided by hosting companies as a way to install Joomla quickly and easily without having to open a separate FTP/SFTP or SSH connection to the server. Be sure to note the version of Joomla your hosting company supports.

#### RocketLauncher
RocketLauncher allows you to essentially download and install Joomla, the Gantry framework, and a copy of the demo site for any RocketTheme template you prefer. This is the easiest way to hit the ground running with Joomla and a RocketTheme template as it will give you a pre-configured site with all the required support files you need to build on.

#### Conventional Install

For most users, a conventional installation will work just fine. You will need to download the [Joomla! ZIP package](http://joomla.org) of your choice, and create a database which you will use to store the content and settings date for the site.

Upon downloading Joomla 3.x, you will need to place the ZIP file in the remote or localhost directory you wish to have your Joomla! site appear on. You can then unpack the file and access the primary installer via your browser by navigating to the root installation folder as you would if you were visiting the site normally.

Joomla Web Installer for 3.x
----------------------------

![][installation_joomla3x_2]

:   1. **Select Language** What language do you wish to use? [16%, 9%, ne]
    2. **Site Name and Description** What name would you like your site to have? What description would you like to give search engines for your site? [30%, 12%, ne]
    3. **Administrator Information** This is where you set up the administrator email, username, and password. [30%, 55%, ne]
    4. **Site Offline** Do you want to site to be live immediately after installation? [80%, 13%, ne]

The first page in the Joomla! 3.x Web Installer is to select your preferred language. This can be done using the **Select Language** drop-down menu (point 1) on the **Configuration** tab within the installer.

Next, you can name your site and give it a description (point 2). This description will be used by search engines as a reference to what it is your site is about. Ideally, it'll be the cached description Google displays when people search for something that can be found at the root of your site. 

Next, you will need to give yourself an administrative user name and password (point 3). This will allow you to receive email updates from the site as well as log in to the Administrator area, also known as the backend where you can configure site settings, layout, user properties, and customize the site to meet your specific needs. You can also opt to have the site remain offline (available only with an administrator's user name and password) until you are ready to switch it on later (point 4). You can have the site go live right away, but this means the public will see the demo duplicate as your home page until you have finished configuring your options. 

Once you are done with this page, hit the **Next** button.

![][installation_joomla3x_3]

:   1. **Database Type** What type of database would you like to use for the site? [22%, 10%, ne]
    2. **Host Name** What is your database username? [31%, 12%, ne]
    3. **User Name** What is your database username? [40%, 13%, ne]
    4. **Database Name** What is the name of your current or new database? [58%, 9%, ne]
    5. **Table Prefix** This sets the prefix that appears on any Joomla-related tables in the database. [67%, 12%, ne]
    6. **Old Database Process** This option gives you the opportunity to back up or remove previous Joomla install data. [82%, 12%, ne]

The next step in installation concerns the database you wish to use. If Joomla is your content management system, then your database is where this content is stored and made available. Joomla will actually create a database for you so you do not have to bother with setting this up on your end. Some Web hosts do not allow this feature, so you may have to create it yourself using Cpanel or another administrative tool your provider gives you to create a MySQL, MySQLi, or PostgreSQL database.

The **Database Type** option (point 1) gives you the ability to choose which type of database you wish to link to your Joomla site. For most users, MySQLi is the database type you will want to select.

You will then be asked for your database's **Host Name** (point 2). This should be provided by your Web host. It is usually `localhost` but can be different, depending on how your server is set up. 

Your **Username** and **Password** (point 3) need to be entered next. This information may be provided by your host, or available for you to configure to your preferences. Check with your host to determine which options are available to you. The same applies to the **Database Name** field (point 4).

The **Table Prefix** (point 5) is used to differentiate your Joomla data from other data stored in the database. One will be randomly generated in this space, though you can change it to whatever you would like.

If you are using a pre-created database, you will want to pay close attention to the **backup** option (point 6). This will allow you to either back up any data presently stored there in the event that something goes wrong with your installation. If you have an existing Joomla install on the database, it will be removed by this process. If it is a fresh install with a new database, this option really is not going to help or hinder you moving forward. Click the *Next* button to continue.

![][installation_joomla3x_5]

:   1. **Install Sample Data** This option gives you some sample data to work from while building your site. Select the data type that works best for you, or none at all. [32%, 9%, ne]
    2. **Email Configuration** Do you want your installation configuration emailed to your administrator address? [80%, 9%, ne]

The final installation page will go over your email address, confirm your database configuration, and alert you to any server-side settings which might conflict with the use of Joomla. Only the settings listed under **Pre-Installation Check** are mandatory in order for Joomla to function properly.

On this page, you can elect to install sample data which will populate your site with data intended to work as a guide during initial adjustments. This includes a few articles, categories, and a handful of sample images.

![][installation_joomla3x_4]

Once you have verified the settings on this page, just hit **Install** and your Joomla site will be set up for you. You will be prompted to remove the installation folder in the next page. By clicking this, you will have completed the installation process. 

[installation_joomla3x_2]: assets/installation_joomla3x_2.jpeg
[installation_joomla3x_3]: assets/installation_joomla3x_3.jpeg
[installation_joomla3x_4]: assets/installation_joomla3x_4.jpeg
[installation_joomla3x_5]: assets/installation_joomla3x_5.jpeg
[installation_joomla3x_6]: assets/installation_joomla3x_6.jpeg
