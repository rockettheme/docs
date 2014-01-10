---
title: Momentum: Recreating the Demo - Initial Template Setup
description: Your Guide to Recreating Elements of the Momentum Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/momentum:Momentum

---

Initial Template Setup
-----

![][demo]

This area of the front page is a standard **mod_custom** module. The settings we used in the demo are listed below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                  |  
| :--------- | :----------------------- |  
| Title      | `Initial Template Setup` |  
| Show Title | Show                     |  
| Position   | sidebar-a                |  
| Status     | Published                |  
| Access     | Public                   |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div>
    <p class="dropcap2">1</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=113"><span class="heading1 nomargintop nomarginbottom">Essential Downloads</span></a>
    <span>Download the template and peripheral files from RocketTheme.com.</span>
</div>

<div>
    <p class="dropcap2">2</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=116"><span class="heading1 nomargintop nomarginbottom">Style Configuration</span></a>
    <span>Customize the existing presets to your only personal preference and save.</span>
</div>

<div>
    <p class="dropcap2">3</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=7&amp;Itemid=113"><span class="heading1 nomargintop nomarginbottom">Launcher Assist</span></a>
    <span>Learn the intricacies of the template faster with the RocketLauncher.</span>
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
| Module Class Suffix | `box1`   |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/initial_1.jpeg
[demo3]: assets/initial_2.jpeg
[demo4]: assets/initial_3.jpeg