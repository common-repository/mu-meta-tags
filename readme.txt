=== MU Meta Tags ===
Contributors: wilecoyote
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6922896
Tags: meta tags
Requires at least: 2.7.1
Tested up to: 2.8.2
Stable tag: 1.0

Add HTML meta tags to a theme header when the theme is used across multiple blog-based sites, such as when using the multi-user version WordPress.

== Description ==

The mu_metatags plug-in was designed for two purposes. One, it is a means to present a very simple tutorial about how to write a plug-in for novice users, and two, it solves a problem of unique meta tags in a single theme header when that theme is used on one or more sites.

The problem arises when the same theme is used by multiple sub-domain sites (URLs) within the multi-user framework of WordPress. You cannot simply place the desired meta tags in the header.php file because those parameter values would apply to every site that references that theme, thereby defeating the purpose of unique meta tags. The MU Meta Tags plug-in meets both purposes.


== Installation ==

Installation is straight forward, as there are no special files, and no unique configuration settings.

1. Upload `mu_metatags.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

This plug-in was designed in part as a tutorial for writing WordPress plug-ins. You can read the tutorial at http://coyotesdesigns.com/mu-meta-tags/

== Frequently Asked Questions ==

none

== Screenshots ==

none

== Changelog ==

= 1.0 =
* Initial release. No known issues.

