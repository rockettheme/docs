---
title: Start

---

What is Joomla?
===
Joomla is an open source platform on which Web sites and applications can be created. It is a content management system (CMS) which connects your site to a MySQLi, MySQL, or PostgreSQL database in order to make content management and delivery easier on both the site manager and visitor.

Joomla's primary focus has been on usability and extensibility since its initial release in 2005. It is because of this that the project has been the recipient of numerous awards, including being a three-time recipient of the PACKT Open Source Content Management System Award.

Joomla is a completely free open source solution available to anyone and everyone with a desire to build dynamic and robust sites for a variety of purposes. Joomla has been utilized by some of the Web's most recognizable brands including Harvard, iHop, and MTV. It is capable of carrying out tasks ranging from corporate websites and blogs to social networks and e-commerce.

Joomla is backed by a large and active developer community. With thousands of unique and useful extensions and templates available, it is presently one of the largest single site building platforms available. It is this incredible community effort that makes Joomla a great choice for developers searching for a single platform with which they can receive active support from their peers.

it is important to think of Joomla not as a limited platform on which a specific type of site is built, but a robust set of tools that makes it possible to connect visitors to data in a variety of ways. Joomla's extensive set of integrated technologies empowers site managers and developers to innovate well beyond the bounds of a simple website.

You can find out more about Joomla! by visiting [Joomla.org](http://www.joomla.org/).

How to install Joomla!
===
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

While Joomla 2.5 stands out as being longer in the tooth and more stable than 3.x, it doesn't offer you as much flexibility in terms of the types of SQL databases you can connect to. In addition, you may miss out on some of the newer features of Joomla 3.x which offer additional customization and enhanced usability.

For users on a non-Microsoft server architecture, MSSQL will not appear under the database options during installation. Instead, you will be able to choose between PostgreSQL, MySQL, and MySQLi. MySQLi is the recommended database type for Joomla 3.x due to its native support and enhanced performance.

### Downloading and Installing
There are several ways to install Joomla! Finding the right method for you depends on a number of factors, but we've listed some of the more common installation types below.

#### One-Click Install
Many hosting companies provide a quick and easy method known as a one-click installation. This is often provided by hosting companies as a way to install Joomla quickly and easily without having to open a separate FTP/SFTP or SSH connection to the server. Be sure to note the version of Joomla your hosting company supports. Right now, version 2.5 is more common as 3.x is newer and is being updated more regularly as bugs and other minor issues are ironed out.

#### Conventional Install
For most users, a conventional installation will work just fine. You'll need to download the [Joomla! ZIP package](http://joomla.org) of your choice, and create a database which you will use to store the content and settings date for the site.

Upon downloading Joomla 2.5 or 3.x, you'll need to place the ZIP file in the remote or localhost directory you wish to have your Joomla! site appear on. You can then unpack the file and access the primary installer via your browser by navigating to the root installation folder as you would if you were visiting the site normally.

#### Joomla Web Installer for 2.5
Installing Joomla! 2.5 using the Web Installer is a fairly simple process. There are seven general steps that need to be completed before your site is ready to go.

First, you'll need to select your language of choice. Joomla is supported in a wide range of languages, including several English dialects. Once you've chosen your desired language, hit the *Next* button in the upper-right corner of the page.

(image)

The next step includes the pre-installation checks and a readout of recommended settings. These checks are in place to make sure that your server is capable of hosting Joomla 2.5 natively. If any of these checks come up missing, you'll need to correct the issue prior to continuing the installation process.

In the *Recommended Settings* section under the primary pre-installation check, a series of server-side settings options are checked and displayed for you. These options aren't required to run Joomla, but are recommended if you want to get the most out of your experience. Once you've confirmed the data on this page, you can hit the *Next* button to continue.

(image)

At this point, you'll be asked to agree to the GNU General Public License that Joomla! is released under. All you need to do here is select *Next* if you agree to the license terms.

(image)

The fourth step of this process is also perhaps one of the most important. The *Database Configuration* page is where you enter the database type, host name, username, password, database name, and table prefix you would like to use for Joomla.

The *Database Type* field offers you a list of supported database types you can use to connect to Joomla. For most users, MySQLi is the best choice, though you do have the option to stick with standard MySQL or alternatives including MSSQL and PostgreSQL.

Your web hosting provider should supply you with a *Host Name* to place in the listed field. Most hosts use `localhost` as the host name, though some do request that databases be hosted from a different IP address.

Your host will also either issue or request that you register a username and password for database management. This can sometimes be "root", though not always. If you're running on a shared hosting plan, this name will likely be different. You can typically create new usernames and passwords through Cpanel or any other hosting management system.

The *Database Name* field should be filled out to match the full name of your desired database. Some hosting providers allow Joomla to create a new database here by entering a database name that doesn't already exist on the server. Others will require that you create the database with the host prior to entering it in this field.

The Table Prefix field is usually best left randomized, though instances where a single database may be used for a larger set of information or multiple applications can benefit from some recognizable association. Essentially, this prefix will appear prior to the name of a table created for the purposes of serving Joomla-specific information.

At the bottom of this page, you'll be asked if you wish to back up information presently existing on the database prior to installing Joomla. This is recommended if you have data you wish to preserve in the event that something goes wrong during installation. If you're creating a new database for this purpose, your decision here really doesn't make as much of a difference.

(image)

The next step involves FTP configuration. Don't panic, this isn't a vital step in most cases. It is only really useful in the event that your server's configuration either prevents or requires that you upload media or install extensions through this method. Servers installed on a Windows operating system and most Linux setups generally don't require this step at all.

(image)

The *Main Configuration* step is where you name your site and set up your administrator account. This can (and should) be separate from your database and hosting username and password. This will be the login credentials you use to access the administrative side of your site. 

You'll need to enter an email address, username, password, and a site name before you can continue.

At the bottom of the page, you have the option to load sample data to your site. This isn't a requirement for most users, though it can help with the initial configuration and application of templates and modules. Otherwise, you'll need to create content to fill in these spaces in order to see how your build will turn out. Once you've finished building your site, you can easily remove this sample data in favor of your own.

(image)

The final step in the process is aptly named "Finish." This page is where you remove the installation folder so your settings during initial setup are locked in. You will not be able to access your site until this step has been completed. Just select the *Remove Installation Folder* and select either Site or Administrator to start building your new Joomla site.

#### Joomla Web Installer for 3.x
(image)

The first step in browser-based installation using the Joomla! 3.x Web Installer is to name your site and give it a description. This description will be used by search engines as a reference to what it is your site is about. Ideally, it'll be the cached description Google displays when people search for something that can be found at the root of your site. See the example below.

(image)

Next, you'll need to give yourself an administrative user name and password. This will allow you to receive email updates from the site as well as log in to the Administrator area, also known as the backend where you can configure site settings, layout, user properties, and customize the site to meet your specific needs. You can also opt to have the site remain offline (available only with an administrator's user name and password) until you're ready to switch it on later. You can have the site go live right away, but this means the public will see the demo duplicate as your home page until you've finished configuring your options. Once you're done with this page, hit the *Next* button.

(image)

The next step in installation concerns the database you wish to use. If Joomla is your content management system, then your database is where this content is stored and made available. Joomla will actually create a database for you so you don't have to bother with setting this up on your end. Some Web hosts don't allow this feature, so you may have to create it yourself using Cpanel or another administrative tool your provider gives you to create a MySQL, MySQLi, or PostgreSQL database.

The **Database Type** option gives you the ability to choose which type of database you wish to link to your Joomla site. You can find a complete breakdown of the differences between these database types here (link). For most users, MySQLi is the database type you'll want to select.

You'll then be asked for your database's host name. This should be provided by your Web host. It is usually `localhost` but can be different, depending on how your server is set up. Your username, password, and database name are all up to you to choose, though you might not want these to match what you use for your Joomla administrative account for security reasons. This information may also be provided by your host.

The table prefix is used to differentiate your Joomla data from other data stored in the database. One will be randomly generated in this space, though you can change it to whatever you'd like.

If you're using a pre-created database, you'll want to pay close attention to the backup option. This will allow you to either back up any data presently stored there in the event that something goes wrong with your installation. If you have an existing Joomla install on the database, it will be removed by this process. If it is a fresh install with a new database, this option really isn't going to help or hinder you moving forward. Click the *Next* button to continue.

(image)

The final installation page will go over your email address, confirm your database configuration, and alert you to any server-side settings which might conflict with the use of Joomla. You can see a detailed list of these settings and what they mean here (link). Only the settings listed under **Pre-Installation Check** are mandatory in order for Joomla to function properly.

Once you've verified the settings on this page, just hit *Install* and your Joomla site will be set up for you. You will be prompted to remove the installation folder in the next page. By clicking this, you will have completed the installation process. 

#### RocketLauncher
RocketLauncher allows you to essentially download and install Joomla, the Gantry framework, and a copy of the demo site for any RocketTheme template you prefer. This is the easiest way to hit the ground running with Joomla and a RocketTheme template as it will give you a pre-configured site with all the required support files you need to build on.

You can find a detailed step-by-step guide for installing Joomla and a template via RocketLauncher here (link).
