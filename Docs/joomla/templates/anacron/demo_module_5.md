---
title: Anacron: Recreating the Demo - Pay as You Grow Pricing
description: Your Guide to Recreating Elements of the Anacron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Anacron:Anacron

---

Pay as You Grow Pricing
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option     | Setting                   |  
| :--------- | :------------------------ |  
| Title      | `Pay as You Grow Pricing` |  
| Show Title | Show                      |  
| Position   | expandedtop-a             |  
| Status     | Published                 |  
| Access     | Public                    |  

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p>All plans come with awesome support by email and phone. There is no hidden fee!</p>

<div class="fp-pricing-table">
    <div class="gantry-width-33 gantry-width-block">
        <div class="gantry-width-spacer">
            <ul class="rt-pricing-table">
                <li class="rt-table-title">Basic</li>
                <li class="rt-table-price">$28</li>
                <li class="rt-table-description">Globally incubate standards compliant channels</li>
                <li class="rt-table-item">5GB Storage</li>
                <li class="rt-table-item">10 Users</li>
                <li class="rt-table-cta-button"><a class="readon2" href="#">Sign Up</a></li>
            </ul>
        </div>
    </div>

    <div class="gantry-width-33 gantry-width-block">
        <div class="gantry-width-spacer">
            <ul class="rt-pricing-table">
                <li class="rt-table-title">Standard</li>
                <li class="rt-table-price">$58</li>
                <li class="rt-table-description">Globally incubate standards compliant channels</li>
                <li class="rt-table-item">25GB Storage</li>
                <li class="rt-table-item">20 Users</li>
                <li class="rt-table-cta-button"><a class="readon2" href="#">Sign Up</a></li>
            </ul>
        </div>
    </div>

    <div class="gantry-width-33 gantry-width-block">
        <div class="gantry-width-spacer">
            <ul class="rt-pricing-table">
                <li class="rt-table-title">Ultimate</li>
                <li class="rt-table-price">$88</li>
                <li class="rt-table-description">Globally incubate standards compliant channels</li>
                <li class="rt-table-item">50GB Storage</li>
                <li class="rt-table-item">30 Users</li>
                <li class="rt-table-cta-button"><a class="readon2" href="#">Sign Up</a></li>
            </ul>   
        </div>
    </div>

    <div class="clear"></div>   
</div>

<p>Free <strong>30 days trial</strong> on all plans. No credit card needed! Need a bigger plan? <a href="#">View Professional Plan</a>.</p> 
~~~

### Basic

![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | No      |  
| Select a Background Image | Blank   |

### Advanced

![][demo4]

| Option              | Setting                                 |  
| :------------------ | :-------------------------------------- |  
| Module Class Suffix | `fp-expandedtop rt-center rt-big-title` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/grow_1.jpeg
[demo3]: assets/grow_2.jpeg
[demo4]: assets/grow_3.jpeg