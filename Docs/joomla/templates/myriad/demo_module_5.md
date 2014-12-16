---
title: Myriad: Recreating the Demo - Photo Gallery
description: Your Guide to Recreating Elements of the Myriad Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

Photo Gallery
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

|   Option   |     Setting     |
| :--------- | :-------------- |
| Title      | `Photo Gallery` |
| Show Title | Show            |
| Position   | feature-b       |
| Status     | Published       |
| Access     | Public          |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50 wow fadeInDown">
            <div class="gantry-width-spacer">
                <div class="rt-image-effect">
                    <img src="images/rocketlauncher/home/fp-feature/img-01.jpg" alt="image" />
                    <div class="rt-image-effect-caption">
                        <p>
                            <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111"><i class="fa fa-fw fa-file-text-o"></i></a>
                            <a href="http://www.rockettheme.com/joomla/templates/myriad"><i class="fa fa-fw fa-file-image-o"></i></a>
                            <a data-rokbox href="images/rocketlauncher/home/fp-feature/img-01.jpg"><i class="fa fa-fw fa-search"></i></a>
                        </p>
                    </div>                      
                </div>  
            </div>
        </div>
        <div class="gantry-width-50 wow fadeInDown">
            <div class="gantry-width-spacer">
                <div class="rt-image-effect">
                    <img src="images/rocketlauncher/home/fp-feature/img-02.jpg" alt="image" />
                    <div class="rt-image-effect-caption">
                        <p>
                            <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111"><i class="fa fa-fw fa-file-text-o"></i></a>
                            <a href="http://www.rockettheme.com/joomla/templates/myriad"><i class="fa fa-fw fa-file-image-o"></i></a>
                            <a data-rokbox href="images/rocketlauncher/home/fp-feature/img-02.jpg"><i class="fa fa-fw fa-search"></i></a>
                        </p>
                    </div>                      
                </div>
            </div>
        </div>      
    </div>
</div>

<div class="clear"></div>

<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50 wow fadeInUp">
            <div class="gantry-width-spacer">
                <div class="rt-image-effect">
                    <img src="images/rocketlauncher/home/fp-feature/img-03.jpg" alt="image" />
                    <div class="rt-image-effect-caption">
                        <p>
                            <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111"><i class="fa fa-fw fa-file-text-o"></i></a>
                            <a href="http://www.rockettheme.com/joomla/templates/myriad"><i class="fa fa-fw fa-file-image-o"></i></a>
                            <a data-rokbox href="images/rocketlauncher/home/fp-feature/img-03.jpg"><i class="fa fa-fw fa-search"></i></a>
                        </p>
                    </div>                      
                </div>
            </div>
        </div>
        <div class="gantry-width-50 wow fadeInUp">
            <div class="gantry-width-spacer">
                <div class="rt-image-effect">
                    <img src="images/rocketlauncher/home/fp-feature/img-04.jpg" alt="image" />
                    <div class="rt-image-effect-caption">
                        <p>
                            <a href="index.php?option=com_content&amp;view=article&amp;id=1&amp;Itemid=111"><i class="fa fa-fw fa-file-text-o"></i></a>
                            <a href="http://www.rockettheme.com/joomla/templates/myriad"><i class="fa fa-fw fa-file-image-o"></i></a>
                            <a data-rokbox href="images/rocketlauncher/home/fp-feature/img-04.jpg"><i class="fa fa-fw fa-search"></i></a>
                        </p>
                    </div>                      
                </div>
            </div>
        </div>      
    </div>
</div>

<div class="clear"></div>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

|        Option       |                   Setting                   |
| :------------------ | :------------------------------------------ |
| Module Class Suffix | `fp-feature-b title5 rt-modtitle-uppercase` |

[demo]: assets/demo_5.jpeg
[demo2]: assets/demo_5a.jpeg
[demo3]: assets/demo_5b.jpeg
[demo4]: assets/demo_5c.jpeg