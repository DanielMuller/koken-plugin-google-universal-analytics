Google Universal Analytics plugin for Koken
===========================================

This [Koken](http://koken.me) plugin is based on Koken's plugin [koken-google-analytics](https://github.com/koken/koken-google-analytics). It automatically generates and inserts Google Universal Analytics tracking code into your published site, regardless of what theme you have selected.

This version allow you to specify the location of the analytics.js in case you want to selfhost that file. This give the avantage to be able to configure proper caching but has the drawback of not being updated automatically in case of new version from Google.

A [Koken](http://koken.me) installation (0.2.0 or higher) and a free [Google Analytics](www.google.com/analytics) account are required.

Installation
------------

- Create the folder *storage/plugins/mesphotos-google-universal-analytics* under your Koken root folder.
- Copy *plugin.json* and *plugin.php* to this folder.
- In your admin dashboard, activate and configure the plugin under *Settings/Plugins*
    - Configure your Tracking ID e.g: UA-XXXXXXXX-X
    - Configure your tracking domain: yoursite.com
    - Configure your tracking Javscript Location:
        - The default from Google is www.google-analytics.com/analytics.js
        - But you can selfhost the file on your server. E.g: www.yoursite.com/koken/storage/custom/analytics.js

Todo
----

Use site configuration to access tracking_domain
