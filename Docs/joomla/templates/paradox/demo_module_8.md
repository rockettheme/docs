---
title: Paradox: Recreating the Demo - Ajax Article Loading
description: Your Guide to Recreating Elements of the Paradox Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/paradox:Paradox

---

Ajax Article Loading
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                |  
| :--------- | :--------------------- |  
| Title      | `Ajax Article Loading` |  
| Show Title | Show                   |  
| Position   | bottom-a               |  
| Status     | Published              |  
| Access     | Public                 |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p class="nomarginbottom">The feature loads articles in an ad hoc manner via <strong>Ajax</strong>. This means additionally articles will only load once the <strong>Load More Articles</strong> button is pressed.</p>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting              |  
| :------------------ | :------------------- |  
| Module Class Suffix | `title4 flushbottom` |  

[demo]: assets/demo_8.jpeg
[demo2]: assets/demo_8a.jpeg
[demo3]: assets/demo_8b.jpeg
[demo4]: assets/demo_8c.jpeg
