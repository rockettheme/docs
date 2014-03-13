---
title: Mercado: Recreating the Demo - New Sidepanel Layout
description: Your Guide to Recreating Elements of the Mercado Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/mercado:Mercado

---

New Sidepanel Layout
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                |  
| :--------- | :--------------------- |  
| Title      | `New Sidepanel Layout` |  
| Show Title | Show                   |  
| Position   | mainbottom-b           |  
| Status     | Published              |  
| Access     | Public                 |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<p>The <strong>Sidepanel</strong> is forced to appear on all pages with, the
mainbody area being locked into a <strong>9-grid layout</strong>.</p>

<div class="attention-style">
    <div class="inner">
        <strong>NOTICE:</strong> The sidepanel can be disabled on a <a href=
        "index.php?option=com_content&amp;view=article&amp;id=48&amp;Itemid=55">
        per-menu-item basis</a>.
    </div>
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

| Option              | Setting  |  
| :------------------ | :------- |  
| Module Class Suffix | `title2` |  

[demo]: assets/demo_10.jpeg
[demo2]: assets/demo_10a.jpeg
[demo3]: assets/demo_10b.jpeg
[demo4]: assets/demo_10c.jpeg
