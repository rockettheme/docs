---
title: How Joomla Templates Work
description: Your Guide to Installing and Setting Up Joomla Templates
breadcrumb: /joomla:Joomla/!platform:Platform/!templates.md:How Joomla Templates Work

---

What is a Joomla Template?
-----

Joomla templates are basically the shell of your site. They are comprised of a series of files that determine the look and feel of a site once your content and modules have been put into place. A template determines things like fonts, colors, menu styles, navigation controls, basic layout design, and certain images such as the header and background (in some cases). A template isn't an entire website in and of itself at all. It is more accurately described as a base on which your site's appearance and layout are formed.

Templates offer you the ability to completely separate a site's content from its design. This enables you to quickly switch between templates with only a small amount of necessary changes in the backend versus having to completely rebuild the site from the ground up. A CMS, like Joomla, gives you this ability.

While some templates offer a great degree of control over layout to users, others can be significantly more rigid. Templates built on a framework that offers a great deal of user customization options, like Gantry, can extend on the built-in backend options Joomla offers in a way that empowers the user to rearrange and reconfigure a site's layout without having to modify the template's code directly.

You can also modify an existing template to appear slightly different depending on which page you are accessing. For example, many sites are designed with a different layout for the home page than a single article page. You might not want some features to appear in specific areas of your site. By [duplicating the template style](../basic/create_duplicate_template_styles.md) and assigning the adjusted layout to specific pages, you can do this fairly easily.

How to install a Joomla template
-----

There are several different ways to install a Joomla template from RocketTheme. You can start your Joomla install from scratch (including building a new database) by downloading the RocketLauncher for your desired template. This will give you everything you need to hit the ground running, including a preconfigured version of the demo for the specific theme, the Gantry framework, and any extensions required for the theme's demo build to work. 

If you have an existing site running a Gantry-enabled template, you just need to download and install the standalone template along with any required and/or recommended extensions listed on the template's product page.

If you have an existing site, but have not yet installed the Gantry library, you can grab a bundle download that takes the standalone version a bit further by adding Gantry framework.


### Installing a Template Using RocketLauncher

RocketLauncher is a working copy of our demo site which you can install on your own server and bring live within minutes. This is essentially a demo replica which you can modify to create a robust site that fits your individual needs.

You can find the RocketLauncher file by visiting the main template page and selecting **Download**. RocketLauncher packages may be available for different versions of Joomla. This gives you a choice between the slightly older yet more widely supported Joomla 2.5 (J25) or the newer and slightly less extension-supported Joomla 3.x. If you have a set of extensions in mind that you wish to use on your site that do not presently support the latest version of Joomla, then packages labeled J25 in the download page will probably be the best choice for you. You can always update your Joomla installation, as well as other components of the site, within the Administrator area.

After you have downloaded the RocketLauncher ZIP file, you can unpack it. This will give you a directory filled with the files you will need to install Joomla and the RocketTheme template on your site. A more recommended method involves uploading the ZIP file directly to your server and unpacking it there. This reduces the probability of file corruption and makes for a faster uploading process. Not all hosts allow this, so check with yours to see if this is an option.

Simply upload these files and subdirectories to your server's root web hosting directory. This is usually done via FTP/SFTP though your individual host may have other options available to you. 

Once these files are in place, you can finish installation using your browser by visiting the URL you have elected to have your Joomla installation installed. This could be the root of your domain (http://example.com) or a subdirectory (http://example.com/joomla) depending on where you placed it in your server's file system.

At this point, you will access the Joomla Web Installer to complete installation. We have step-by-step guides for installing a [Joomla 2.5][joomla25] or [3.x][joomla3x] site available to take you through the remainder of the installation process.

### Installing a Template Bundle

Assuming that you already have Joomla installed and just wish to change your existing site over to a RocketTheme template using Gantry Framework, the bundle installation option is probably going to be what you are looking for. This bundle includes the template itself in addition to Gantry, so you can hit the ground running with a single installation package.

>> Note: The Bundle template is only necessary if the Gantry Library is not installed at `/components/com_gantry`.

You can find this bundle package on all Gantry-supported template download pages. Simply download the bundle ZIP file and install it to your existing Joomla site. 

![][install1]

:   1. **Extension Manager** This is where you will want to go to install any extensions. [18%, 59%, se]

The easiest way to do this is by going to **Admin → Extensions → Extension Manager** (point 1) within the Administrator area of your site. 

![][install2]

:   1. **Install** This sidebar indicates which area within the Extension Manager you are in. [37%, 13%, nw]
    2. **Browse** Locate the template's ZIP file on your local drive. [60%, 91%, sw]
    3. **Upload and Install** This will begin installation of your new template. [71%, 42%, ne]

Once you have done this, you should be at an installation page (indicated by the sidebar in the image above). From here, you will need to select **Browse** (point 2) and choose your template package zip file you downloaded previously. After you have made your selection, hit **Upload and Install** (point 3). Joomla will automatically unzip the package and install its components for you. 

![][install3]

Once this is done, a series of green messages will appear on the upload page indicating that the template, and any included components, have been successfully installed.

The downloads page for the template might indicate one or more extensions are required for it to operate properly. These extensions will be linked on the downloads page. You can install them using the same process listed above.

![][install4]

:   1. **Default** Selecting the star will set the template as default template for the visitors side of your Joomla site. [75%, 70%, ne]

Once you have successfully installed the bundle, you can navigate to **Admin → Extensions → Template Manager** and select the star next to your new template (point 1) to set it as the default template for the front end of your site.

### Installing a Standalone Template

The standalone template is the bare bones of the template itself. If you already have the Gantry Library installed on your site, then adding another Gantry-enabled template is just a matter of selecting the standalone ZIP file from the template's downloads page and uploading it via the administrative extensions uploader as described previously.

### Other Available Files

There are several other files that you might find useful on the template's download page. For example, the **Source PNG(s)** including some of the image files exclusive to the template are made available so that you may customize them to meet your individual needs. 

While these files are not directly intended to be installed on your Joomla site, they can serve as a useful resource for further customization and understanding of what went into creating the template.

[joomla25]: install_joomla25.md
[joomla3x]: install_joomla3x.md
[install1]: assets/template_install_1.png
[install2]: assets/template_install_2.png
[install3]: assets/template_install_3.png
[install4]: assets/template_install_4.png