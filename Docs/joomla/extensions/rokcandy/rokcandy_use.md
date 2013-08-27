---
title: RokCandy - User Guide
description: Your Guide to Using RokCandy for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/rokcandy:RokCandy

---

How to Configure RokCandy
-----
![][rokcandy1]

RokCandy is distributed with default snippets for a variety of logical purposes such as for content title. However, Joomla 1.5 offers its templates the capacity to override the core of Joomla. In this manner, we can add files to the template that will override the snippets in RokCandy. Therefore, you can quickly add and edit your own macros without modifying core files. 

The file is called **default.ini** and, if you are using a RocketTheme template which uses RokCandy, it will be located in the `/templates/rt_TEMPLATE_NAME_j15/html/com_rokcandy/` directory. However, if the folder does not exist, you will have to create the necessary folders as shown in the path above and create a new file named default.ini. 

![][rokcandy2]

Also, you can also add and control your own in the Administrator: **Components → RokCandy**. They will appear in the following format:

~~~
[tag]{text}[/tag]=<tag>{text}</tag>
~~~

Such as

~~~
[alert]{text}[/alert]=<span class="alert">{text}</span>
~~~

As is apparent, each line is separated into distinctive sections. There are two parts, the RokCandy syntax (left of =) and the outputted HTML (right of =). You would create your own tag name and insert them between square brackets, [], followed by {text} and the closing tag with [] brackets again. This segment is followed by the = symbol and following on from that is the HTML output. Note, the {text} is required in both parts to denote what element is to be carried forward. You can use any value between the {} brackets, such as {title} or {link} as long as they are cross referenced in the HTML output as shown in the example below:-

~~~
[box title={title} link={link}]{text}[/box]=<div class="box"><h3><a href="/{link}">{title}</a></h3><p>{text}</p></div>
~~~

[rokcandy1]: assets/rokcandy_1.jpeg
[rokcandy2]: assets/rokcandy_2.jpeg