---
title: How to Install Joomla! 2.5
breadcrumb: /joomla:Joomla/!platform:Platform/!install_joomla_25.md:How to Install Joomla! 2.5

---

How to Install Joomla! 2.5
-----

Installing Joomla is a fairly straightforward process. There are several ways to do it, and all of them offer their own benefits depending on the individual needs of the user. The preferred method depends on a number of factors, including whether you are installing to a localhost or remote hosting environment.

### Technical Requirements

Before installing Joomla, you should make sure that your server meets the minimum requirements for the Joomla release you wish to use. These requirements are made available on [Joomla.org](http://www.joomla.org/technical-requirements.html) and can be verified against your existing server version, PHP, and MySQL (or supported alternatives). For most users with remotely hosted sites, Cpanel provides this information on the left-hand sidebar.

Currently, the Joomla requirements are as follows:

#### Joomla 2.5

| Software      | Minimum       | Recommended |
| :------------ |--------------:| ---------:  |
| MySQL         | 5.0.4 +       |     5.0.4 + |
| PHP           | 5.2.4 +       |       5.3 + |
| Apache        | 2.x +         | 2.x +       |
| Nginx         | 1.0           |     1.1     |
| Microsoft IIS | 7             | 7           |

While Joomla 2.5 stands out as being longer in the tooth and more stable than 3.x, it does not offer you as much flexibility in terms of the types of SQL databases you can connect to. In addition, you may miss out on some of the newer features of Joomla 3.x which offer additional customization and enhanced usability.

For users on a non-Microsoft server architecture, MSSQL will not appear under the database options during installation. Instead, you will be able to choose between PostgreSQL, MySQL, and MySQLi. MySQLi is the recommended database type for Joomla 3.x due to its native support and enhanced performance.

### Downloading and Installing

There are several ways to install Joomla! Finding the right method for you depends on a number of factors, but we've listed some of the more common installation types below.

#### One-Click Install

Many hosting companies provide a quick and easy method known as a one-click installation. This is often provided by hosting companies as a way to install Joomla quickly and easily without having to open a separate FTP/SFTP or SSH connection to the server. Be sure to note the version of Joomla your hosting company supports. Right now, version 2.5 is more common as 3.x is newer and is being updated more regularly as bugs and other minor issues are ironed out.

#### Conventional Install

For most users, a conventional installation will work just fine. You'll need to download the [Joomla! ZIP package](http://joomla.org) of your choice, and create a database which you will use to store the content and settings date for the site.

Upon downloading Joomla 2.5 or 3.x, you'll need to place the ZIP file in the remote or localhost directory you wish to have your Joomla! site appear on. You can then unpack the file and access the primary installer via your browser by navigating to the root installation folder as you would if you were visiting the site normally.

#### RocketLauncher

RocketLauncher allows you to essentially download and install Joomla, the Gantry framework, and a copy of the demo site for any RocketTheme template you prefer. This is the easiest way to hit the ground running with Joomla and a RocketTheme template as it will give you a pre-configured site with all the required support files you need to build on.

Joomla Web Installer for 2.5
----------------------------

Installing Joomla! 2.5 using the Web Installer is a fairly simple process. There are seven general steps that need to be completed before your site is ready to go.

![][installation_j25_1]

:   1. **Next** This will lock in your language selection and take you to the next step in the installation process. [19%, 90%, nw]

First, you'll need to select your language of choice. Joomla is supported in a wide range of languages, including several English dialects. Once you have chosen your desired language, hit the *Next* button in the upper-right corner of the page.

![][installation_j25_2]

:   1. **Extensions** This will open the Extensions drop-down menu in Administrator. [35%, 90%, nw]
    2. **Extension Manager** This will open the Extension Manager where you can install any extension packages. [70%, 90%, nw]

The next step includes the pre-installation checks and a readout of recommended settings. These checks are in place to make sure that your server is capable of hosting Joomla 2.5 natively. If any of these checks (point 1) come up missing, you'll need to correct the issue prior to continuing the installation process.

In the **Recommended Settings** section (point 2) under the primary pre-installation check, a series of server-side settings options are checked and displayed for you. These options are not required to run Joomla, but are recommended if you want to get the most out of your experience. Once you have confirmed the data on this page, you can hit the **Next** button to continue.

![][installation_j25_3]

:   1. **Next** This will lock in your language selection and take you to the next step in the installation process. [18%, 90%, nw]

At this point, you'll be asked to agree to the GNU General Public License that Joomla! is released under. All you need to do here is select **Next** (point 1) if you agree to the license terms.

![][installation_j25_4]

:   1. **Database Type** Select your preferred database type (MySQLi, MySQL, PostgreSQL, or MSSQL) from the list. [35%, 46%, ne]
    2. **Host Name** Where is your database hosted? [41%, 46%, ne]
    3. **Username** What is your database username? [47%, 46%, ne]
    4. **Password** What is your database password? [53%, 46%, ne]
    5. **Database Name** What is the name of your new or existing database you wish to use for Joomla? [59%, 46%, ne]
    6. **Table Prefix** What would you like the table prefix to be for any Joomla tables in the database? [67%, 46%, ne]
    7. **Old Database Process** Do you want to back up or remove existing database information from previous Joomla installations? [75%, 46%, ne]

The fourth step of this process is also perhaps one of the most important. The **Database Configuration** page is where you enter the database type, host name, username, password, database name, and table prefix you would like to use for Joomla.

The **Database Type** field (point 1) offers you a list of supported database types you can use to connect to Joomla. For most users, MySQLi is the best choice, though you do have the option to stick with standard MySQL or alternatives including MSSQL and PostgreSQL.

Your web hosting provider should supply you with a **Host Name** (point 2) to place in the listed field. Most hosts use `localhost` as the host name, though some do request that databases be hosted from a different IP address.

Your host will also either issue or request that you register a username (point 3) and password (point 4) for database management. This can sometimes be "root", though not always. If you are running on a shared hosting plan, this name will likely be different. You can typically create new usernames and passwords through Cpanel or any other hosting management system.

The **Database Name** field (point 5) should be filled out to match the full name of your desired database. Some hosting providers allow Joomla to create a new database here by entering a database name that does not already exist on the server. Others will require that you create the database with the host prior to entering it in this field.

The **Table Prefix** field (point 6) is usually best left randomized, though instances where a single database may be used for a larger set of information or multiple applications can benefit from some recognizable association. Essentially, this prefix will appear prior to the name of a table created for the purposes of serving Joomla-specific information.

At the bottom of this page (point 7), you'll be asked if you wish to back up information presently existing on the database prior to installing Joomla. This is recommended if you have data you wish to preserve in the event that something goes wrong during installation. If you are creating a new database for this purpose, your decision here really does not make as much of a difference.

![][installation_j25_5]

The next step involves FTP configuration. Do not panic, this isn't a vital step in most cases. It is only really useful in the event that your server's configuration either prevents or requires that you upload media or install extensions through this method. Servers installed on a Windows operating system and most Linux setups generally do not require this step at all.

![][installation_j25_6]

:   1. **Site Name** What do you want the name of your site to be? [32%, 46%, ne]
    2. **Site Offline** This is where you determine whether the site should be online after installation, or made available to visitors right away. [55%, 46%, ne]
    3. **Username** What is your database username? [70%, 46%, ne]

The **Main Configuration** page is where you name your site (point 1) and set up your administrator account. Here, you can name your site and set up the meta description and keywords you wish to have search engines use to rank and list your content. You can also opt to have the site taken offline (login credentials required to view) while you work on it (point 2).

You'll need to enter an email address, username and password (point 3) before you can continue. This can (and should) be separate from your database and hosting username and password. This will be the login credentials you use to access the administrative side of your site. 

At the bottom of the next page, you have the option to load sample data to your site. This isn't a requirement for most users, though it can help with the initial configuration and application of templates and modules. Otherwise, you'll need to create content to fill in these spaces in order to see how your build will turn out. Once you have finished building your site, you can easily remove this sample data in favor of your own.

![][installation_j25_7]

:   1. **Site Name** What do you want the name of your site to be? [60%, 61%, se]

The final step in the process is aptly named "Finish." This page is where you remove the installation folder so your settings during initial setup are locked in. You will not be able to access your site until this step has been completed. Just select the *Remove Installation Folder* (point 1) and select either Site or Administrator to start building your new Joomla site.

![][installation_j25_9]

[installation_j25_1]: assets/installation_j25_1.png
[installation_j25_2]: assets/installation_j25_2.png
[installation_j25_3]: assets/installation_j25_3.png
[installation_j25_4]: assets/installation_j25_4.png
[installation_j25_5]: assets/installation_j25_5.png
[installation_j25_6]: assets/installation_j25_6.png
[installation_j25_7]: assets/installation_j25_7.png
[installation_j25_9]: assets/installation_j25_9.png