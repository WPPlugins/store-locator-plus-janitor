=== Store Locator Plus - Janitor ===
Plugin Name:  Store Locator Plus - Janitor
Contributors: charlestonsw
Donate link: https://www.storelocatorplus.com/product/store-locator-plus-janitor/
Tags: search form, google maps, cleaning, janitor, database, locator
Requires at least: 3.8
Tested up to: 4.8
Stable tag: 4.8

A free add-on to assist with extra maintenance during major upgrades or porting to new systems for the Store Locator Plus plugin.

== Description ==

A free add-on pack for the [Store Locator Plus](https://www.storelocatorplus.com/) location mapping system plugin.
This add-on assists in cleaning up the Store Locator Plus settings including clearing out all pre-existing settings that may
interfere with upgrading or installing on a new server after restoring a WordPress backup.   Allows Store Locator Plus add-ons
to behave as if the plugin activation is happening on a new install.

= Options Clean Up =

Delete all [Store Locator Plus](https://www.storelocatorplus.com/) settings from the WordPress options table while retaining location data.

Current add-on packs are also supported:

* [Experience](https://www.storelocatorplus.com/product/experience/)
* [Power] (https://www.storelocatorplus.com/product/power/)
* [Premier](https://www.storelocatorplus.com/product/premier-subscription/)

Legacy add-on packs supported:
* [Contact Extender](https://www.storelocatorplus.com/product/slp4-contact-extender/)
* [Directory Builder] (https://www.storelocatorplus.com/product/directory-builder/)
* [Enhanced Map](https://www.storelocatorplus.com/product/slp4-enhanced-map/)
* [Enhanced Results](https://www.storelocatorplus.com/product/slp4-enhanced-results/)
* [Enhanced Search](https://www.storelocatorplus.com/product/slp4-enhanced-search/)
* [Pro Pack](https://www.storelocatorplus.com/product/slp4-pro/)
* [Tagalong](https://www.storelocatorplus.com/product/slp4-tagalong/)
* [Widget Pack](https://www.storelocatorplus.com/product/slp4-widgets/)

Third party add-on packs supported:
* [Event Location Manager](https://www.storelocatorplus.com/product/event-location-manager/)
* [Gravity Forms Integration](https://www.storelocatorplus.com/product/gravity-forms-integration/)
* [Multi Map](https://www.storelocatorplus.com/product/multi-map/)
* [Social Media Extender](https://www.storelocatorplus.com/product/slp4-social-media-extender/)
* [User Managed Locations](https://www.storelocatorplus.com/product/slp4-user-managed-locations/)

= Description Decoding =

Prior versions of Store Locator Plus may have encoded HTML while storing the data in the location descriptions.
A one-time-use tool will repair the location descriptions, converting the HTML encoded data to standard HTML
notation.   If you are seeing text such as &lt;br/&gt; instead of <br/> in your description data, you need this tool.

== Installation ==

= Requirements =

* Store Locator Plus: 4.4.31
* Wordpress: 3.8
* PHP: 5.2

= Install After SLP =

1. Go fetch and install Store Locator Plus version 4.0 or higher.
2. Purchase this plugin from CSA to get the latest .zip file.
3. Go to plugins/add new.
4. Select upload.
5. Upload the zip file.

== Frequently Asked Questions ==

= What are the terms of the license? =

The license is GPL.  You get the code, feel free to modify it as you
wish.  I prefer customers pay me because they like what I do and
want to support my efforts to bring useful software to market.  Learn more
on the [SLP License Terms](https://www.storelocatorplus.com/products/general-eula/).

== Changelog ==

= 4.8 =

Ensure SLP_Settings is loaded when required.

= 4.6.5 =

Updates to maintain compatibility with SLP 4.6.5.

= 4.4.04 =

Requires SLP 4.4.31 for updated location delete method.

= 4.4.03 =

Enhancements

* Add GFI and GFL settings.
* Simplify the admin interface to have tools and settings only.
* Clean up the settings interface.

Changes

* Requires SLP 4.4.27
* Texdomain changed to slp-janitor per WP standard.

Fixes

* Resetting of individual options_nojs settings for base plugin.

= 4.4.02 =


Show SLP Installed Base version used to trigger activation/update code.

= 4.4.01 =

Add a one-click reset for the Plugin Style cache.

= 4.4 =


Settings page will not show options that don't exist in the WordPress options table.
Update to support new Power and Experience add-on packs.
Add back the themes array setting so it can be cleared.