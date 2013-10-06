---
title: Alerion: Recreating the Demo: Special Features
description: Your Guide to Recreating Elements of the Alerion Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Alerion:Alerion

---

Headline, Subheading, and Headline Icon
-----

![][headline3]

Setting the text you wish to appear as the headline and subheading for each section in a module is a fairly simple process. You only need to do the following steps.

1. Navigate to **Admin -> Alerion Theme**.
2. Go to the **Style** tab and set the text for Showcase, Feature, Utility, and so on (pictured above).
4. You can also set an icon style for the headline using FontAwewsome icon format, such as: `icon-list-alt` (pictured below). This icon will also appear on the QuickNav.

![][headline2]

QuickNav Menu
-----

![][quicknav1]

QuickNav adds a scrolling menu that follows your viewport as you scroll. Instructions for how to set this up to match the demo are detailed below.

![][quicknav2]

1. Navigate to **Admin -> Alerion Theme**.
2. Go to the **Style** tab and enable **QuickNav**.
3. The icon is taken from the Headline icon parameter on the **Style** tab with the **FontAwesome** icon format, such as: `icon-bullhorn`.

![][quicknav3]

Background Image and Parallax
-----

![][parallax1]

Parallax is apparent motion of a 3D object depending on your perspective. This effect has been transposed into the template, allowing configurable areas to move based on scroll position.

![][parallax2]

>> IMPORTANT NOTE: For demo purpose we load the background for Showcase, Feature, and Footer section in templates/rt_alerion/less/demo-styles.less as the following. If you wish to use your own image and use the image picker, please remove this part from your demo-styles.less (EDIT: demo-parallax-bg.less in later releases of the template).

~~~
// Parallax Background Images (Please remove the following if you wish to use your own images)
.contentstyle-preset1 {
    #rt-top-surround {
        background-image: url(../../../images/rocketlauncher/frontpage/showcase/showcase-bg-p1.jpg);
    }
    #rt-feature {
        background-image: url(../../../images/rocketlauncher/frontpage/feature/feature-bg-p1.png);
    }   
    #rt-footer {
        background-image: url(../../../images/rocketlauncher/frontpage/footer/footer-bg-p1.jpg);
    }   
}
.contentstyle-preset2 {
    #rt-top-surround {
        background-image: url(../../../images/rocketlauncher/frontpage/showcase/showcase-bg-p2.jpg);
    }
    #rt-feature {
        background-image: url(../../../images/rocketlauncher/frontpage/feature/feature-bg-p2.png);
    }      
    #rt-footer {
        background-image: url(../../../images/rocketlauncher/frontpage/footer/footer-bg-p2.jpg);
    }   
}
.contentstyle-preset3 {
    #rt-top-surround {
        background-image: url(../../../images/rocketlauncher/frontpage/showcase/showcase-bg-p3.jpg);
    }
    #rt-feature {
        background-image: url(../../../images/rocketlauncher/frontpage/feature/feature-bg-p3.png);
    }      
    #rt-footer {
        background-image: url(../../../images/rocketlauncher/frontpage/footer/footer-bg-p3.jpg);
    }   
}
.contentstyle-preset4 {
    #rt-top-surround {
        background-image: url(../../../images/rocketlauncher/frontpage/showcase/showcase-bg-p4.jpg);
    }
    #rt-feature {
        background-image: url(../../../images/rocketlauncher/frontpage/feature/feature-bg-p4.png);
    }      
    #rt-footer {
        background-image: url(../../../images/rocketlauncher/frontpage/footer/footer-bg-p4.jpg);
    }   
}
.contentstyle-preset5 {
    #rt-top-surround {
        background-image: url(../../../images/rocketlauncher/frontpage/showcase/showcase-bg-p5.jpg);
    }
    #rt-feature {
        background-image: url(../../../images/rocketlauncher/frontpage/feature/feature-bg-p5.png);
    }      
    #rt-footer {
        background-image: url(../../../images/rocketlauncher/frontpage/footer/footer-bg-p5.jpg);
    }   
}
.contentstyle-preset6 {
    #rt-top-surround {
        background-image: url(../../../images/rocketlauncher/frontpage/showcase/showcase-bg-p6.jpg);
    }
    #rt-feature {
        background-image: url(../../../images/rocketlauncher/frontpage/feature/feature-bg-p6.png);
    }      
    #rt-footer {
        background-image: url(../../../images/rocketlauncher/frontpage/footer/footer-bg-p6.jpg);
    }   
}
// End of Parallax Background Images
~~~

Instructions for setting these features up in Administrator are detailed below.

![][parallax3]

1. Navigate to **Admin -> Alerion Theme**.
2. Go to **Style** tab and you can see all parameter to configure the parallax background.
3. Choose the background image (pictured above) by using the image picker you wish to use for the background of the section.
4. Enable the parallax style effects for the background image. You can also enable or disable a color tinting overlay that matches your accent color and will appear on top of your selected background image. Additionally, you can set the contrast style for light or dark, the overlay gradient style, as well as the overlay pattern style for the background.
5. Select the movement speed of the parallax effect (pictured below). The speed parameter is not really a speed. It's a delta value which is based on many different factors, such as how big the background image and how big the section is. You will need to play with the value until the scroll seems smooth.

![][parallax4]

[headline2]: assets/headline_2.jpeg
[headline3]: assets/headline_3.jpeg
[quicknav1]: assets/quicknav_1.jpeg
[quicknav2]: assets/quicknav_2.jpeg
[quicknav3]: assets/quicknav_3.jpeg
[parallax1]: assets/parallax_1.jpeg
[parallax2]: assets/parallax_2.jpeg
[parallax3]: assets/parallax_3.jpeg
[parallax4]: assets/parallax_4.jpeg