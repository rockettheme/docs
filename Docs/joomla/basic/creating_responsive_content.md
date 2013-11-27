---
title: Creating Responsive Content
description: Your guide to creating responsive content for your Joomla site.
breadcrumb: /joomla:Joomla/!basic:Basic Tutorials/!creating_responsive_content.md:Creating Responsive Content

---

Introduction
-----
Building a responsive template is a long and detailed process that involves coordinating all of your site's elements in a way that makes for a perfect storm allowing smooth and seemingly seamless transitions between the largest desktop browser windows to the smallest mobile devices.

There are several design choices we take into consideration when building our demos in order to demonstrate exactly what our templates are capable of, and set our users up for the best possible experience with them.

Before we get into some of the tricks we use to make our demo content look the way it does, you might want to check out these blog posts outlining our take on responsive design.

* [Responsive Design: Part 1 - RocketTheme's Plan][part1]
* [Responsive Design: Part 2 - RocketTheme's Solution][part2]
* [Responsive Design: Part 3 - RocketTheme's Extensions][part3]

Our responsive templates are only part of a properly-executed responsive site. Your content should be set up for success with various browser widths. Any content with fixed sizes could have a detrimental impact on how your page loads on various screens. Everything from your text to your images should be able to scale up or down at will.

>> NOTE: The explanation and the screenshots used in this tutorial are based on the Kirigami template. These methods can be applied to any other responsive RocketTheme template.

### Responsive Images
There are two points we need to cover in order to create responsive images.

#### Do Not Fix the Width and/or Height of Your Images
First, you must not have fixed width and height attributes specified for any images placed on your site. A max width or height is fine, but locking any image in to a particular size will likely break your site's responsive features.

Here's an example of an image set in a way that will break the responsive layout:

~~~
<img src="path/to/your/image.jpg" width="600" height="200" alt="image" />
~~~

Doing this locks the image at 600px by 200px, regardless of the size of the screen used to view it. To combat this issue, we provide a custom class called `.rt-image` which you can wrap your image in.

~~~
<div class="rt-image">
    <img src="path/to/your/image.jpg" alt="image" />
</div>
~~~

Doing this will ensure that the image is responsive and will scale proportionally with the rest of your content.

#### Image Width and Container Width
The image's width should be matched for the container at the largest width. Let's see how we get the best width for the images in "RokSprocket Features" module.

Before cropping and resizing the actual image, we can use a placeholder image to create the large image. [Placehold.it][placehold] is one service which offers a quick and simple image placeholder. In the sample below, the image has a width/height of 1000px by 500px.

![][responsive1]

Below, we'll take a look at how a 1000px x 500px image appears in the browser.

![][responsive2]

Now, you can resize the browser for two screen size breakdowns. You can also use the Chrome Developer Toolbar to check the image width. In this example, a Large Display (>= 1200px width) displays the image at 659px.

![][responsive3]

Scaling down your browser's width to 767px or below initiates the smartphone stage of the site's responsiveness. The image width in this case becomes 478px.

![][responsive4]

From the result above, we will take the largest width, 659px. So, we can now resize and crop the actual image to the 659px width. For the height, you may adjust it to fit the article description. In our demo, the height of the image is 350px. This doesn't mean all of your images should be cropped or resized to a width of 659px, though doing so will certainly improve the optimization of your site as it'll only require users to download the image file at a size it will actually be presented at.

### Custom Responsive Grids
We have some responsive grid classes that you can use to create custom width for your content.

~~~
/* Demo Responsive Grid */
.gantry-width-block {display: block; float: left;}
.gantry-width-spacer {margin: 15px;}
.gantry-width-20 {width: 20%;}
.gantry-width-25 {width: 25%;}
.gantry-width-30 {width: 30%;}
.gantry-width-33 {width: 33.33%;}
.gantry-width-40 {width: 40%;}
.gantry-width-50 {width: 50%;}
.gantry-width-60 {width: 60%;}
.gantry-width-66 {width: 66.66%;}
.gantry-width-70 {width: 70%;}
.gantry-width-75 {width: 75%;}
.gantry-width-80 {width: 80%;}
~~~

The sample implementation can be seen on the demo frontpage.

![][responsive5]

You may add your own custom class. With these custom classes, you can create multiple-column content. Just make sure the total width in a row is 100%.

In small tablets, larger and standard smartphones view, those blocks will be stacked by the following.

~~~
.gantry-width-20, .gantry-width-25, .gantry-width-30, .gantry-width-33, .gantry-width-40, .gantry-width-50, .gantry-width-60, .gantry-width-66, .gantry-width-70, .gantry-width-75, .gantry-width-80 {width: 100%;}
~~~

![][responsive6]

### Responsive Utility Classes
We have a [quick guide set up to assist][class] in the understanding of responsive support classes which you can use to make content on your site appear or disappear depending on the size of the browser window being used to display it. This allows you to trim around the edges where a little too much (or too little) content can make your site appear either too cluttered or bare.

These classes aren't just for whole modules. They can be used to cut out content as it appears in a single block of text, or even some images. By adding `<span class="hidden-phone"></span>` to an area of text you wish to have hidden on smartphones and other small-screen devices but present elsewhere, you can trim this content out without losing the whole module. Otherwise, the content might be a bit crushed in the smaller screen and appear stretched (pictured below).

![][responsive8]

Below is an example paragraph you might find in an article.

~~~
<p>The main focus of the <strong>Kirigami</strong> release, is its Responsive Layout. <span class="hidden-tablet"><strong>Responsive</strong> effectively means a design that will adapt automatically to match whatever device or window size is loading it.</span></p>
~~~

The result: A leaner, more aesthetically pleasing article tease without sacrificing the content on larger-screen devices.

![][responsive9] 


[part1]: http://www.rockettheme.com/blog/team/1550-responsive-design-and-gantry4
[part2]: http://www.rockettheme.com/blog/team/1551-responsive-design-rocketthemes-solution
[part3]: http://www.rockettheme.com/blog/team/1555-responsive-design-rocketthemes-extensions
[placehold]: http://placehold.it/
[class]: responsive_support_classes.md
[responsive1]: assets/responsive_1.jpg
[responsive2]: assets/responsive_2.jpg
[responsive3]: assets/responsive_3.jpg
[responsive4]: assets/responsive_4.jpg
[responsive5]: assets/responsive_5.jpg
[responsive6]: assets/responsive_6.jpg
[responsive7]: assets/responsive_7.jpg
[responsive8]: assets/responsive_8.jpg
[responsive9]: assets/responsive_9.jpg
