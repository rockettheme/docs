---
title: Sienna: Customizing Booking Form and Simple Booking Email Templates
description: Your Guide to Recreating Elements of the Sienna Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/sienna:Sienna

---

## Introduction

In this tutorial, we will show you how to customize your own email template using Simple Form, which is the application that is integrated into our **Simple Booking** or **Booking Form** particles.

## Customizing the Email Template

The first step to creating a new template to use with your **Booking Form** particle is to visit `https://getsimpleform.com/instructions?api_token=YOUR_TOKEN_HERE` (make sure YOUR_TOKEN_HERE is using your correct API).

The next thing you will want to do is select the orange button labeled **Form Settings** in the upper-right area of the page. Going there, you can place your customized email template in the **Body Template** field and select **Save**.

Here is an example of the content you can put in this field:

~~~ .html
Hello Mr. Example,
<br />
You received a message from {{Name}} ({{Email}}): <br />
<b>Title</b>:  {{Title}} <br />
<b>SubTitle</b>:  {{SubTitle}} <br />
<b>Description</b>:  {{Description}} <br />
<b>Price</b>:  {{Price}} <br />
<b>CheckInDate</b>:  {{CheckInDate}} <br />
<b>CheckOutDate</b>:  {{CheckOutDate}} <br />
<b>Adults</b>:  {{Adults}} <br />
<b>Children</b>:  {{Children}} <br />
~~~

You can change any aspect of this Body Template, the parts in the `{{ }}` are the areas that are generated from our particle. You can also adjust the email to add new information and/or customize the data as you wish.

It's also worth noting that the **Booking Form** does not use all of the items in our example. The **Title**, **Subtitle**, **Description**, and **Price** fields will be blank in the email if you do not remove them from your **Body Template** or add them when doing your own customizations to the particle.

