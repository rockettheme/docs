---
title: RokFeatureTable
description: Your Guide to Using RokFeatureTable for WordPress
breadcrumb: /wordpress:WordPress/plugins:Plugins/rokfeaturetable:RokFeatureTable

---

Widget Options
-----
You can access RokFeatureTable's main widget settings by navigating to **Admin -> Appearance -> Widgets -> RokFeatureTable**. Any changes you make here will be reflected in a single occurrence of the RokFeatureTable widget on the frontend of your site.

![][widget1]

:   1. **Title** Sets the title for the RokFeatureTable widget. This is not a required field. [26%, 12%, ne]
    2. **Highlight Column** This option sets the column number you wish to have highlighted by default. This is typically a column or product you wish to bring attention to. [35%, 12%, ne]
    3. **Built-in CSS** RokFeatureTable comes with a default style that integrates well with many WordPress themes. If you want to use your own, or if the theme you are using supports a custom style, you might want to set this param to No. [45%, 12%, ne]
    4. **Template Selection** RokFeatureTables has the ability to import predefined templates from both the plugins folder, or your theme. RokFeatureTable comes with two predefined templates as examples: Browsers and Price Table. [55%, 12%, ne]
    5. **Current Table Layout** This area of the menu sets the size and content of the feature table. It is the most important component of the widget setup process. More details about this menu are located in the [Table Layout](rokfeaturetable_use.md#table-layout) section below. [70%, 12%, ne]

1. **Title**: Sets the title for the RokFeatureTable widget. This is not a required field.

2. **Highlight Column**: This option sets the column number you wish to have highlighted by default. This is typically a column or product you wish to bring attention to.

3. **Built-in CSS**: RokFeatureTable comes with a default style that integrates well with many WordPress themes. If you want to use your own, or if the theme you are using supports a custom style, you might want to set this param to No.

4. **Template Selection**: RokFeatureTables has the ability to import predefined templates from both the plugins folder, or your theme. RokFeatureTable comes with two predefined templates as examples: Browsers and Price Table.

5. **Current Table Layout**: This area of the menu sets the size and content of the feature table. It is the most important component of the widget setup process. More details about this menu are located in the [Table Layout](rokfeaturetable_use.md#table-layout) section below.

Table Layout
-----
You can access the table layout options via the widget properties menu featured above. This tool allows you to create and fill your feature table with information that includes everything from basic text to custom CSS classes, subline text, links, and styles.

![][widget2]

:   1. **Columns** You can add or remove columns to your feature table. Columns can be individually highlighted to emphasize the included content. [21%, 5%, ne]
    2. **Rows** Each column can have an independent number of rows. You can add or remove rows using the **+** or **-** controls. Each row within a column acts as a single cell. [29%, 49%, sw]
    3. **Class** You can use the class control to add a unique CSS class to the cell. [29%, 56%, sw]
    4. **Subline** This option allows you to add a sub-line of text to the cell. This is useful for disclaimers or extra information. [29%, 64%, sw]
    5. **Link** You can have a particular cell link to a specific URL. [29%, 72%, sw]
    6. **Style** This option allows you to assign custom style rules to the cell. [29%, 80%, sw]

1. **Columns** You can add or remove columns to your feature table. Columns can be individually highlighted to emphasize the included content.

2. **Rows** Each column can have an independent number of rows. You can add or remove rows using the **+** or **-** controls. Each row within a column acts as a single cell.

3. **Class** You can use the class control to add a unique CSS class to the cell.

4. **Subline** This option allows you to add a sub-line of text to the cell. This is useful for disclaimers or extra information.

5. **Link** You can have a particular cell link to a specific URL.

6. **Style** This option allows you to assign custom style rules to the cell.

Custom Templates
-----
Creating custom templates is very easy. You just need your favorite text editor and some knowledge on how the syntax is. Below an example of custom template that we are going to cover on all its aspects.

~~~ .html
name::padding-top:10px;|Firefox
name-sub::Gecko Engine
name-classes::class2 class3
button-text::Download
button-text-sub::free
button-text-link::http://www.mozilla.com/en-US/firefox/all.html
---
name::padding-top:10px;|Chrome
name-sub::WebKit Engine
name-classes::class2 class3
button-text::Download
button-text-sub::free
button-text-link::http://www.google.com/chrome
---
name::padding-top:10px;|Safari
name-sub::WebKit Engine
name-classes::class2 class3
button-text::Download
button-text-sub::free
button-text-link::http://www.apple.com/safari/download/
---
name::padding-top:10px;|Opera
name-sub::Presto Engine
name-classes::class2 class3
button-text::Download
button-text-sub::free
button-text-link::http://www.opera.com/browser/
~~~

Each Column is separated by 3 dashes `---`, so every time you are done writing rows, to 'switch' to another column, just add `---`.

To create a row, or even better, a cell, you start typing the class name of the reference followed by two colons `::`. Let's ignore all the columns and let's just take as reference the first one. Even without knowing the syntax, yet, you can easily tell all the columns and rows are equals, what makes them difference are just the values, but not the structure.

~~~ .html
name::padding-top:10px;|Firefox
name-sub::Gecko Engine
name-classes::class2 class3
button-text::Download
button-text-sub::free
button-text-link::http://www.mozilla.com/en-US/firefox/all.html
~~~

So, as said earlier, we started writing a cell `name::padding-top:10px;|Firefox`. This translated means: "Create a cell, use as referenced class name 'name', add some in-line styling `padding-top:10px;` and use **Firefox** as text of the cell.

In the case that you want that cell to have a subline, the next line of the code would contain something like: `name-sub::Gecko Engine`. As you can see, 'name' has been kept for referencing to the 'name' cell, but we added a new keyword `-sub`. That's what lets RokFeatureTable know that our second line in the code needs to be a subline of 'name'. Translation: "In the cell that has 'name' as reference class add a subline with the text 'Gecko Engine'".

Now, let's say we want our cell to have additional classes. To do so, follow the same rules of '-sub', we write: `name-classes::class2 class3`, which translates to: "In the cell that has 'name' as reference class, I also need other classnames: `class2` and `class3`".

What follows is not prefixed by any 'name' anymore. That means we are done with the 'name' cell and we are switching to a new one, 'button-text'.

Everything is exactly as in 'name' cell, except we have a new keyword, `-link`.

NOTE: All the referenced cells allows HTML syntax, if instead of just plain "Firefox" (in the example above), we wanted a bold, red and italic "Firefox" (Firefox) this is how we would have written our cell: `name::padding-top:10px;|<strong style="color:red;"><em>Firefox</em></b>`

[featured]: assets/rokintroscroller.jpeg
[settings]: assets/wp_rokintroscroller_widget.jpeg
[widget1]: assets/wp_rokfeaturetable_widget_1.jpeg
[widget2]: assets/wp_rokfeaturetable_widget_2.jpeg