---
title: Grunge: Recreating the Demo - Frontpage Showcase A
description: Your Guide to Recreating Elements of the Grunge Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/grunge:Grunge

---

Frontpage Showcase A
-----

![][demo]

This area of the front page is a **RokStories** widget. You will find the settings used in our demo below.

>> RokStories is a legacy plugin by RocketTheme for WordPress. You can replicate this look using RokSprocket or a Text widget. We've included the instructions for Text below.

## Text Method

### Widget Info

| Option     | Setting                  |
| :--------- | :----------------------- |
| Title      | Blank                    |
| Show Title | Hide                     |
| Position   | Showcase                 |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rokstories-layout2">
<div class="feature-block"><img class="floatleft rt-sample-rokstories" src="http://example.com/images/stories/demo/frontpage/showcase1.jpg" border="0" alt="image" /> <span class="feature-title">Grunge Free/GPL Theme Release</span>
<p class="feature-desc"><strong>Grunge</strong>, the June 2010 Free GPL release, is the second free theme to take advantage of the Gantry Framework, and is outfitted with a sophisticated, artistic and professional design, on top of the highly functional core.</p>
<div class="readon"><a href="#"><span>Read the Full Story</span></a></div>
</div>
</div>
~~~

[demo]: assets/demo_1.jpeg