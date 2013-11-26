---
title: Acacia: Coming Soon
description: Your Guide to Creating Elements of the Acacia Template for WordPress
breadcrumb: /joomla:Joomla/!templates:Templated/acacia:Acacia

---

Introduction
-----

![][comingsoon]

Acacia introduces a **Coming Soon** page which allows you to display a stylish page indicating that your site is either being worked on or under construction. This page includes a countdown timer, your logo, and an area for text you can use to share any information you'd like to about the pending release.

You can also have users subscribe to a newsletter should you wish to email them and let them know when the site is up, as well as keep in touch to share regular updates and information.

How to Enable/Disable the Page
-----

The **Coming Soon** page can be enabled or disabled from the **Features** tab in **Template Manager**. You can opt to create an override for this page, or enable it on your primary template, accordingly. You can reach this option by navigating to **Administration -> Extension -> Template Manager -> Acacia -> Features** and turning **Coming Soon Page** on or off.

How to Make Changes
-----

Making changes to the Coming Soon page will require you to access a file and make manual changes yourself. It is not as difficult as it sounds. All of the changes you might want to make to this page can be done by visiting `/templates/rt_acacia/comingsoon.php` and altering its code. Some of the more common changes are listed below.

### Countdown Timer

Begin by visiting `/templates/rt_acacia/comingsoon.php` and make your way to **line 51**:

~~~ .html
var counter = new SimpleCounter('rt-comingsoon-counter',new Date(2013,9,1));
~~~

The date here `Date(2013,9,1)` is set for **October 1st, 2013**.

>> NOTE: The month in the Date object starts from 0, not 1, so if your website is launching in October, you need to set the month value to 9. Furthermore, 0 for January to 11 for December.

### Text

There is a block of text under the countdown timer in our default page. This block of text is located on **line 54**:

~~~ .html
<p class="rt-comingsoon-additional-message">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Donec eu libero sit amet quam egestas semper. Rerum, minus, totam iusto eligendi quas tenetur natus illum at dolor nam officia facilis aliquid eveniet vero nihil laudantium ab numquam obcaecati.</p>
~~~

Just replace the text between the `<p>` tags with the information you wish to have displayed here. You can remove this line to have no text appear in this area at all.

### Newsletter Subscription 

The subscription field and button are a standard form found between **lines 55 and 58**.

~~~ .html
					<form class="rt-comingsoon-form" action="#">
						<input type="text" onblur="if(this.value=='') { this.value='Email Address'; return false; }" onfocus="if (this.value=='Email Address') this.value=''" value="Email Address" size="18" alt="Email Address" class="inputbox" name="email">
						<a href="#" class="readon">Subscribe <span class="icon-signin"></span></a>
					</form>
~~~

[comingsoon]: assets/comingsoon.jpg