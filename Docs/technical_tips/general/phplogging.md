---
title: How to Turn Up PHP Error Logging Levels
description: PHP error logging is an important component of any comprehensive troubleshooting strategy. 
breadcrumb: /technical_tips:Technical Tips/!phplogging:PHP Logging

---

Introduction
----

When building or maintaining a site powered by PHP, errors can happen. These errors can cause issues that are often difficult to pinpoint or accurately troubleshoot without error logging in place.

These logs are also useful in cases where a problem is sporadic or difficult to replicate. Instead of spending hours trying to recreate the error, you can check the logs and uncover the issue fairly quickly.

In this guide, we will go over a few ways to turn up the logging levels so you can see errors that might not appear in these logs at their default settings.

Enabling PHP Error Logging Through htaccess
------

Depending on your hosting provider, you may be able to activate private PHP error logging using the htaccess file. This file acts like a doorman, allowing certain traffic through, directing traffic when exceptions are needed, and preventing access to secured areas of your site's file structure to unauthorized parties, and more.

If you want to enable private PHP error logging using this file, you will need to add the code below to either your htaccess file, or httpd.conf (a common configuration file found on Apache).

~~~ .html
php_flag  log_errors on
php_value error_log  /home/path/public_html/(your domain)/PHP_errors.log
~~~

The last row of the above text should be adjusted to match the actual location of the **PHP_errors.log** file. If one does not already exist in your site's root directory, you can create it using a text editor. Set the permissions to this file to `755`. If required, you can set this file's permission level to `777`.

Once this is done, you should start seeing error log entries appear in the file, which you can read using a standard text editor like Notepad or TextEdit. Keep in mind that if you do nothing else, this log file may be accessible by the public.

Enabling PHP Error Logging Through Apache GUI
-----

![][apacheerrors]

If you are building your site on a local Apache server, or hosting it from a machine and prefer to use GUI tools, Apache makes it easy to turn on and configure PHP error logging. To do this, you need to open the Apache server application (in the case pictured above, MAMP Pro) and click the **PHP** tab.

From here, you will see a section titled **Error Handling**. Simply select the types of errors you want to log (we recommend **All Errors and Warnings**) and where you want the log file saved. You can access this log at any time by navigating to it in your file manager, or selecting **View Log** in the server GUI. 

Enabling PHP Error Logging Through php.ini
-----

Setting up error logging in php.ini works the same way as it does through htaccess. It's the more common solution, as this file handles all PHP configuration for your server. To initiate logging, and turn off error display to visitors, enter the following code in your php.ini file.

~~~ .html
display_errors = Off
log_errors = On
error_log = /var/log/php-errors.log
~~~ .html

If the log file listed above does not exist, or you would like to have the log appear in another location on your site's local directory, you can create the file and/or adjust the log location as stated in the `error_log` line in the above text. This file should be writable by **www-data**.

How to Prevent Unauthorized Access to the Log File
-----

Chances are, you don't want the public to have the ability to read your log files from the comfort of their browsers. You can (and should) secure this file using htaccess permissions. This can be done by adding the code below to your htaccess file.

~~~ .html
<Files PHP_errors.log>
 Order allow,deny
 Deny from all
 Satisfy All
</Files>
~~~

You can still access this file remotely from within the site's file directory using a secured file transfer system such as SFTP.

How to Prevent PHP Error Notifications to Visitors
-----

No one wants to see a PHP error notification pop up when they're browsing the Web. For many folks that don't really understand what these errors mean, it can actually be very concerning. Likewise, you probably don't want errors on your site to show up at all when someone visits your site.

You can actually disable these via the htacces file located in your site's root directory. Just add the following code to shut off PHP error notifications on the frontend. This won't have any affect on the private error logging mentioned previously in this guide.

~~~ .html
php_flag display_startup_errors off
php_flag html_errors off
php_flag display_errors off
~~~

You can also disable error display to visitors through your site's php.ini file. To do so, enter the following text in the php.ini file.

~~~ .html
display_errors = Off
~~~

Adding this bit of text should eliminate the presence of PHP errors for visitors of your site. Keep in mind that functional errors will still cause issues, and your visitors will not be able to give you any information beyond reporting the problem.

[firefoxwebdeveloper]: https://addons.mozilla.org/en-US/firefox/addon/web-developer/
[firebug]: https://addons.mozilla.org/en-US/firefox/addon/firebug/
[chromewebdeveloper]: https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm
[apacheerrors]: assets/apache_errors.jpg