---
title: Ionosphere: Recreating the Demo - Frontpage Article
description: Your Guide to Recreating Elements of the Ionosphere Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/ionosphere:Ionosphere

---

Frontpage Article
----
![][demo]
This area of the front page is a a featured article. You can replicate this by creating a new article by going to **Administrator -> Content -> Article Manager -> Add New Article**. Making it appear on the front page is easy enough. Just assign the article to the home page and make sure you have **MainBody** turned on in your Template Settings page. You will find the settings used in our demo below.

In order for the social buttons to appear as they do in the demo, you will first need to install and activate [**RokSocialButtons**][roksocial], which is available for free on our site.

![][social]

Once the extension is published using the settings listed in the above image, you can add them to your article using the `{socialbuttons}` line shows in the article text field below.

### Edit Article
![][demo2]

| Option   | Setting        |  
| :------- | :------------- |  
| Title    | `Top Features` |  
| Featured | Yes            |  
| Status   | Published      |  
| Access   | Public         |  
| Language | All            |  

### Article Text
Enter the following in the **Article Text** editor.

~~~
<div class="module-content">
<div class="fp-main-img"><img src="images/stories/demo/frontpage/fp-main-1.jpg" alt="image" width="284" height="253"/></div>
 
{socialbuttons}
 
<div class="promo largepaddingtop"><h3 class="feature nobold largemarginbottom">Featured Extensions</h3></div>
<p class="medmarginbottom">An assortment of stylistically integrated extensions are available with Ionosphere:</p>
<ul class="circle nomarginright nomarginbottom">
    <li><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=7">RokSprocket: Content Module</a><br />Combine tabbed, showcase and other functionality within one module.</li>
    <li class="nomarginbottom"><a href="index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=7">RokAjaxSearch: Search Module</a><br />A sophisticated search module with integrated Google features such as Image Search.</li>
</ul>
 
<div class="clear"></div>
<div class="fp-main-module box6">
    <div class="rt-block nomargintop">
        <div class="module-surround">
            <div class="rt-demo-grid-4">
                <ul class="dots nomarginbottom">
                    <li>Triple Level SplitMenu &amp; Fusion Menu.</li>
                    <li>11 Styled and 26 Layout Module Suffixes.</li>   
                    <li>84 Positions including 15 Gantry Rows.</li>
                </ul>
                <div class="clear"></div>
            </div>
            <div class="rt-demo-grid-4">
                <ul class="dots nomarginbottom">
                    <li>Twelve Customizable Style Variations.</li>
                    <li>Built with the Powerful Gantry Framework.</li>
                    <li>Comprehensive Content Typography.</li>
                </ul>
                <div class="clear"></div>
            </div>
            <div class="clear"></div>
        </div>
    </div>
</div>
</div>
~~~

[demo]: assets/demo_article.jpg
[demo2]: assets/article_1.jpg
[roksocial]: http://www.rockettheme.com/extensions-downloads/free/3298-roksocialbuttons
[social]: assets/roksocial.jpg