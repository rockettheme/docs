---
title: Paradigm: Coming Soon
description: Your Guide to Creating Elements of the Paradigm Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/Paradigm:Paradigm

---

Introduction
-----

![][comingsoon]

Paradigm introduces a **Coming Soon** page which allows you to display a stylish page indicating that your site is either being worked on or under construction. This page includes a countdown timer, your logo, and an area for text you can use to share any information you would like to about the pending release.

You can also have users subscribe to a newsletter should you wish to email them and let them know when the site is up, as well as keep in touch to share regular updates and information.

How to Enable/Disable the Page
-----

The **Coming Soon** page can be enabled or disabled from the **Gizmos** tab in **Theme Settings**. You can opt to create an override for this page, or enable it on your primary theme, accordingly. You can reach this option by navigating to **Administration -> Paradigm Theme -> Gizmos** and turning **Coming Soon Page** on or off.

How to Make Changes
-----

Making changes to the Coming Soon page will require you to access a file and make manual changes yourself. It is not as difficult as it sounds. All of the changes you might want to make to this page can be done by visiting `/themes/rt_Paradigm_wp/comingsoon.php` and altering its code. Some of the more common changes are listed below.

### Countdown Timer

You can set the countdown timer by navigating to **Admin -> Paradigm Theme -> Gizmos** and setting the date fields in the **Coming Soon Page** area of the page. The date you set here will be the date the countdown will expire.

### Text

There is a block of text under the countdown timer in our default page. This block of text is located on **line 54**:

~~~ .html
<p class="rt-comingsoon-additional-message">Paradigm supports a simple coming soon or offline style page with a time counter. It has been specifically styled to match the theme. This feature can be enabled in Admin Dashboard → Paradigm Theme → Gizmos → Coming Soon Page. You can customize this page by editing the comingsoon.php file inside the theme folder. Please visit <a href="http://www.rockettheme.com/">Paradigm tutorials</a> for more information.</p>
~~~

Just replace the text between the `<p>` tags with the information you wish to have displayed here. You can remove this line to have no text appear in this area at all.

### Newsletter Subscription 

The subscription field and button are a standard form found between **lines 81 and 88**.

~~~ .html
					<form class="rt-comingsoon-form" action="#">
						<input type="text" onblur="if(this.value=='') { this.value='Email Address'; return false; }" onfocus="if (this.value=='Email Address') this.value=''" value="Email Address" size="18" alt="Email Address" class="inputbox" name="email">
						<a href="#" class="readon">Subscribe <span class="icon-signin"></span></a>
					</form>
~~~

[comingsoon]: assets/comingsoon.jpeg