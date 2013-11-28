---
title: Lumiere: Recreating the Demo - FP Showcase - RokSprocket Features
description: Your Guide to Recreating Elements of the Lumiere Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/lumiere:Lumiere

---

FP Showcase - RokSprocket Features
-----
![][demo]

:   1. **RokSprocket** [30%, 10%, se]

The RokSprocket Showcase module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest. This particular implementation includes HTML5 embedded video that can bring your site to life.

You can see more information about this feature in our [HTML5 video guide][special].

### Filtered Article List
![][demo6]

Below is the HTML code for the sample content, to be placed in the **description** field in each line item on RokSprocket. There are three separate blocks of code below to represent the three different articles presented in our demo. This step does not activate the embedded video feature (this is handled in the Template Manager), but it will enable you to have text display over the video as it does in our demo.

#### Template Features

~~~
<p class='promo1 rt-center nomarginbottom'>Dynamic Backgrounds</p>
<p class='promo3 rt-center'>((HTML5 support for displaying stunning videos and images in the header))</p>
 
<div class='gantry-width-block demo-width-100 smallmarginbottom'>
  <div class='gantry-width-33 gantry-width-block'>
    <div class='gantry-width-spacer'>
      <div class='gantry-width-25 gantry-width-block'>
        <span class='big-icon icon-film'></span>                  
      </div>                
      <div class='gantry-width-75 gantry-width-block'>                            
        <p class='promo3 nomarginbottom'><span class='hidden-tablet'>Video </span> Controls.</p>                            
        <p class='rt-fadeout'>The video background feature includes several controls: Play/Pause and Mute/Unmute.</p>                  
      </div>      
    </div>              
  </div>      
  <div class='gantry-width-33 gantry-width-block'>            
    <div class='gantry-width-spacer'>                  
      <div class='gantry-width-25 gantry-width-block'>                            
        <span class='big-icon icon-list'></span>                    
      </div>                  
      <div class='gantry-width-75 gantry-width-block'>                            
        <p class='promo3 nomarginbottom'>Image<span class='hidden-tablet'> Option</span>s.</p>                          
        <p class='rt-fadeout'>
          <span class='visible-large rt-floatleft nomarginright'>Alternatively, s</span>
          <span class='hidden-large rt-floatleft nomarginright'>S</span>elect an image background or backup, for when a video cannot be displayed.
        </p>                            
      </div>              
    </div>      
  </div>  
  <div class='gantry-width-33 gantry-width-block'>            
    <div class='gantry-width-spacer'>                  
      <div class='gantry-width-25 gantry-width-block'>                            
        <span class='big-icon icon-external-link'></span>                  
      </div>                  
      <div class='gantry-width-75 gantry-width-block'>                            
        <p class='promo3 nomarginbottom'>Downloops.com</p>                          
        <p class='rt-fadeout'>The stunning videos for each preset are generously provided by <a href='http://www.downloops.com/'>www.downloops.com</a></p>                          
      </div>              
    </div>      
  </div>
</div>
<p class='rt-center'>      
  <a href='index.php?option=com_content&amp;view=article&amp;id=10&amp;Itemid=117' class='big-button readon'>Take a Tour Now <span class='icon-play'></span></a>
</p>
~~~

#### Integrated Extensions

~~~
<p class='promo1 rt-center nomarginbottom'>RokSprocket<span class='hidden-tablet'> Styling</span></p>
<p class='promo3 rt-center'>((RokSprocket is a powerful content display extension<span class='hidden-tablet'>, that is quick and easy to use</span>))</p>
 
<div class='gantry-width-block demo-width-100 smallmarginbottom'>  
  <div class='gantry-width-33 gantry-width-block'>        
    <div class='gantry-width-spacer'>          
      <div class='gantry-width-25 gantry-width-block'>                
        <span class='big-icon icon-edit'></span>            
      </div>            
      <div class='gantry-width-75 gantry-width-block'>                
        <p class='promo3 nomarginbottom'>Intuitive<span class='hidden-tablet'> UI</span>.</p>              
        <p class='rt-fadeout'>An advanced interface, used for all layout types, to easily configure RokSprocket.</p>            
      </div>    
    </div>          
  </div>    
  <div class='gantry-width-33 gantry-width-block'>        
    <div class='gantry-width-spacer'>          
      <div class='gantry-width-25 gantry-width-block'>                
        <span class='big-icon icon-list-ul'></span>          
      </div>            
      <div class='gantry-width-75 gantry-width-block'>                
        <p class='promo3 nomarginbottom'>Headlines<span class='hidden-tablet'> Layout</span>.</p>              
        <p class='rt-fadeout'>A snippet layout type, ideal for previewing content items, such as for newsflash articles.</p>                
      </div>          
    </div>    
  </div>  
  <div class='gantry-width-33 gantry-width-block'>        
      <div class='gantry-width-spacer'>          
        <div class='gantry-width-25 gantry-width-block'>                
          <span class='big-icon icon-th'></span>            
        </div>            
        <div class='gantry-width-75 gantry-width-block'>                
            <p class='promo3 nomarginbottom'>Mosaic<span class='hidden-tablet'> Layout</span>.</p>        
            <p class='rt-fadeout'>A grid type layout mode to easily display multiple content blocks, in a magazine format.</p>              
        </div>          
      </div>    
  </div>
</div>
<p class='rt-center'>  
  <a href='index.php?option=com_content&amp;view=article&amp;id=6&amp;Itemid=113' class='big-button readon'>Take a Tour Now <span class='icon-play'></span></a>
</p>
~~~

#### Preset Styles

~~~
<p class='promo1 rt-center nomarginbottom'><span class='hidden-tablet'>Advanced </span>Menus</p>
<p class='promo3 rt-center'>((Choose between two available menu options<span class='hidden-tablet'>, Dropdown Menu or SplitMenu, or none</span>))</p>
 
<div class='gantry-width-block demo-width-100 smallmarginbottom'>    
  <div class='gantry-width-33 gantry-width-block'>        
    <div class='gantry-width-spacer'>          
      <div class='gantry-width-25 gantry-width-block'>                
        <span class='big-icon icon-edit'></span>            
      </div>            
      <div class='gantry-width-75 gantry-width-block'>                
        <p class='promo3 nomarginbottom'>Dropdown<span class='hidden-tablet'> Menu</span>.</p>                
        <p class='rt-fadeout'>A CSS based dropdown menu, with support for multiple columns with custom widths.</p>            
      </div>    
    </div>          
  </div>    
  <div class='gantry-width-33 gantry-width-block'>        
    <div class='gantry-width-spacer'>          
      <div class='gantry-width-25 gantry-width-block'>                
        <span class='big-icon icon-list-ul'></span>          
      </div>            
      <div class='gantry-width-75 gantry-width-block'>                
        <p class='promo3 nomarginbottom'><span class='hidden-tablet'>More </span>Features.</p>                
        <p class='rt-fadeout'>The Dropdown Menu also has support for inline text, icons, modules and positions.</p>              
      </div>          
    </div>    
  </div>  
  <div class='gantry-width-33 gantry-width-block'>        
    <div class='gantry-width-spacer'>          
      <div class='gantry-width-25 gantry-width-block'>                
        <span class='big-icon icon-th'></span>            
      </div>            
      <div class='gantry-width-75 gantry-width-block'>                
        <p class='promo3 nomarginbottom'>SplitMenu.</p>      
        <p class='rt-fadeout'>A versatile, static horizontal menu system that displays its children in the sidebar.</p>    
      </div>          
    </div>    
  </div>
</div>
<p class='rt-center'>  
  <a href='index.php?option=com_content&amp;view=article&amp;id=5&amp;Itemid=112' class='big-button readon'>Take a Tour Now <span class='icon-play'></span></a>
</p>
~~~

### Details
![][demo2]

| Option           | Setting                            |  
| :--------------- | :--------------------------------- |  
| Title            | FP Showcase - RokSprocket Features |  
| Show Title       | Hide                               |  
| Access           | Public                             |  
| Position         | showcase-a                         |  
| Status           | Published                          |  
| Content Provider | Joomla                             |  
| Type             | Features                           |  

### Layout Options
![][demo3]

| Option | Setting |
|:------|:-------|
| Display Limit     | ∞         |
| Theme             | Showcase  |
| Article Titles    | Show      |
| Article Text      | Show      |
| Preview Length    | ∞         |
| Strip HTML Tags   | No        |
| Arrow Navigation  | Show      |
| Pagination        | Hide      |
| Animation         | Crossfade |
| Autoplay          | Disable   |
| Autoplay Delay    | 5         |
| Image Resize      | Disable   |

### Article Defaults
![][demo4]

### Advanced
![][demo5]

| Option              | Setting                                            |
|:--------------------|:---------------------------------------------------|
| Module Class Suffix | `basic fp-demo-showcase`                           |

[demo]: assets/lumiere2.jpeg
[demo2]: assets/features_1.jpeg
[demo3]: assets/features_2.jpeg
[demo4]: assets/features_3.jpeg
[demo5]: assets/features_4.jpeg
[demo6]: assets/features_5.jpeg
[special]: special_features.md