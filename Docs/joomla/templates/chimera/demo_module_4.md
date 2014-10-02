---
title: Chimera: Recreating the Demo - FP Utility B
description: Your Guide to Recreating Elements of the Chimera Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/chimera:Chimera

---

FP Utility B
----

![][demo]

This area of the front page is a **mod_custom** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting        |
| :---------- | :------------- |
| Title       | `FP Utility B` |
| Show Title  | Hide           |
| Position    | utility-b      |
| Status      | Published      |
| Access      | Public         |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="rt-device-animation" data-animation-step="1">
  <div class="device">
    <div class="phone-home-button"></div>
    <div class="tablet-home-button"></div>
    <div class="screen-stand"><div class="leg"></div><div class="foot"></div></div>
    <div class="display">
      <div class="slide1"><div>Chimera's design is great on <strong>desktops</strong>...</div></div>
      <div class="slide2"><div>...brilliant on <strong>tablets</strong>...</div></div>
      <div class="slide3"><div>and perfect for <strong>mobile!</strong></div></div>
    </div>
  </div>
</div>

<script>

  var duration = 20000, steps = 3, step = 1;

  setInterval( function() {
    document.querySelector( '.rt-device-animation' ).setAttribute( 'data-animation-step', step = ++step > steps ? 1 : step );
  }, duration / steps );

</script>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `fp-utility-b` |

[demo]: assets/demo_4.jpeg
[demo2]: assets/demo_4a.jpeg
[demo3]: assets/demo_4b.jpeg
[demo4]: assets/demo_4c.jpeg
