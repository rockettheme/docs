---
title: Diametric: Recreating the Demo - Featured Article
description: Your Guide to Recreating Elements of the Diametric Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/diametric:Diametric

---

Featured Article
-----
![][demo]

The area of the front page dedicated to featured articles has a bit of unique styling in place to allow for additional functionality, such as the social buttons found in this example. 

In order for the social buttons to appear as they do in the demo, you will first need to install and activate [**RokSocialButtons**][roksocial], which is available for free on our site.

![][social]

Once the extension is published using the settings listed in the above image, you can add them to your article using the `{socialbuttons}` line shows in the article text field below. You can find step-by-step instructions on installing and activating an extension in [our guide][ext].

Next, you will need to create a featured article. You can do this by going to **Administrator -> Content -> Article Manager -> Add New Article**. Making it appear on the front page is easy enough. Just assign the article to the home page and make sure you have **MainBody** turned on in your Template Settings page. You will find the settings used in our demo to create the **Core Gantry Framework** article below.

### Edit Article
![][demo2]

| Option   | Setting                |  
| :------- | :--------------------- |  
| Title    | `Core Gantry Framework`|  
| Featured | Yes                    |  
| Status   | Published              |  
| Access   | Public                 |  
| Language | All                    |  

### Article Text
Enter the following in the **Article Text** editor.

~~~
<p><strong>Gantry</strong> is a powerful base framework, providing a standard platform to ensure powerful, <strong>versatile</strong> and popular features are common across all templates. Supported features include an <strong>intuitive</strong> control panel.</p>

<a class="readon rt-floatleft nomarginright" href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=106"><span>Read More</span></a>

{socialbuttons}
~~~

[demo]: assets/demo_11.jpeg
[demo2]: assets/article_1.jpg
[roksocial]: http://www.rockettheme.com/extensions-downloads/free/3298-roksocialbuttons
[ext]: ../../platform/extensions.md
[social]: assets/roksocial.jpg