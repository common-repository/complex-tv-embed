=== Plugin Name ===
Contributors: complex_ntrsctn
Tags: complextv, ooyala
Requires at least: 3.0.1
Tested up to: 4.2
Stable tag: 1.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Donate link: 

Creates a Shortcode to Embed Videos from Complex TV Publisher Hub.

== Description ==

This plugin creates a Shortcode to embed Videos from Complex TV Publisher Hub.

It also adds a Settings page to store default values for your Sitename, Player ID, Adset ID, and default Video Width & Height values, which are used as defaults when generating the shortcode.

Site's using this plugin should be Publishers on the Complex Media Publishers Network.

The shortcode should be in this format `[complextv contentid="" sitename="" playerid="" adsetid="" width="" height="" keywords=""]`

== Installation ==

1. Upload `complex-tv-embed` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to `Settings > Complex Tv Embed` to fill in default values for:

    * Sitename
    * Player ID
    * Adset ID
    * Video Width
    * Video Height

== Frequently Asked Questions ==

= What is the purpose of this plugin? =

Videos that are embedded / shared from Complex TV use a javascript tag to create the video, and WordPress strips these out for security reasons.
This plugin creates a shortcode for these videos making it easier to embed video from Complex TV.

== Screenshots ==

1. The Settings page to fill in after activating the plugin, which can be found in `Setting > ComplexTV Embed`

== Changelog ==

= 1.4 =
* Schemaless Player URL

= 1.3 =
* 

= 1.2 =
* Updated embed code with new player URL, General clean up

= 1.1 =
* Fix for default values not populating shortcode. Exclude unnecessary arguments.

= 1.0 =
* Complex TV Embed plugin

== Upgrade Notice ==

= 1.0 =
* Complex TV Embed plugin
