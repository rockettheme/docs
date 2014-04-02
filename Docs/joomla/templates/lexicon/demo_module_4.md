---
title: Lexicon: Recreating the Demo - Navigation Options
description: Your Guide to Recreating Elements of the Lexicon Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lexicon:Lexicon

---

Navigation Options
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                                                                            |  
| :--------- | :--------------------------------------------------------------------------------- |  
| Title      | `Navigation Options[span class="rt-title-tag"]Menu Systems for All Devices[/span]` |  
| Show Title | Show                                                                               |  
| Position   | content-top-a                                                                      |  
| Status     | Published                                                                          |  
| Access     | Public                                                                             |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <p class="nomarginbottom">&nbsp;</p><span class=
            "rt-circle-number">1</span>
            <h4>Dropdown Menu</h4>
            <p>An advanced CSS based multi-level dropdown system.</p>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <p class="nomarginbottom">&nbsp;</p><span class=
            "rt-circle-number">2</span>
            <h4>SplitMenu</h4>
            <p>A static menu with child menu items placed in the sidebar.</p>
        </div>
    </div>
    <div class="gantry-width-33">
        <div class="gantry-width-spacer">
            <p class="nomarginbottom">&nbsp;</p><span class=
            "rt-circle-number">3</span>
            <h4>Mobile Menus</h4>
            <p>Options for a selectbox or side tree panel menu <span class=
            "hidden-tablet">for mobile</span>.</p>
        </div>
    </div>
</div>
<div class="clear">
    &nbsp;
</div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                            |  
| :------------------ | :--------------------------------- |  
| Module Class Suffix | `fp-content-top-01 rt-title-large` |   

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_4a.jpeg
[demo3]: assets/demo_4b.jpeg
[demo4]: assets/demo_4c.jpeg
