# Gravity Forms to Avala API Add-On

A custom Gravity Forms add-on to submit Gravity Forms entries to Avala Aimbase CRM

## Installation ##

1. Download plugin Zip file
2. Unpack files to `avala-api-gforms-feed` directory in your WordPress plugins directory
3. Activate plugin
4. Go to Gravity Forms settings > Avala API and enter your API information
5. Go to Form Settings and create a new connection

## Requirements ##

This plugin requires a subscription to Aimbase CRM that supports API POSTs, as well as the Gravity Forms plugin for WordPress.

## Notes ##

This plugin is not officially supported by Avala or the Aimbase Marketing Automation platform. If you are to use this plugin, the arrays for Lead Types, Categories and Sources are hard-coded in this plugin, and do not use Aimbase Lead API to dynamically generate these values. These need to be changed to match your Lead values from your individual Aimbase deployment subscription and updated everytime one of these values is changed in Aimbase. If the submitted Source, Type or Category is incorrect, it will fail to submit during the lead staging process.
