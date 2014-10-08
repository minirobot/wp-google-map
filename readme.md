
# Plugin Description
This plugin is based on *One Website , One Map , One Marker* theme.
However it may support multiple maps in future.
This is the simplest and non-bloated WordPress Google Map Plugin.Made for noobs.
Written in pure javascript, no jQuery at all, responsive, configurable, no ads and 100% Free of cost.

- - -



>**Download the Last version from [here](https://wordpress.org/plugins/ank-google-map)**



## Installation Guide
- Login to WordPress Admin panel
- Go through menus Plugin->Add New
- Search for `ank google map`
- Install the plugin via WordPress interface.
- Activate the plugin when asked
- Configure Map options from Settings->Ank Google Map
- Paste `[ank-google-map`] shortcode in your pages

- - -
## Requirements
- WordPress v3.8+ (latest will be better)
- HTML5 Supported Browser (latest Firefox,Chrome,Safari,Opera,IE)

- - -



## Features
- Configure map height and width.
- Responsive map, auto center map upon resize.
- Configure map border color.
- Disable/Enable map controls.
- Find location by address (Autocomplete)
- Change map's language eg:Hindi/Urdu
- Place animated marker on map
- Select colorfull Markers
- Place info window on marker with custom text/markup.

- - -


## FAQ

**Why did u call it Light Weight ?**

Because it does not depend on jQuery, written in pure Java Script.
Options page utilize inbuilt jQuery and Color Picker.
It uses WP dash-icons in Plugin Options Page.
It does not create additional tables in your database, uses inbuilt wp_options table.

**What do you mean by Non Bloated**

There are many of Map plugins in plugin directory, but most of them not written well.
Means they put lots of java script (uncompressed) code on every page of your website.
They also loads jquery file before them which effect your page speed.
This plugin will put its code on the page where it was called only.
It will write compressed java script code, and does not depends on external js library like:jQuery.


**Options page does not work well :(**

You must have modern browser to configure the map option.
Old browsers will not work well.

**Color picker could not load :(**

This plugin utilize inbuilt WP Color API.
You must have WordPress v3.5+ in order to use this feature.

**Shortcode does not work in text widget**

Add this line to your theme's functions.php

`add_filter( 'widget_text', 'do_shortcode' );`

**Changes does not reflect after saving settings ?**

Are you using some Cache/Performance plugin ? Flush your WP cache and refresh target page.

**Where does it store settings and options ?**

WP Database->wp-options->ank_google_map.
In a Single Row, stored in array for faster access.

**From where does it loads additional Marker (color) images ?**

Every marker image is loaded from official Google Server.

**What if i uninstall/remove this plugin?**

No worry! It will remove its traces from database upon uninstall.
You have to remove short-code from your pages by yourself.

**How do i enter correct language code ?**

You can get latest supported language code list from [here](https://spreadsheets.google.com/pub?key=p9pdwsai2hDMsLkXsoM05KQ&gid=1)



**How to make it responsive**

Set Map Canvas Width to 100 %.


**Do you hate jQuery ?**

No, I love it as like you. But I prefer faster websites.

**Can i modify this plugin ?**

Yes you can. But you can't make money by selling this. You can ask for donation.

**Any plan to support more than one map.**

Only if i got some time to code.

**Is Google Map API is free.**

Until we break its terms and conditions.
Google Map API V3 does not need an API Key.

**Future Plans ?**

* Localization for Option Page.
* More security approaches.
* More options.

- - -

Created By: *Ankur Kumar* &copy; 2014