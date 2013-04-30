---
title: How to Install Joomla! 2.5

---

How to Install Joomla! 2.5
===
Installing Joomla is a fairly straightforward process. There are several ways to do it, and all of them offer their own benefits depending on the individual needs of the user. The preferred method depends on a number of factors, including whether you're installing to a localhost or remote hosting environment.

### Technical Requirements
Before installing Joomla, you should make sure that your server meets the minimum requirements for the Joomla release you wish to use. These requirements are made available on [Joomla.org](http://www.joomla.org/technical-requirements.html) and can be checked against your existing server version, PHP, and MySQL (or supported alternatives). For most users with remotely hosted sites, Cpanel provides this information on the left-hand sidebar.

Currently, the Joomla requirements are as follows:

| Software      | Minimum       | Recommended |
| :------------ |--------------:| ---------:  |
| MySQL         | 5.0.4 +       |     5.0.4 + |
| PHP           | 5.2.4 +       |       5.3 + |
| Apache        | 2.x +         | 2.x +       |
| Nginx         | 1.0           |     1.1     |
| Microsoft IIS | 7             | 7           |

While Joomla 2.5 stands out as being longer in the tooth and more stable than 3.0, it doesn't offer you as much flexibility in terms of the types of SQL databases you can connect to. In addition, you may miss out on some of the newer features of Joomla 3.0 which offer additional customization and enhanced usability.

For users on a non-Microsoft server architecture, MSSQL will not appear under the database options during installation. Instead, you will be able to choose between PostgreSQL, MySQL, and MySQLi. MySQLi is the recommended database type for Joomla 3.x due to its native support and enhanced performance.

### Downloading and Installing
There are several ways to install Joomla! Finding the right method for you depends on a number of factors, but we've listed some of the more common installation types below.

#### One-Click Install
Many hosting companies provide a quick and easy method known as a one-click installation. This is often provided by hosting companies as a way to install Joomla quickly and easily without having to open a separate FTP/SFTP or SSH connection to the server. Be sure to note the version of Joomla your hosting company supports. Right now, version 2.5 is more common as 3.0 is newer and is being updated more regularly as bugs and other minor issues are ironed out.

#### Conventional Install
For most users, a conventional installation will work just fine. You'll need to download the [Joomla! ZIP package](http://joomla.org) of your choice, and create a database which you will use to store the content and settings date for the site.

Upon downloading Joomla 2.5 or 3.x, you'll need to place the ZIP file in the remote or localhost directory you wish to have your Joomla! site appear on. You can then unpack the file and access the primary installer via your browser by navigating to the root installation folder as you would if you were visiting the site normally.

#### RocketLauncher
RocketLauncher allows you to essentially download and install Joomla, the Gantry framework, and a copy of the demo site for any RocketTheme template you prefer. This is the easiest way to hit the ground running with Joomla and a RocketTheme template as it will give you a pre-configured site with all the required support files you need to build on.

You can find a detailed step-by-step guide for installing Joomla and a template via RocketLauncher here (link).

Joomla Web Installer for 2.5
----------------------------
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

The next step involves FTP configuration. Don't panic, this isn't a vital step in most cases. It's only really useful in the event that your server's configuration either prevents or requires that you upload media or install extensions through this method. Servers installed on a Windows operating system and most Linux setups generally don't require this step at all.

(image)

The *Main Configuration* step is where you name your site and set up your administrator account. This can (and should) be separate from your database and hosting username and password. This will be the login credentials you use to access the administrative side of your site. 

You'll need to enter an email address, username, password, and a site name before you can continue.

At the bottom of the page, you have the option to load sample data to your site. This isn't a requirement for most users, though it can help with the initial configuration and application of templates and modules. Otherwise, you'll need to create content to fill in these spaces in order to see how your build will turn out. Once you've finished building your site, you can easily remove this sample data in favor of your own.

(image)

The final step in the process is aptly named "Finish." This page is where you remove the installation folder so your settings during initial setup are locked in. You will not be able to access your site until this step has been completed. Just select the *Remove Installation Folder* and select either Site or Administrator to start building your new Joomla site.
