---
title: RokWeather: Widget Configuration
description: Your Guide to Using the RokWeather Widget for Grav
breadcrumb: /grav:Grav/!plugins:Plugins/rokweather:RokWeather

---

Using RokWeather
-----

RokWeather is a highly configurable widget that allows you to control the various aspects of its appearance and functions. Not only is this widget configurable in the backend, but you can double-click the location from the frontend and change it without having to access the administrator account at all. This is a small, but useful function that users can take advantage of.

### Widget Options

![][widget]

:   1. **Title** This title will appear over the widget on the frontend. If left blank, no title will appear. [15%, 10%, ne]
    2. **Source** Choose between Yahoo or Wunderground. [20%, 10%, ne]
    3. **Default Location** Enter a location that will have its weather data displayed by default. For example, the default option is Golden, CO. [26%, 10%, ne]
    4. **Location Display Override** This option allows you to display weather data for one location whilst displaying a label for another, such as using a nearby city's weather data but displaying the name of your own town. [33%, 10%, ne]
    5. **Forecast Items to Show** This setting determines how many days ahead the widget will display a forecast for. [47%, 10%, ne]
    6. **Default Degree Type** Choose between degree Celsius or Fahrenheit for the default temperature reading. [52%, 10%, ne]
    7. **User interaction** This parameter allows to disable user interaction so they cannot change the location and weather data. [56%, 10%, ne]
    8. **Enable Units Switch** This option allows you to configure whether the Celsius/Fahrenheit switch is displayed. [60%, 10%, ne]
    9. **Location Caching** Enables or disables a location cache. [64%, 10%, ne]
    10. **Enable Location Cookie** A cookie is created when a user enters a location which will be stored for when the user visits again. This option allows you to disable the setting of a cookie, and therefore, the default location will be shown on each refresh. [67%, 10%, ne]
    11. **Enable Icon Display** Determine whether or not the weather icon displays in the top left of the module. [71%, 10%, ne]
    12. **Enable Humidity Display** An option to display humidity for the selected location. [75%, 10%, ne]
    13. **Enable Wind Display** An option to display wind data for the selected location. [79%, 10%, ne]
    14. **Default Windspeed Type** Determine what units to display for wind speed, either MPH, KPH or KTS. [82%, 10%, ne]
    15. **Enable Weather Forecasts** Enable the display of forecast weather data. [86%, 10%, ne]

1. **Title**: This title will appear over the widget on the frontend. If left blank, no title will appear.

2. **Source**: Choose between Yahoo or Wunderground. For Wunderground, you will need to sign up to their API and enter their reference in the API key field: [http://www.wunderground.com/][wunderground]

3. **Default Location**: Enter a location that will have its weather data displayed by default. For example, the default option is Golden, CO.
>> Some locations may return as invalid, although available on the respective sources due to limitations in their APIs, not RokWeather.

4. **Location Override**: This option allows you to display weather data for one location whilst displaying a label for another, such as using a nearby city's weather data but displaying the name of your own town.

5. **Forecast Items to Show**: This setting determines how many days ahead the widget will display a forecast for. This only works if **Enable Weather Forecasts** is turned on under **General Settings**.

6. **Default Degree Type**: Choose between degree Celsius or Fahrenheit for the default temperature reading.

7. **User interaction**: This parameter allows to disable user interaction so they cannot change the location and weather data.

8. **Enable Units Switch**: This option allows you to configure whether the Celsius/Fahrenheit switch is displayed.

9. **Location Caching**: Enables or disables a location cache.

10. **Enable Location Cookie**: A cookie is created when a user enters a location which will be stored for when the user visits again. This option allows you to disable the setting of a cookie, and therefore, the default location will be shown on each refresh.

11. **Enable Icon Display**: Determine whether or not the weather icon displays in the top left of the module.

12. **Enable Humidity Display**: An option to display humidity for the selected location.

13. **Enable Wind Display**: An option to display wind data for the selected location.

14. **Default Windspeed Type**: Determine what units to display for wind speed, either MPH, KPH or KTS.

15. **Enable Weather Forecasts**: Enable the display of forecast weather data.


[wunderground]: http://www.wunderground.com/
[options1]: assets/rokweather_options_1.png
[options2]: assets/rokweather_options_2.png
[options3]: assets/rokweather_options_3.png
[widget]: assets/wp_rokweather_widget.png