---
title: Syndicate: Recreating the Demo - News Topics
description: Your Guide to Recreating Elements of the Syndicate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/syndicate:Syndicate

---

News Topics
-----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting       |
| :--------- | :------------ |
| Title      | `News Topics` |
| Show Title | Show          |
| Position   | footer-a      |
| Status     | Published     |
| Access     | Public        |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~
<div class="rt-demo-grid-2">
    <ul class="bullet-1 nomarginbottom">
        <li><em class="bold title">News</em>
            <ul class="bullet-none">
                <li>Politics</li>
                <li>World News</li>
            </ul>
        </li>
        <li><em class="bold title">Politics</em></li>
        <li><em class="bold title">Sports</em>
            <ul class="bullet-none">
                <li>Football</li>
                <li>Rubgy</li>
                <li>Cricket</li>
            </ul>
        </li>
        <li><em class="bold title">Health</em>
            <ul class="bullet-none">
                <li>Private</li>
            </ul>
        </li>
    </ul>
</div>
<div class="rt-demo-grid-2">
    <ul class="bullet-1 nomarginbottom">
        <li><em class="bold title">Property</em></li>
        <li><em class="bold title">Finance</em>
            <ul class="bullet-none">
                <li>Personal</li>
                <li>Economics</li>
                <li>Markets</li>
            </ul>
        </li>
        <li><em class="bold title">Fashion</em></li>
        <li><em class="bold title">Tech</em>
            <ul class="bullet-none">
                <li>Phones</li>
                <li>Laptops</li>
                <li>Other</li>
            </ul>
        </li>
    </ul>
</div>
<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting    |
| :------------------ | :--------- |
| Module Class Suffix | `title6`   |

[demo]: assets/demo_9.jpeg
[demo2]: assets/demo_9a.jpeg
[demo3]: assets/demo_9b.jpeg
[demo4]: assets/demo_9c.jpeg
