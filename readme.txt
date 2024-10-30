=== Fast Retina Images (Lazy Load) ===
Contributors: bitnulleins
Tags: lazy load, retina, performance, images, bit01, wordpress
Requires at least: 3.8
Tested up to: 5.6
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Automatically loads normal or retina versions of images while scrolling.

== Description ==

*Fast Retina Images (Lazy Load)* boost your website performance and reduce the traffic because images outside of viewport (visible part of web page) won't be loaded until the user scrolls to them. This *lazy* technique works with jQuery or zepto.js.

*Lazy Retina* loads by default:

* thumbnails
* images in posts
* images in pages

This plugin is based on [Unveil.js](http://luis-almeida.github.io/unveil/).

= Retina Images =

The Lazy Retina plugin automatically adds retina sizes to every (custom) image size.

You've to [regenerate](http://wordpress.org/plugins/regenerate-thumbnails/) already uploaded images.

= Support in Themes =

If you want to *lazy load* an image in themes please use the following code:

`<?php if (function_exists('lazy_retina_image') { echo lazy_retina_image( $image_id, $size, $attr ); } ?>`

= Settings =

Under "Options" -> "Media" you can remove the default link to full image path

= Author =

* [Website (German)](http://www.bit01.de)

== Installation ==

Go to "Plugins" -> "Install". Search for "Lazy Retina", install and activate it.

Alternative Way:

* Download the zip-File and export it to the ./wp-content/plugins/ path.
* Activate the plugin at the backend.

== Frequently Asked Questions ==

= What if my image is too small for retina version? =

It'll return the normal sized image.

= Which size must an image have for retina? =

The image size have to at least the double of original width and height.

== Screenshots ==

1. Image link settings

== Changelog ==

= 1.2.1 =

* Tested up to WP 5.6

= 1.2 =

* Tested up to WP 5.2.2

= 1.0.2.1 =

* Bug fixed, caused by empty arrays

= 1.0.2 =

* Updated version for WordPress 4.7.6+

= 1.0.1 =
* Fix some bugs

= 1.0 =
* First version appeared

== Upgrade Notice ==

No upgrades.
