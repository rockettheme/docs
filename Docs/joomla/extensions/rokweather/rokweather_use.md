---
title: RokWeather: Module Configuration
description: Your Guide to Using the RokWeather Module for Joomla
breadcrumb: /joomla:Joomla/extensions:Extensions/rokweather:RokWeather

---

Using RokWeather
-----

RokWeather is a highly configurable module that allows you to control the various aspects of its appearance and functions. Not only is this module configurable in the backend, but you can double-click the location from the frontend and change it without having to access the administrator account at all. This is a small, but useful function that users can take advantage of.

### Basic Options

![][options3]

:   1. **Sources** Choose between Yahoo or Wunderground. [30%, 64%, sw]
    2. **Default Location** Enter a location that will have its weather data displayed by default. For example, the default option is Golden, CO. [50%, 64%, sw]
    3. **Location Display Override** This option allows you display weather data for one location whilst displaying a label for another, such as using a nearby city's weather data but displaying the name of your own town. [59%, 64%, sw]
    4. **Forecast Items to Show** This setting determines how many days ahead the module will display a forecast for. [79%, 64%, sw]

1. **Sources**: Choose between Yahoo or Wunderground. For Wunderground, you will need to sign up to their API and enter their reference in the API key field: [http://www.wunderground.com/][wunderground]

2. **Default Location**: Enter a location that will have its weather data displayed by default. For example, the default option is Golden, CO.

    >> Some locations may return as invalid, although available on the respective sources due to limitations in their APIs, not RokWeather.

3. **Location Display Override**: This option allows you display weather data for one location whilst displaying a label for another, such as using a nearby city's weather data but displaying the name of your own town.

4. **Forecast Items to Show**: This setting determines how many days ahead the module will display a forecast for. This only works if **Enable Weather Forecasts** is turned on under **General Settings**.

![][options2]

:   1. **Default Degree Type** Choose between degree Celsius or Fahrenheit for the default temperature reading. [14%, 62%, se]
    2. **User interaction** This parameter allows you to disable user interaction so visitors of your site cannot change the location and weather data on frontend. [22%, 62%, se]
    3. **Enable Units Switch** This option allows you to configure whether the Celsius/Fahrenheit switch is displayed. [31%, 62%, se]
    4. **Enable Location Cookie** A cookie is created when a user enters a location which will be stored for when the user visits again. This option allows you to disable the setting of a cookie, and therefore, the default location will be shown on each refresh. [40%, 62%, se]
    5. **Enable Icon Display** Determine whether or not the weather icon displays in the top left of the module. [48%, 62%, se]
    6. **Enable Humidity Display** An option to display humidity for the selected location. [56%, 62% se]
    7. **Enable Wind Display** An option to display wind data for the selected location. [65%, 62%, se]
    8. **Default Windspeed Type** Determine what units to display for wind speed, either MPH, KPH or KTS. [73%, 62%, se]
    9. **Enable Weather Forecasts** Enable the display of forecast weather data. [84%, 62%, se]

1. **Default Degree Type**: Choose between degree Celsius or Fahrenheit for the default temperature reading.

2. **User interaction**: This parameter allows to disable user interaction so they cannot change the location and weather data.

3. **Enable Units Switch**: This option allows you to configure whether the Celsius/Fahrenheit switch is displayed.

4. **Enable Location Cookie**: A cookie is created when a user enters a location which will be stored for when the user visits again. This option allows you to disable the setting of a cookie, and therefore, the default location will be shown on each refresh.

5. **Enable Icon Display**: Determine whether or not the weather icon displays in the top left of the module.

6. **Enable Humidity Display**: An option to display humidity for the selected location.

7. **Enable Wind Display**: An option to display wind data for the selected location.

8. **Default Windspeed Type**: Determine what units to display for wind speed, either MPH, KPH or KTS.

9. **Enable Weather Forecasts**: Enable the display of forecast weather data.

### Advanced Options

![][options1]

:   1. **Module Class Suffix** This is a suffix applied to the CSS class of the module. This allows for individual module styling. [18%, 45%, se]
    2. **Caching** Selects whether or not to cache the content of this module. [30%, 80%, sw]
    3. **Cache Time** This option sets the time between module recaching. [38%, 45%, se]
    4. **Module Tag** This sets the HTML tag for the module. [49%, 80%, sw]
    5. **Bootstrap Size** This option specifies how many columns the module will use. [57%, 45%, se]
    6. **Header Tag** This field sets the HTML tag for the module header/title. [65%, 80%, sw]
    7. **Header Class** This field sets the CSS class for the module header/title. [73%, 45%, se]
    8. **Module Style** This option allows for an override of the template style for its position. [81%, 80%, sw]

1. **Module Class Suffix**: A suffix applied to the CSS class of the module. This allows for individual module styling.

2. **Caching**: Selects whether or not to cache the content of this module.

3. **Cache Time**: Sets the time between module recaching.

4. **Module Tag**: Sets the HTML tag for the module.

5. **Bootstrap Size**: Specifies how many columns the module will use.

6. **Header Tag**: Sets the HTML tag for the module header/title.

7. **Header Class**: Sets the CSS class for the module header/title.

8. **Module Style**: Allows for an override of the template style for its position.


[wunderground]: http://www.wunderground.com/
[options1]: assets/rokweather_options_1.jpeg
[options2]: assets/rokweather_options_2.jpeg
[options3]: assets/rokweather_options_3.jpeg
