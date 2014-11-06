---
title: Somaxiom: Recreating the Demo - 3rd Party Extensions Support
description: Your Guide to Recreating Elements of the Somaxiom Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/somaxiom:Somaxiom

---

3rd Party Extensions Support
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |            Setting             |
| :--------- | :----------------------------- |
| Title      | `3rd Party Extensions Support` |
| Show Title | Show                           |
| Position   | feature-c                      |
| Status     | Published                      |
| Access     | Public                         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<em class="rt-typoblock">JomSocial - Community Component</em>
<p>A community based third party addon that offers social networking capabilities to the Joomla.</p>

<em class="rt-typoblock">K2 - Content Construction Kit</em>
<p>A CCK (content construction kit) platform that extends Joomla well beyond its basic functions.</p>

[readon2 url="#"]Read More[/readon2]
<div class="clear"></div>
~~~

### Options

![][demo3]

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

|        Option       | Setting |
| :------------------ | :------ |
| Module Class Suffix | `tab3`  |

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg