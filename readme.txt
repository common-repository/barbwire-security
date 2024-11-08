=== Barbwire Security ===
Contributors: munyagu
Donate link: http://munyagu.com/donate/
Tags: security,admin,Brute Force,admin rename,xmlrpc,rest api
Requires at least: 4.6
Tested up to: 5.7
Requires PHP: 5.6
Stable tag: 2.1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html



== Description ==

This plugin enhances the WordPress security.
Effective such as the brute force attack.
Includes the following specific functions.

1.Google reCaptcha v3 protect login screen from bot attacks.

2.Change the URL of the login screen, to avoid attacks on the login screen.
  You can ward off tying for try to login for cracking, such as Brute-force attack.
  Adding parameter to login URL so that default login url will hidden.

3.Block the display of author archive page
  WordPress leaks your login id because of redirect author archive page by author id to login id.
  (If you enter "your-site-url/?author=1", you can try it.)
  Simply hideing author archive page so that block to leak login id.

4.To limiting the part of the XML-RCP feature prevents the attack.
  Block DDOS attacks against other sites with yor WordPress site, pingback enabled.
  Block login via XML-RPC.

5.Disable the REST API function and reduce the risk of receiving external attacks.
  You can disable all REST APIs and you can partially disable them.
  (This feature will be removed in version 2.1.)

These features will be able to choose whether or not to enable.

This plug-in does not change the .htaccess
You can use with confidence.
Also it works in both Apache and nginx.



(photo by Keoni Cabral https://www.flickr.com/photos/keoni101/)
== Installation ==

1. Install and activate the plugin through the 'Plugins' menu in WordPress.
2. Go to Settings > Barbwire Security.
3. Perform the necessary settings and press the Save button.

== Screenshots ==

1. Setting

2. Setting

3. Help

== Changelog ==

= 2.0.1 =
fix error message to be displayed once even when the reCaptcha key was correct.
update disabling only XML-RCP pingback to disabling pingback and login.
fix typo

= 2.0.0 =
add Google reCaptcha v3 protect login screen from bot attacks.

= 1.4.7 =
add parameter to logout url

= 1.4.6.5 =
update renew readme.txt and plugin file header.
update move the translation from mo files to Polyglots

= 1.4.6.4 =
fix From version 1.4.6.3, part of the login URL change function was not working properly.
update do refactor
fix documentation

= 1.4.6.3 =
update remove unused code.

= 1.4.6.2 =
update replace deprecated action hook.

= 1.4.6.1 =
fix bug for subdirectory type WordPress.

= 1.4.6 =
update For WordPress 5.3

= 1.4.5.1 =
fix Fetal error.

= 1.4.5 =
fix Bug prevent access to password-protected content.

= 1.4.4 =
fix Error when the version of WordPress does not support REST API.

= 1.4.3 =
fix Error on setting screen in Version 4.6.x or earlier.

= 1.4.0 =
change Possible to finely set the restriction of REST API
change Move menu to submenu of option
fix Remove Notice Error in setting page
add Link to setting page to plugin list page
Refactored
Specify support for version 4.9

= 1.3.0 =
Skipped

= 1.2.1 =
fix settings page duplication
Specify support for version 4.8.2

= 1.2.0 =
Add new function, Disable the REST API
Refactor source codes

= 1.1.1 =
fix readme.txt

= 1.1.0 =
fix disnable pingback function was not working
add function block the display of author archive page
add help documentation

= 1.0.3 =
fix login page will divulge, when using Permalink settings
Thanks to @nyarocom pointed out.(https://wordpress.org/support/topic/login-page-will-divulge/)

= 1.0.2 =
fix php warning message

= 1.0.1 =
fix error error of removing the plugin

= 1.0.0 =
First release
