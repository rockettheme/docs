---
title: RokCandy - User Guide
description: Your Guide to Using RokCandy for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/rokcandy:RokCandy

---

How to Configure RokCandy
-----

![][rokcandy1]

RokCandy is distributed with default snippets for a variety of logical purposes such as article and module titles. However, Joomla offers its templates the capacity to override the platform's core. In this manner, we can add files to the template that will override the snippets in RokCandy. Therefore, you can quickly add and edit your own macros without modifying core files. 

![][rokcandy2]

Also, you can add and control your own in the Administrator: **Components -> RokCandy**. They will appear in the following format:

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

RokCandy Use in RocketTheme Template Demos
-----

Many of our demos feature content that takes advantage of RokCandy. By using `[span]` tags in module titles and other areas where HTML code may not be easily injected, we can quickly reference custom CSS classes that change the way this content appears on the frontend.

There is one additional macro that you will need to add to RokCandy in order to properly replicate demo content that uses custom CSS class spans in module titles.

To create this macro in RokCandy, simply click the green **New** button in the upper-left area of the RokCandy Manager page. From here, you will need to enter the following information.

In the Macro field, enter:

~~~ .html
[span class="{class}"]{text}[/span]
~~~ 

In the HTML field, enter:

~~~ .html
<span class="{class}">{text}</span>
~~~

Once this macro has been saved and published, you should be able to replicate any demo content that features the `[span]` macro tag in its content.

>> NOTE: You are only able to use a single macro in a given string of text. If you need multiple classes in a single macro, place them in a new macro and use them accordingly.

[rokcandy1]: assets/rokcandy_1.jpeg
[rokcandy2]: assets/rokcandy_2.jpeg
