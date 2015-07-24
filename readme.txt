=== eveeno ===
Contributors: babo2015
Tags: event, registration, form
Requires at least: 4.1
Tested up to: 4.2.2
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WordPress plugin for embedding eveeno registration forms.

== Description ==

Embed registration forms and event lists from [eveeno.de](https://eveeno.com) in your WordPress site simply by adding a shortcode.
All you need is your event id (for embedding a registration form), your user id (for embedding an event list) and eventually the width and height. 
You will find the event id and the user id in your eveeno backend under Event-Einstellungen > Widgets.

= Examples =
Embedding a registration form:
`
[eveeno show="form" eventid="123456789" width="95%" height="1000px"]
`
Embedding an event list as a table:
`
[eveeno show="table" userid="1234" width="95%" height="400px"]
`
Embedding an event list in grid view:
`
[eveeno show="grid" userid="1234" width="95%" height="400px"]
`

== Installation ==

1. Upload `eveeno.php` and eventually the languages `folder` to the `/wp-content/plugins/eveeno` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Place a shortcode in your page or post.

== Changelog ==

= 1.1 =
* Added shortcodes for event lists (table and grid view)
* Changed name parameter to id as event names may change

= 1.0 =
* First release: shortcode for registration forms
