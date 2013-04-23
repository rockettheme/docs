---
title: Start

---

What is Joomla?
===
Joomla is an open source platform on which Web sites and applications can be created. It's a content management system (CMS) which connects your site to a MySQLi, MySQL, or PostgreSQL database in order to make content management and delivery easier on both the site manager and visitor.

Joomla's primary focus has been on usability and extensibility since its initial release in 2005. It's because of this that the project has been the recipient of numerous awards, including being a three-time recipient of the PACKT Open Source Content Management System Award.

Joomla is a completely free open source solution available to anyone and everyone with a desire to build dynamic and robust sites for a variety of purposes. Joomla has been utilized by some of the Web's most recognizable brands including Harvard, iHop, and MTV. It's capable of carrying out tasks ranging from corporate websites and blogs to social networks and e-commerce.

Joomla is backed by a large and active developer community. With thousands of unique and useful extensions and templates available, it is presently one of the largest single site building platforms available. It's this incredible community effort that makes Joomla a great choice for developers searching for a single platform with which they can receive active support from their peers.

It's important to think of Joomla not as a limited platform on which a specific type of site is built, but a robust set of tools that makes it possible to connect visitors to data in a variety of ways. Joomla's extensive set of integrated technologies empowers site managers and developers to innovate well beyond the bounds of a simple website.

You can find out more about Joomla! by visiting [Joomla.org](http://www.joomla.org/).

How to install Joomla!
----------------------------------
Installing Joomla is a fairly straightforward process. There are several ways to do it, and all of them offer their own benefits depending on the individual needs of the user. The preferred method depends on a number of factors, including whether you're installing to a localhost or remote hosting environment.

### Technical Requirements
Before installing Joomla, you should make sure that your server meets the minimum requirements for the Joomla release you wish to use. These requirements are made available on [Joomla.org](http://www.joomla.org/technical-requirements.html) and can be checked against your existing server version, PHP, and MySQL (or supported alternatives). For most users with remotely hosted sites, Cpanel provides this information on the left-hand sidebar.

Currently, the Joomla requirements are as follows:

#### Joomla 2.5

| Software      | Minimum       | Recommended |
| :------------ |--------------:| ---------:  |
| MySQL         | 5.0.4 +       |     5.0.4 + |
| PHP           | 5.2.4 +       |       5.3 + |
| Apache        | 2.x +         | 2.x +       |
| Nginx         | 1.0           |     1.1     |
| Microsoft IIS | 7             | 7           |

#### Joomla 3.x

| Software      | Minimum       |  Recommended  |
| :------------ |--------------:| ------------: |
| MySQL         | 5.1 +         |     5.1 +     |
| MSSQL         | 10.50.1600.1 +| 10.50.1600.1 +|
| PostgreSQL    | 8.3.18 +      |     8.3.18 +  |
| PHP           | 5.3.1 +       |       5.3.1   |
| Apache        | 2.x +         | 2.x +         |
| Nginx         | 1.0           |     1.1       |
| Microsoft IIS | 7             | 7             |

While Joomla 2.5 stands out as being longer in the tooth and more stable than 3.0, it doesn't offer you as much flexibility in terms of the types of SQL databases you can connect to. In addition, you may miss out on some of the newer features of Joomla 3.0 which offer additional customization and enhanced usability.

For users on a non-Microsoft server architecture, MSSQL will not appear under the database options during installation. Instead, you will be able to choose between PostgreSQL, MySQL, and MySQLi. MySQLi is the recommended database type for Joomla 3.x due to its native support and enhanced performance.

### Downloading and Installing
There are several ways to install Joomla! Finding the right method for you depends on a number of factors, but we've listed some of the more common installation types below.

#### One-Click Install
Many hosting companies provide a quick and easy method known as a one-click installation. This is often provided by hosting companies as a way to install Joomla quickly and easily without having to open a separate FTP/SFTP or SSH connection to the server. Be sure to note the version of Joomla your hosting company supports. Right now, version 2.5 is more common as 3.0 is newer and is being updated more regularly as bugs and other minor issues are ironed out.

#### Conventional Install
For most users, a conventional installation will work just fine. You'll need to download the [Joomla! ZIP package](http://joomla.org) of your choice, and create a database which you will use to store the content and settings date for the site.

Upon downloading Joomla 2.5 or 3.x, you'll need to place the ZIP file in the remote or localhost directory you wish to have your Joomla! site appear on. You can then unpack the file and access the primary installer via your browser by navigating to the root installation folder as you would if you were visiting the site normally.

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

Once you've verified the settings on this page, just hit *Install* and your Joomla site will be set up for you. You will be prompted to remove the installation folder in the next page. By clicking this, you will have completed the installation process. 

#### RocketLauncher
RocketLauncher allows you to essentially download and install Joomla, the Gantry framework, and a copy of the demo site for any RocketTheme template you prefer. This is the easiest way to hit the ground running with Joomla and a RocketTheme template as it will give you a pre-configured site with all the required support files you need to build on.

You can find a detailed step-by-step guide for installing Joomla and a template via RocketLauncher here (link).
