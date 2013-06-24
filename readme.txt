=== Cryptocurrency Ticker ===
Contributors: bitstein
Tags: bitcoin, ticker, cryptocurrency, quote, price
Requires at least: 2.8
Tested up to: 3.5.1
Stable tag: 0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Based on: Cryptocurrency Ticker by CryptoBadger - http://wordpress.org/plugins/cryptocurrency-ticker/

Wordpress plugin that fetches, caches, and displays current Bitcoin prices from various exchanges using the Bitcoincharts API.

== Description ==

Bitcoin Ticker displays current cryptocurrency prices (bitcoin and litecoin) on your WordPress site. You can choose to display a current bitcoin and/or litecoin price.

Prices are fetched from Bitcoincharts.com using their markets API.

Ticker prices are cached for a duration that you specify in the widget menu, to improve performance and prevent your site from making too many requests from bitcoincharts.com.

== Installation ==

1. Upload the contents of the plugin .zip to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. In the 'Widgets' menu in WordPress, place the widget where you want it to appear on your site
4. Verify that the plugin's settings are what you want in the widget menu

== Frequently Asked Questions ==

= Can I change the look of the widget? =

Yes, simply modify the included crypto-ticker.css file, located in the plugin's /css directory.

= Can the ticker display prices in currencies other than USD? =

Not at the moment. If there is enough interest I'll add other currencies later.

= Help! The ticker doesn't seem to be fetching prices! =

Try temporarily disabling any other Wordpress caching plugins that you're running, and then delete my plugin's cache from the options menu. If that doesn't work, ensure that outbound traffic on port 443 (SSL/HTTPS) is open from your server - the plugin fetches quotes on that port.

== Changelog ==

= 0.1 =
* Initial release.

== Donations ==

If this plugin helped you, feel free to tip me.

* 16YwwzQfEzxoa2AVVt79QsYMTiDAbFPCpq