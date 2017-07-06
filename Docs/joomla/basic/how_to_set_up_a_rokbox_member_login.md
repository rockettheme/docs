---
title: How to Set Up a RokBox Member Login
description: Your guide to setting up a RokBox Member Login for your Joomla site.
breadcrumb: /joomla:Joomla/!basic:Basic Tutorials/!how_to_set_up_a_rokbox_member_login.md:How to Set Up a RokBox Member Login

---

Introduction
-----

Setting up a RokBox member login is a great way to add quick and easy visual appeal to the process of logging in for your site's members. It only takes a few minutes to set up.

>> Note: Before following the instructions below, make sure you have the latest version of [RokBox Plugins][rokbox] for Joomla 3.x installed. Once installed, confirm that they are enabled in the Plugin Manager by navigating to **Extensions → Plugin Manager**.

Here are the steps you will want to take to set up the RokBox login for your site.

![][login1]

1. In your Administrator panel, navigate to **Extensions → Template Manager** and select your default RocketTheme template.

2. In the template parameter, set the **Login Panel** option to **On**.

3. Set the position to where you would like the login button to appear on your site. You can also set the button text that will appear before and after a member has logged in to your site.

4. **Save** your changes and close the **Template Manager**. 

5. Navigate to **Extensions → Module Manager** and search for **login**. If you do not see a module called **mod_login** you can create a new module and select `Login` as its type.

6. Assign it to the `login` module position and assign it to all pages. Even if you do not wish to have the login button appear on all pages, this particular module will only appear when it is called.

7. **Save** your changes and publish the module.

[login1]: assets/login_1.jpeg
[login2]: assets/login_2.jpeg
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox