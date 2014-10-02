---
title: Omnicron: Recreating the Demo - Service Updates
description: Your Guide to Recreating Elements of the Omnicron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/omnicron:Omnicron

---

Service Updates
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting            |
| :--------- | :----------------- |
| Title      | `Service Updates`  |
| Show Title | Show               |
| Position   | bottom-a           |
| Status     | Published          |
| Access     | Public             |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-block rt-demo-typo-block">
  <strong>OFFLINE:</strong> <em>31.08.10 @ 12:31 EST</em>. Sharing hosting servers are currently disabled due to a backup error. <a href="#">http://bit.ly/bWZUiKq</a>
</div>
<div class="rt-block rt-demo-typo-block">
  <strong>RESTORED:</strong> <em>29.08.10 @ 18:53 EST</em>. Email has been restored. All received messages are now synced. <a href="#">http://bit.ly/cWXUiFt</a>
</div>
<div class="rt-block rt-demo-typo-block">
  <strong>OFFLINE:</strong> <em>28.08.10 @ 23:14 EST</em>. Our email system is down. Backup servers are trapping all sent emails. <a href="#">http://bit.ly/wQDSpKl</a>
</div>
~~~

### Basic

![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting        |
| :------------------ | :------------- |
| Module Class Suffix | `box4`         |

[demo]: assets/demo_3.jpeg
[demo2]: assets/demo_3a.jpeg
[demo3]: assets/demo_3b.jpeg
[demo4]: assets/demo_3c.jpeg
