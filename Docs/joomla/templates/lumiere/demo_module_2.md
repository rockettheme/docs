---
title: Lumiere: Recreating the Demo - Search Our Site Title
description: Your Guide to Recreating Elements of the Lumiere Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lumiere:Lumiere

---

Search Our Site Title
-----
![][demo]

:   1. **mod_custom** [40%, 10%, se]

This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSISYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                            |
| :--------- | :----------------------------------------------------------------- |
| Title      | `Search Our Site Title`                                            |
| Show Title | Hide                                                               |
| Position   | footer-a                                                           |
| Status     | Published                                                          |
| Access     | Public                                                             |
| Language   | All                                                                |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="fp-search-title">Search Our Site</p>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                       |  
| :------------------ | :---------------------------- |  
| Module Class Suffix | `fp-search`                   |    

[demo]: assets/demo_1.jpeg
[demo2]: assets/searchtitle_1.jpeg
[demo3]: assets/searchtitle_2.jpeg
[demo4]: assets/searchtitle_3.jpeg