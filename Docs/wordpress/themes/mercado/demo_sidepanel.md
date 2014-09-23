---
title: Mercado: Recreating the Demo - Side Panel
description: Your Guide to Recreating Elements of the Mercado Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/mercado:Mercado

---

Side Panel Section
-----

![][demo]

:   1. **Text** [6%, 17%, se]
    2. **RokNewsPager** [23%, 17%, se]
    3. **Gantry Login Form** [55%, 17%, se]
    4. **Gantry Links** [78%, 17%, se]

Here is the widget breakdown for the Side Panel section:

* Text
* RokNewsPager
* Gantry Login Form
* Gantry Links

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p><strong>Mercado</strong>, the <strong>September</strong> 2011 release, is the epitome of elegant <strong>eCommerce</strong> integration, with its contemporary, <strong>refined</strong> visuals, style and structure. </p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Enter `Welcome` in the **Title** field.
* Set the **Title Variation** option to **Title 4**.
* Leaving everything else at its default setting, select **Save**.

#### RokNewsPager

This area of the demo is a RokNewsPager widget. RokNewsPager is no longer supported by RocketTheme. Many of its features and functionality have been integrated into [RokSprocket][roksprocket].

#### Gantry Login Form

The login form located on the front page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option          | Setting      |  
| :-------------- | :----------- |  
| Title           | `Login Form` |  
| User Greeting   | Hi,          |  
| Title Variation | Title 3      |  

#### Gantry Links

The **Gantry Links** widget is used to display links in a way that works natively with the Gantry framework. It is a great alternative to the default WordPress blogroll widget. Links are controlled via the native **Links** feature in WordPress. You will find the options used in our demo below.

| Option                | Setting       |
| :-------------------- | :------------ |
| Title                 | `Blogroll`    |
| Links Category        | Blogroll      |
| Show Link Image       | Checked       |
| Show Link Name        | Checked       |
| Show Link Description | Unchecked     |
| Show Link Rating      | Unchecked     |
| Categorize            | Unchecked     |
| Categories Order By   | Name          |
| Links Order By        | Name          |
| Limit Links           | 2             |
| List Class            | menu          |
| Category Class        | link_category |
| Title Variation       | Title 4       |

[roksprocket]: ../../plugins/roksprocket/
[demo]: assets/demo_4.jpeg
