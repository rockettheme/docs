---
title: Spectral: Coming Soon
description: Your Guide to Creating Elements of the Spectral Template for WordPress
breadcrumb: /joomla:Joomla/!templates:templates/spectral:Spectral

---

Introduction
-----

![][comingsoon]

Spectral introduces a **Coming Soon** page which allows you to display a stylish page indicating that your site is either being worked on or under construction. This page includes a countdown timer, your logo, and an area for text you can use to share any information you would like to about the pending release.

You can also have users subscribe to a newsletter should you wish to email them and let them know when the site is up, as well as keep in touch to share regular updates and information.

How to Enable/Disable the Page
-----

![][comingsoon2]

The **Coming Soon** page can be enabled or disabled from the **Features** tab in **Template Manager**. You can opt to create an override for this page, or enable it on your primary template, accordingly. You can reach this option by navigating to **Administration -> Extensions -> Template Manager -> Spectral -> Features** and turning **Coming Soon Page** on or off.

How to Make Changes
-----

Making changes to the Coming Soon page will require you to access a file and make manual changes yourself. It is not as difficult as it sounds. All of the changes you might want to make to this page can be done by visiting `/templates/rt_Spectral/comingsoon.php` and altering its code. Some of the more common changes are listed below.

### Countdown Timer

You can set the timer by visiting the **Features** tab within the **Template Manager**. Navigate to **Administration -> Extensions -> Template Manager -> Spectral -> Features** and find the date settings within the **Coming Soon Page** section. Here, you can set the end date by entering the day, month, and year you want the timer to expire. Setting the **Show** option to **On** will turn the page on.

### Email Subscription 

To enable or disable the sample email subscription form, you can navigate to **Administrator -> Extensions -> Template Manager -> Spectral -> Features -> Email Subscription** to turn it on or off. By setting this option to **On**, you are turning on the email subscription form in both the **Offline** and **Coming Soon** pages.

### Language 

We have also added a number of language constants to display the text for the Coming Soon page. For example, in the same **rt_spectral/comingsoon.php** file you should see language constants such as: 

~~~ .html
'RT_COMINGSOON_TITLE', 'DAY', 'SECOND', 'MINUTES', 'RT_SUBSCRIBE'
~~~

These constants are defined in **rt_spectral/language/en-GB/en-GB.tpl_rt_spectral.ini**. For example, you should see: 

~~~ .html
RT_COMINGSOON_TITLE="Our Website is Coming Soon"
RT_COMINGSOON_MESSAGE="Spectral supports a simple coming soon or offline style page with a time counter. It has been specifically styled to match the template. This feature can be enabled in Template Manager &rarr; Spectral &rarr; Features &rarr; Coming Soon Page. You can customize this page by editing the comingsoon.php file inside the template folder. Please visit <a href='http://www.rockettheme.com/forum/index.php?f=821&amp;t=210469&amp;rb_v=viewtopic'>this tutorial</a> for more information."
RT_AUTHORIZED_LOGIN_MESSAGE="This feature hides your Joomla site behind the Coming Soon page with its Countdown timer. You can still access the frontend of the site by logging in as an administrator below. You can customize this message in the Spectral template language file."
~~~

To override any of these constants, visit your Joomla admin and go to **Extensions -> Language Manager -> Overrides -> New**.

In the **Language Constant** inputbox, put any constant you wish to override, such as: 

~~~ .html
RT_COMINGSOON_TITLE
RT_COMINGSOON_MESSAGE
~~~

Once this is done, place your desired text in the Text box to display your text.

[comingsoon]: assets/comingsoon.jpg
[comingsoon2]: assets/comingsoon2.jpg