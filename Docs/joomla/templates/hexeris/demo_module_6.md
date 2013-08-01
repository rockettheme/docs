---
title: Hexeris: Recreating the Demo - Demo Replica
description: Your Guide to Recreating Elements of the Hexeris Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hexeris:Hexeris

---

Demo Replica
-----
![][demo]
This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

### Details
![][demo2]

| Option            | Setting            |  
| :---------------- | :----------------- |  
| Title             | Demo Replica       |  
| Show Title        | Show               |  
| Position          | feature-b          |  
| Status            | Published          |  
| Access            | Public             |  
| Ordering          | 1. Demo Replica    |  
| Start Publishing  | 0000-00-00 00:00:0 |  
| Finish Publishing | 0000-00-00 00:00:0 |  
| Language          | All                |  
| Note              | Blank              |

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<div>
    <p>You can deploy a <a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=109">replica</a> of this month's demo with ease, using the readily available <strong>RocketLauncher</strong> package.</p>
    <a href="index.php?option=com_content&amp;view=article&amp;id=8&amp;Itemid=109" class="readon"><span>More Info</span></a>
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

| Option              | Setting                   |  
| :------------------ | :------------------------ |  
| Module Class Suffix | `box1 rt-bevel icon-copy` |

[demo]: assets/demo_5.jpeg
[demo2]: assets/replica_1.jpeg
[demo3]: assets/replica_2.jpeg
[demo4]: assets/replica_3.jpeg