---
title: Stratos: Recreating the Demo - Member Access
description: Your Guide to Recreating Elements of the Stratos Theme for Joomla
breadcrumb: /joomla:Joomla/templates:Templates/stratos:Stratos

---

Member Access
-----
![][ma1]
The Member Access module makes it easy for your site's users to log in and take advantage of any extra benefits your site offers them. Setup for this module is actually pretty basic.

>> The **Member Access** module requires **RokBox2** to be installed and published in order for the popup to function. In addition, the Login Panel feature needs to be active in the template settings. This creates the Member Access button which loads the module.

Here are the details:

![][ma2]

### Details
| Option     | Setting       |  
| :--------- | :------------ |  
| Title      | Member Access |  
| Show Title | Show          |  
| Position   | login         |  
| Status     | Published     |  
| Access     | Public        |  
| Ordering   | Member Access |  

### Basic Options
| Option                  | Setting |  
| :---------------------- | :------ |  
| Pre-Text                | Blank   |  
| Post-Text               | Blank   |  
| Login Redirection Page  | Default |  
| Logout Redirection Page | Default |  
| Show Greeting           | Yes     |  
| Show Name/Username      | Name    |  
| Encrypt Login form      | No      |  

### Advanced Options
| Option              | Setting |  
| :------------------ | :------ |  
| Module Class Suffix | Blank   |  

### Template Settings
You will need to make the actual member login button appear next to the main menu at the top of the page so your visitors have the ability to activate that module.

To do this, you will need to go through the template settings and activate the **Login Panel** option in the **header-c** position. More details about this process can be found in our [template settings documentation][login].

[login]: demo_override.md#features
[ma1]: assets/member_access_1.jpg
[ma2]: assets/member_access_2.jpg