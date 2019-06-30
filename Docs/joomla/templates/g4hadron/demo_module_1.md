---
title: Hadron: Recreating the Demo - FP RokAjaxSearch
description: Your Guide to Recreating Elements of the Hadron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hadron:Hadron

---

FP RokAjaxSearch
-----

![][demo]

The Site Search area of the front page is a **mod_rokajaxsearch** module that allows visitors to search your site using the powerful RokAjaxSearch tool. By moving your mouse over the magnifying glass, a full search field will appear.

>> This particular look is only possible because the `search` suffix was put in the **Feature Suffix** field in the Social Buttons feature. You can access this setting by navigating to **Admin > Templates Manager > Hadron > Features > Social Buttons**. The **Social Buttons** position is also set to **navigation-b**.

![][socialbuttons]

### Details

![][demo2]

| Option     | Setting            |  
| :--------- | :----------------- |  
| Title      | `FP RokAjaxSearch` |  
| Show Title | Hide               |  
| Position   | navigation-c       |  
| Status     | Published          |  
| Access     | Public             |  
| Language   | All                |  
| Note       | Blank              |  

### Layout Options

![][demo3]

| Option                            | Setting                                                  |
|:----------------------------------|:---------------------------------------------------------|
| Search Page URL                   | `index.php?option=com_search&view=search&tmpl=component` |
| Advanced Search Page URL          | `index.php?option=com_search&view=search`                |
| Include RokAjaxSearch default CSS | No                                                       |
| Theme Style                       | Blue                                                     |
| Searchphrase                      | Any words                                                |
| Ordering                          | Newest First                                             |
| Limit                             | 10                                                       |
| Results Per Page                  | 3                                                        |
| Google Web Search                 | No                                                       |
| Google Blog Search                | No                                                       |
| Google Images Search              | No                                                       |
| Google Videos Search              | No                                                       |
| Show Pagination                   | Yes                                                      |
| Google SafeSearch                 | Moderate                                                 |
| Image Size to Search              | Medium                                                   |
| Show Estimated                    | Yes                                                      |
| Hide div id(s)                    | Blank                                                    |
| Link to All Results               | Yes                                                      |
| Show Description                  | Yes                                                      |
| Include (Category/Section)        | Yes                                                      |
| Show Read More Link               | Yes                                                      |

### Advanced

![][demo4]

| Option              | Setting                         |  
| :------------------ | :------------------------------ |  
| Module Class Suffix | `fp-rokajaxsearch hidden-phone` |  

[demo]: assets/demo_1d.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[socialbuttons]: assets/socialbuttons.jpg
[demo4]: assets/demo_1c.jpeg