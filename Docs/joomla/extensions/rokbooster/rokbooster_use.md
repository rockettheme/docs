---
title: RokBooster: Setup Guide
description: Your Guide to Setting Up and Using RokBooster for Joomla
breadcrumb: /joomla:Joomla/extensions:Extensions/rokbooster:RokBooster

---

Plugin Configuration
-----

RokBooster gives you the ability to optimize your entire site in order to reduce the load on your server, deliver a faster experience to your users, and potentially improve pagerank through reducing site load times.

You can access the RokBooster plugin settings by navigating to **Extensions → Plug-in Manager → System - RokBooster**. 

### Details
![][rokbooster_setup_8]

:   1. **Status** Enables or disables RokBooster. [37%, 37%, sw]
    2. **Access** Sets the access level, determining which user groups have access to the RokBooster editor. [45%, 43%, sw]
    3. **Ordering** Sets Joomla ordering for RokBooster. If you are experiencing interference with RokBooster and other plugins, you can move it higher in the list to attempt to rectify it. [54%, 23%, se]

1. **Status** enables or disables RokBooster.

2. **Access** sets the access level, determining which user groups have access to view RokBooster on the backend.

3. **Ordering** sets Joomla ordering for RokBooster. If you are experiencing interference with RokBooster and other plugins, you can move it higher in the list to attempt to rectify it.

### Basic Cache Settings
![][rokbooster_setup_1]

:   1. **Cache Time** Delineates the amount of time the cache will remain unchanged before it is flushed for a new file.  [58%, 49%, sw]
    2. **Clear Cache** Manually clears the cached files. If the RokBooster is enabled, these files will regenerate as needed. [70%, 39%, sw]

1. **Cache Time** delineates the amount of time the cache will remain unchanged before it is flushed for a new file.

2. The **Clear Cache** button will manually clear the cached files. If the RokBooster is enabled, these files will regenerate as needed.

### Style Sheet Settings
![][rokbooster_setup_2]

:   1. **Compress CSS Files** Combines and compresses CSS files. [45%, 28%, sw]
    2. **Sort Method** Determines the type of sorting method used by RokBooster. [55%, 42%, sw]
    3. **Compress Inline CSS Blocks** Combines and compresses inline CSS blocks. [64%, 24%, se]
    4. **Compile Imported CSS Files** References files in CSS via **@import** rules and add them to the compression. This will slow down the compilation and processing, but not the scanning. [73%, 29%, sw]

1. **Compress CSS Files** combines and compresses CSS files.

2. **Sort Method** to set the type/method for CSS files sorting, **Keep Absolute Ordering** or **Place External Links at Top**.

3. **Compress Inline CSS Blocks** combines all inline CSS blocks together.

4. **Compile Imported CSS Files** gets the files referenced in CSS via **@import** rules and add them to the compression. This will slow down the compilation and processing, but not the scanning.

### JavaScript Settings
![][rokbooster_setup_3]

:   1. **Compress Scripts** Combines and compresses JavaScript files. [51%, 28%, sw]
    2. **Sort Method** Sets the type/method for JavaScript files sorting: **Keep Absolute Ordering** or **Place External Links at Top**. [62%, 41%, sw]
    3. **Compress Inline Scripts** Combines all inline JavaScript blocks together. [72%, 28%, sw]

1. **Compress Scripts** combines and compresses JavaScript files.

2. **Sort Method** sets the type/method for JavaScript files sorting: **Keep Absolute Ordering** or **Place External Links at Top**.

3. **Compress Inline Scripts** combines all inline JavaScript blocks together.

### Image Settings
![][rokbooster_setup_4]

:   1. **Max Image Size for Data URIs** The maximum image size to be able to be used for Data URIs. Converting an image to a base64 Data URI add about a 33% overhead. Internet Explorer 8 is limited to 32KB for a Data URI. So a good size to use to support IE would be 21612 bytes.  [51%, 50%, sw]
    2. **Inline CSS Images** Convert in CSS references to local images to Data URIs for images smaller then the Maximum Data URI image size.  [61%, 23%, se]
    3. **Inline Page Images** Convert in page references to local images to Data URIs for images smaller then the Maximum Data URI image size.  [71%, 28%, sw]

1. **Max Image Size for Data URIs** sets the maximum image size to be able to be used for Data URIs. Converting an image to a base64 Data URI add about a 33% overhead. Internet Explorer 8 is limited to 32KB for a Data URI. So a good size to use to support IE would be 21612 bytes.

2. **Inline CSS Images** converts in CSS references to local images to Data URIs for images smaller then the Maximum Data URI image size.

3. **Inline Page Images** converts in page references to local images to Data URIs for images smaller then the Maximum Data URI image size.

### Font Settings
![][rokbooster_setup_5]

:   1. **Max Font Size for Data Urls** Sets the maximum font size used in Data URIs. [58%, 48%, sw]
    2. **Inline CSS Fonts** Converts fonts referenced in CSS to a data URI, if it is below the maximum DATA URI font size. [68%, 27%, sw]

1. **Max Font Size for Data Urls** sets the maximum font size used in Data URIs. Converting a font to a base64 Data URI increases overhead by about 33%. Internet Explorer 8 (IE8) is limited to 32KB Data URIs. So, the recommended size to maintain IE support would be 21612.

2. **Inline CSS Fonts** converts fonts referenced in CSS to a data URI, if it is below the maximum DATA URI font size.

### Advanced Plugin Configuration
![][rokbooster_setup_6]

:   1. **Ignored Pages** The paths, URLs, or partials to pages to be ignored by RokBooster. [33%, 71%, sw]
    2. **Ignored Files** The paths or URLs to files to be ignored by RokBooster. One file per line.  [50%, 71%, sw]
    3. **Scan Method** The method to use for script and style identification and replacement, "Joomla Header Scan", "Full Header Scan", and "Full Page Scan".  [65%, 36%, sw]
    4. **Use Background Rendering** Recommended. Render the combined and compressed cache files in the background. This will cause the first couple of hits to a page to show with uncompressed and uncollected files until the cache files are created.  [72%, 28%, sw]
    5. **Disable for Internet Explorer** Internet Explorer has hardcoded limits on the size of CSS files and rules per file that it can use. This setting lets you disable the compressed files only for IE.  [78%, 35%, sw]
    6. **Cache File Permissions** Permissions that the RokBooster cache files are created with. Don't change unless you need to.  [85%, 39%, sw]

1. **Ignored Pages** The paths, URLs, or partials to pages to be ignored by RokBooster. One file per line. Example: **/blog/stream/**. If you use double quotes ("") around a string, it will match exactly. If you don't use the quotes, it will match any part of the page to the current URL. Exact matches with double quotes should start with a forward slash (/). If you use just a forward slash and nothing else, it will match the homepage only.

2. **Ignored Files**: The paths or URLs to files to be ignored by RokBooster. One file per line. You can enter this information for a single file, or an entire folder by listing the name of the parent directory of the files you'd like to have RokBooster ignore. For exmaple, if you want RokBooster to ignore every JS file in **/jscripts**, just type `jscripts` in the box. Alternatively, you can just type the name of the file you wish to have RokBooster ignore without having to enter the directory path.

3. **Scan Method**: The method to use for script and style identification and replacement, "Joomla Header Scan", "Full Header Scan", and "Full Page Scan".

4. **Use Background Rendering**: Recommended. Render the combined and compressed cache files in the background. This will cause the first couple of hits to a page to show with uncompressed and uncollected files until the cache files are created.

5. **Disable for Internet Explorer**: Internet Explorer has hardcoded limits on the size of CSS files and rules per file that it can use. This setting lets you disable the compressed files only for IE. You can also elect to only disable compression for browsers less than IE10 while maintaining this feature for IE10+.

6. **Cache File Permissions**: Permissions that the RokBooster cache files are created with. Don't change unless you need to.

### Debug Settings
![][rokbooster_setup_7]

:   1. **Debug Log Location** Link to the debug log. May appear as **Unavailable** if no log has yet been generated. [46%, 28%, sw]
    2. **Debut Log Level** The level of information in the debug logs. [60%, 42%, sw]

1. **Debug Log Location** displays the link to the debug log. May appear as **Unavailable** if no log has yet been generated.

2. **Debut Log Level** sets the level of information in the debug logs.

[rokbooster_setup_1]: assets/rokbooster_setup_1.jpeg
[rokbooster_setup_2]: assets/rokbooster_setup_2.jpeg
[rokbooster_setup_3]: assets/rokbooster_setup_3.jpeg
[rokbooster_setup_4]: assets/rokbooster_setup_4.jpeg
[rokbooster_setup_5]: assets/rokbooster_setup_5.jpeg
[rokbooster_setup_6]: assets/rokbooster_setup_6.jpg
[rokbooster_setup_7]: assets/rokbooster_setup_7.jpeg
[rokbooster_setup_8]: assets/rokbooster_setup_8.jpeg