=== WooCommerce Product Custom Tab ===
Contributors: Sunita, Ravi Raiya
Donate link: http://wordpressmarket.com/market-item/woocommerce-product-custom-tab/
Tags: woocommerce product tabs, woocommerce product custom tabs, woo product custom tabs, woo product tabs
Requires at least: 3.3
Tested up to: 3.7.1
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This Lite Version plugin extends the WooCommerce plugin by adding custom product tab which may contain text, html or shortcodes.

== Description ==

This plugin extends the WooCommerce plugin by adding custom product tab which may contain text, html or shortcodes.

To easily add multiple tabs, share tabs between products, and more features, consider upgrading to the premium [WooCommerce Product Custom Tab Pro ](http://wordpressmarket.com/market-item/woocommerce-product-custom-tab/)


= Feedback =
* We are open to your suggestions and feedback - Thank you for using or trying out one of our plugins!
* Drop us a line at [www.bigfoottechnorati.co.in](http://www.bigfoottechnorati.co.in)

= More =
* [Also see our other plugins](http://www.bigfoottechnorati.co.in) or see [our WordPress.org profile page](http://profiles.wordpress.org/sunita121981/)
* Upgrade to the WooCommerce Product Custom Tab Pro now available On [WooCommerce Product Custom Tab Pro](http://wordpressmarket.com/market-item/woocommerce-product-custom-tab/)

= More =



== Installation ==

1. Upload the entire 'woo-product-tab' folder to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Edit a product, then click on 'Custom Tab' within the 'Product Data' panel

== Frequently Asked Questions ==

If you have any problem with the plugin, please contact me.

== Screenshots ==

1. Install plugin
2. add custom tabs in product

== Frequently Asked Questions ==

= How do I hide the tab heading? =

use following code to the bottom of your theme's functions.php:

`
add_filter( 'woo_custom_product_tabs_head', 'woo_custom_product_tabs_head_heading' );
function woo_custom_product_tabs_head_heading( $heading ) { return ''; }
`

== Changelog ==

= 1.0 =
Initial version

== Upgrade Notice ==

= 1.0 =
No upgrades yet.