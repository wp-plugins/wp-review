=== WP Review ===
Contributors: mythemeshop
Creator's website link: http://mythemeshop.com/
Tags: review, wp review, rating, wp rating, user rating, google rating, star rating, product review
Requires at least: 3.0.1
Tested up to: 3.9
Stable tag: 2.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Create reviews! Choose from stars, percentages or points for review scores. Supports Retina Display, WPMU & Unlimited Color Schemes.

== Description ==

Did you always want to increase the user interaction on your website by rating products/services/anything? We at <a href="http://mythemeshop.com/">MyThemeShop</a> understand your need, & created a premium Review plugin. We are now distributing it for FREE to give back to the WordPress community. We have been given so much by the WordPress community, it's time to give back.

**WP Review plugin** is an easy yet powerful way to review content easily, without affecting the speed of your site. If you're a blogger, you probably occasionally review or rank products, services, tools, recipes, or other content on your site. WP Review plugin is a customizable and lightweight way to create reviews, using stars, percentage or point rating, and it includes support for translation, WPMU, Google rich snippets and unlimited colors. Just install it and follow the simple configuration instructions to place it in your desired location.

= Live Demos =
<blockquote>See WP Review in action on our demo pages:
<a href="http://demo.mythemeshop.com/spike-gaming/2014/03/12/the-12-most-inspirational-female-characters-in-games/" target="_blank">Star Review Type</a>,
<a href="http://demo.mythemeshop.com/spike-wedding/2014/03/13/top-10-wedding-guest-complaints/" target="_blank">Point Review Type</a>,
<a href="http://demo.mythemeshop.com/spike-health/2014/02/27/high-calorie-foods-you-should-never-eat-before-going-to-bed/" target="_blank">Percentage Review Type</a></blockquote>

= Why WP Review from <a href="http://mythemeshop.com">MyThemeShop</a>: =
* Fastest review plugin.
* Stars, percentage and point rating system.
* Supports Google Rich Snippets(schema.org)
* 100% Fluid Responsive.
* WP Multisite and Multiuser (WPMU / WPMS / WordPress MU) compatible.
* Design it as you want, unlimited color options.
* Translation Ready.
* Reviews are displayed to visitors in a friendly format.
* Completely customizable, including which fields to ask for, require, and show.
* Minimal design but could be instantly made modern.
* Works with caching plugins and all majority of themes.
* Easy to modify the CSS to better fit your theme style.
* Support for adding your own custom fields.
* Minimalist, lightweight, and efficient code means that your users won’t notice any hiccups.
* Position it above or below the content with ease and no coding.
* Supports Shortcode `[wp-review]` to show review anywhere in post.

= Support =
We will do our best to provide support through the WordPress forums. However, all plugin support is provided in our forum. If you have not registered yet, you can do so here: <a href="https://mythemeshop.com/go/signup/index/c/free">https://mythemeshop.com/go/signup/index/c/free</a>. After searching the knowledge base and forum if you are still stuck, feel free to open a new thread, and a member of our support team will be happy to help. Cheers!<br>
Support link: <a href="http://community.mythemeshop.com/forum/free/plugin-support">http://community.mythemeshop.com/forum/free/plugin-support</a>

= Developer Zone =
Yes, this plugin is so developer friendly, so you could use it with any theme you develop. Define default CSS, custom position, one line integration in your theme's code.

Show average review in your theme using below function:
`<?php if (function_exists('wp_review_show_total')) wp_review_show_total(); ?>`

GitHub link: <a href="https://github.com/MyThemeShop/WP-Review-by-MyThemeShop">https://github.com/MyThemeShop/WP-Review-by-MyThemeShop</a>

= Feedback =
If you like this plugin, then please leave us a good rating and review.<br> Consider following us on <a rel="author" href="https://plus.google.com/+Mythemeshop/">Google+</a>, <a href="https://twitter.com/MyThemeShopTeam">Twitter</a>, and <a href="https://www.facebook.com/MyThemeShop">Facebook</a>

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload the `wp-review` folder to the to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. You can see rating options on single post editor.
4. Configure the available rating options as you want.

== Frequently Asked Questions ==

= User rating not working =

Please disable all plugins and check if rating is working properly. Then you can enable all plugins one by one to find out which plugin is conflicting with WP Rating plugin.

== Screenshots ==

1. Plugin Options
2. Plugin Options 2
3. Star Review type
4. Point Review type
5. Percentage Review type

== Changelog ==

= 2.0 =
* Fixed the, `'` switching in to `/` issue (<a href="http://bit.ly/PFMGAq">http://bit.ly/PFMGAq</a>)
* Added `[wp-review]` shortcode to show the ratings anywhere in the content.
* Added an option to not show review automatically in the Review Location dropdown.
* Added support for Custom post types and pages.
* For Developers Added new function for showing only total rating, it could be used in themes' archives. A custom class name can be passed to the function, for easier customization. See `wp_review_show_total()` function in includes/functions.php file. There's also a shortcode for it, just in case: [wp-review-total]
* For Developers Added the default colors which appear in the meta boxes are now stored in an option. It can be modified directly with `update_option()`, or using the new `wp_review_set_default_colors()` function, which is also called on plugin activation to set the plugin's default colors.
* Made small CSS and responsive improvements.

= 1.0 =
* Official plugin release.