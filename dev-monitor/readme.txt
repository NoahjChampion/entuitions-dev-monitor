=== Dev Monitor ===
Contributors: onodev
Donate link: http://onodev.com/donate/
Tags: development, admin bar, queries, javascript, css, conditionals
Requires at least: 3.9
Tested up to: 3.9.1
Stable tag: 1.1.0
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Monitor Scripts, Styles, Queries, and more during Development

== Description ==

Dev Monitor optionally adds SQL Query, Memory Usage, Execution Time, Javascript, CSS, Wordpress Conditionals, and included theme and plugin PHP file information to the admin bar for users with the appropriate permissions. Use this plugin to aid your development by making it easy to see which files are included and where.

== Installation ==

1. Upload the plugin to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Visit Settings > Dev Monitor to choose which options you would like to display.

== Frequently Asked Questions ==

= Why can't I see the queries? =

Make sure SAVEQUERIES is defined in your wp-config.php. Add the following line:

`define('SAVEQUERIES',true);`

== Screenshots ==

1. Dev Monitor adds some information to your admin bar about Queries, Execution Time, Memory, Theme/Plugin PHP Includes, Javascript includes, CSS includes, and Widgets.
2. Mouse over the Dev Monitor Stats to get added information. Here you can see the Javascript handles for all of the enqueued scripts.
3. The included PHP Files located in your themes or plugin directory.
4. A list of queries (assuming SAVEQUERIES has been defined)
5. The CSS handles for all of the enqueued styles.
6. True/False conditional menu
7. Page Specific conditional menu

== Changelog ==

= 1.1.0 =
* Added "Wordpress Conditionals" submenu

= 1.0.1 =
* Added Screenshots

== Upgrade Notice ==

A Wordpress Conditonals menu was added so you can easily see which conditionals will apply to your current page.

== What You'll See ==

Check out the screenshots section for pictures of what you get.

1. Queries: With SAVEQUERIES enabled you'll see execution time, the query, and the reference location (ordered by time). Without SAVEQUERIES enabled you'll simply see the number of queries.
2. Execution Time: How long it took to load the page
3. Memory: How much memory was used
4. PHP Includes: Which php theme files and plugin files were included
5. Javascripts: Javascript handles and file sizes for enqueued scripts
6. CSS: CSS handles and file sizes for enqueued scripts
7. Widgets: A list of Active (not necessarily *used*) and Inactive widgets
8. Conditionals: 2 Lists of wordpress conditionals run on the current page. True/False conditionals can be used without parameters. Page Specific will return true for the current page when run with the supplied parameters.