---
title: RokBridge
description: Your Guide to Using RokBridge for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!!RokBridge:RokBridge

---

Introduction
-----

RokBridge is a non-invasive, bi-directional bridge for Joomla and the forum platform phpBB3. By following a few simple sets, you can easily integrate the two platforms, providing registration, user syncing and syncing of login sessions.

Traditionally bridges for Joomla have been a variety of hacks in both the Joomla and the forum code base, resulting in a precarious solution that was prone to break with updates on either side. This is not the case with RokBridge due to its non-invasive characteristics. RokBridge has been developed with the help of key members of the phpBB3 team to ensure that no hacks are required on the Joomla or phpBB3 side. Everything just works.

Requirements
-----

RokBridge has the following requirements in order to operate:

* Joomla 2.5 or 3.x - ensure you are using the latest version.
* phpBB3

>> RokBridge is still in Beta and should be used for testing purposes only! Use on a live site only after thorough testing. We are not responsible for loss of data or other complications or other issues that may arise as a result of this extension. Use at your own discretion!

How Does it Work?
-----

The bridge is a Joomla application and not a Joomla component. This means that it runs in a standalone environment outside of Joomla. We have chosen this approach for performance reasons. 

Running phpBB3 inside Joomla would almost double the server load as both the Joomla CMS and phpBB3 applications would need to be booted up at the same time for each page request. For smaller forums this might not be a problem, but for large installations this would definitely be an issue. With the bridge running as a Joomla application, there is no visual integration. You must use a matching phpBB3 theme to ensure visual integration. The [RocketTheme phpBB3 Theme Club][theme] provides matching themes for many of our Joomla Templates.

Key Features
-----

* Non-invasive Joomla application
* Simple unified Joomla component based install & setup
* Powerful Joomla modules: Login, Latest Posts, Latest Members, Top Members, Online Members
* Uses Joomla authenticator and user synchronization system, which will allow for authentication via plugins such as openID, ldap, gmail, etc...
* Bi-directional syncing of registrations in either Joomla or phpBB3
* Synchronization of profile data
* Very little performance overhead compared to traditional bridges
* No Joomla or phpBB3 hacks required
* Joomla SEF capabilities trickle down to bridged forum

How to Install
--------------

>> NOTE: If you have installed a previous version of the bridge prior to 1.0RC6, you should first remove the phpBB3 User and phpBB3 Authentication plugins from your Joomla install. The new component will fail to install properly unless these two plugins are removed cleanly.

**Important**: As of **1.0RC14**, all modules are included in the installer package. With an existing installation all previous installed rokbridge modules as member, latest posts and login module must be removed.

#### Step One - Package Installation

The first thing you’ll need to do is [download][download] the latest version of RokBridge. The package you will download contains everything to get RokBridge up and running and it is compatible with both Joomla 2.5 and Joomla 3.x. It does not need to be uncompressed. 

Once you have downloaded the package, go into the Joomla Administrator and:

From Joomla 2.5:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `rokbridge.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

From Joomla 3.x:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `rokbridge.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

>> NOTE: For additional information on installing extensions, visit our detailed extensions installation guide located [here][install].

Once installation is complete, a message highlighted in green should indicate its successful completion.

### Step Two - Bridge Installation

When you visit the **RokBridge administrator component** in the Components menu, you will see the default configuration screen. The **Joomla User Plugin** and the **Joomla Authentication Plugin** should already be installed and activated. The next step is to choose a location for the phpBB3 bridge. This will effectively be the URL by which your community will visit your forum. By default this install path is set to "forum" and the default phpBB3 install path is set to "**distribution**". Just update the **Bridge Path** field in the RokBridge Configuration settings and click the **Save** button in the toolbar for the settings to take effect. 

>> **Warning**: The **Bridge Path** can NOT be the same as the phpBB3 Path. Do not use leading or trailing slashes.

![][rokbridge1]

To install the bridge in this location you have just chosen, simply click on the "**Install**" button in the Action column of the RokBridge Status section. At this point the bridge files are copied to this directory and the status section should show the bridge installed. We recommend using Joomla's FTP mode to allow the installer to copy and update the files with the correct permissions as needed.

>> NOTE: The RokBridge installer will create the bridge directory. The bridge cannot be installed into a pre-existing directory.

### Step Three - phpBB3 Installation

By default the phpBB3 path is set to `distribution`, but you can change this to any location you want for your phpBB3 installation. If you have phpBB3 previously installed (NOTE: must be under the Joomla directory), you can change the **phpBB3 Path** field to this directory name and click the save button. For example, if you have phpBB3 installed in "phpbb3_forum" directory, change the path to this and click the save button to save your configuration changes. If the path is a valid phpBB3 install, this will be recognized and shown in the **RokBridge Status** section below.

If you do not have phpBB3 installed yet, download the latest version from [phpBB.com][phpbb] and extract it into a directory of your choosing under your Joomla install. For example install the phpBB3 forum into `<Joomla Directory>/phpbb3`. Then point your browser to this directory and follow the installation instructions to fully install phpBB3. If you have any questions regarding the installation of phpBB3, please consult the [phpBB.com][phpbb] website. After you have successfully installed phpBB3, you can enter the directory you used into the **phpBB3 Path** field of the RokBridge Configuration.

### Step Four - phpBB3 Authentication Plugin

The next process is to install the **phpBB3 Authentictation Plugin**. Simply click on the "**Install**" link next to that item in the status area, and the authentication plugin will be copied to your phpBB3 install in the appropriate location. If you do not see an "**Install**" option in the action column you need to ensure that both the phpBB3 Bridge and the phpBB3 Forum are properly installed. The installation of the plugin now also auto-sets the phpBB3 authentication method in the phpBB3 configuration.

### Step Five - RokBridge Specific Indexes for phpBB3

This new step adds some database indexes on the phpBB3 tables that improve performance especially with the new RokBridge modules.

### Step Six - phpBB3 Patch

We have tried extremely hard to make this bridge as unintrusive as possible, however there are a couple of minor bugs in phpBB3 prior to 3.x.6 that require a minor code patch. This step modifies the phpBB3 functions.php and functions_admin.php files to fix these bugs. phpBB3's update mechanism will see this edit, and it will not cause a problem with future updates. We worked with the phpBB3 team to ensure these issues are resolved and do not require patching in versions 3.x.6 and greater.

![][rokbridge2]

All versions of phpBB3 use GET rather than POST in their advanced search form, this is addressed by editing the proSilver template directly and is a non-invasive minor patch. Simply click the Install button to add this bug fix.

### Step Seven - RokBridge Menu Item

In the **Menu Item Manager** for your menu of choice, you can either set up an External Link to your new bridged location, or you can create a **RokBridge Menu Item**. The RokBridge Menu Item basically acts as a redirect to your current bridge location and is a good option if you plan on changing your bridge location at some point.

[featured]: assets/rokbridge.jpeg
[download]: http://www.rockettheme.com/extensions-joomla/rokbridge
[rokbridge1]: assets/rokbridge_1.jpg
[rokbridge2]: assets/rokbridge_2.jpg
[gantrywidget]: assets/wp_RokBridge_gantrywidget.jpeg
[phpbb]: http://phpbb.com
[theme]: http://www.rockettheme.com/phpbb3
[install]: ../../platform/extensions.md