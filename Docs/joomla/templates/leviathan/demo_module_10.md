---
title: Leviathan: Recreating the Demo - Frontpage Sidebar Menu
description: Your Guide to Recreating Elements of the Leviathan Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/leviathan:Leviathan

---

Frontpage Sidebar Menu
----
![][demo]

The **Frontpage Sidebar Menu** module is a standard **Menu** module. Here is a breakdown of the options selected to make it appear as it does on the front page of our demo.

### Icons
The sidebar RokNavMenu menu icons are [referenced here][font].

To replace the icons, please open and edit `demo-styles.less` inside the `templates/rt_leviathan/less/` folder.

~~~
// Demo FP Menu
.fp-menu ul.menu > li {
    a {
        padding: 14px 40px;
        &:after {
            font-family: FontAwesome;
            font-size: 1.2em;
            font-weight: normal;
            position: absolute;
            left: 17px;
        }
    }
    ul {
        li {
            padding-left: 15px;
        }
        li a {
            padding: 8px 20px;
        }
        li:nth-child(n) a:after {
            content: "";
        }
    }
    // Icons Reference: https://github.com/FortAwesome/Font-Awesome/blob/master/less/font-awesome.less
    &:nth-child(1) a:after {
        content: "\f015";
    }
    &:nth-child(2) a:after {
        content: "\f004";
    }
    &:nth-child(3) a:after {
        content: "\f05a";
    }
    &:nth-child(4) a:after {
        content: "\f0c9";
    }
    &:nth-child(5) a:after {
        content: "\f06b";
    }
    &:nth-child(6) a:after {
        content: "\f06a";
    }
    &:nth-child(7) a:after {
        content: "\f024";
    }
    &:nth-child(8) a:after {
        content: "\f019";
    }                          
}
~~~

### Details
![][demo2]

| Option            | Setting         |  
| :---------------- | :-------------- |  
| Title             | Quick Menu      |  
| Show Title        | Hide            |  
| Position          | sidebar-a       |  
| Status            | Published       |  
| Access            | Public          |   
| Language          | All             |  
| Note              | Blank           |  

### Basic Options
![][demo3]

| Option              | Setting          |  
| :------------------ | :--------------- |  
| Start Level         | 1                |  
| End Level           | All              |  
| Show Sub-menu Items | Yes              |  

### Advanced Options
![][demo4]

| Option              | Setting                                                                        |  
| :------------------ | :----------------------------------------------------------------------------- |  
| Module Class Suffix | `fp-menu title1 rt-small-sidebar-title nomargintop nopaddingtop` |  

[demo]: assets/demo_10.jpeg
[demo2]: assets/quick_1.jpeg
[demo3]: assets/quick_2.jpeg
[demo4]: assets/quick_3.jpeg
[font]: https://github.com/FortAwesome/Font-Awesome/blob/master/less/font-awesome.less
