WP Flipclock
============

The repository for WP Flipclock on Github.

Description
-----------
WP Flipclock is a plugin that allows you to quickly and easily add a flipclock to your site’s posts and pages via a shortcode.

The plugin allows you to count down or up from a specific date, as well as choose whether you count down days, hours or minutes.

This plugin uses the [Flipclock.js](http://www.flipclockjs.com) library from [ObjectiveHTML](https://www.objectivehtml.com/).

Demo
----
On the [WP Flipclock](http://winwar.co.uk/plugins/wp-flipclock/) page.

Installation
------------
1. Upload the plugin (unzipped) into `/wp-content/plugins/`.
2. Activate the plugin under the “Plugins” menu.

Usage
-----
To use the plugin in your site, all you need to add to the page is the [flipclock] shortcode. There are various attributes you can add as well:-

* **name** - Give the flipclock a name. Default is “flipclock”. If you have more than one flipclock on any page it’s useful to give them unique names.
* **countdown (True/False)** - Allows you to count down to a date (true), or count up from a date (false). Default is *false*.
* **date** – Any date string, formatted how you like, which the clock will count up from/down to. Default is *none*.
* **face (days/hours/minutes)** - The face of the clock. Default is hours. Options are:-
⋅⋅*days – Days : Hours : Minutes : Seconds
⋅⋅*hours - Hours : Minutes : Seconds
⋅⋅*minutes - Minutes : Seconds
* **lang** - Changes the language of the labels (days,hours,minutes,seconds). Supported languages: English, Russian, Spanish, French, German.
* **timezone** - Sets timezone for date. Now it shows the correct time before the event. (fix issue #2 Time Localisation). The time zones have unique names in the form "Area/Location", e.g. "America/New_York".
* **seconds** - Hides|shows seconds in face-mode "days". 
⋅⋅*1 - shows seconds
⋅⋅*0 - hide seconds

Props
-----
1.5
---
[gleave75](https://github.com/gleave75) who discovered a bug in v1.4 where the countdown timer was out by how far away that time zone was from UTC.

1.4
---
* [Den Kalinin](https://github.com/dek30rus) for his work integrating languages & and timezones.