## Simple, Quick View Developer tools, in your admin bar.

**Dev Monitor is a _free_ wordpress plugin for developers that let’s you easily monitor important development information on every page.**

![enter image description here](https://monosnap.com/file/TELsn7O3jEK0xLD0XUAhOuuNZwB46n.png)

![enter image description here](https://monosnap.com/file/BSnwjFgIGpll9C2pcOlHhtZqXfoBYT.png)

 [Original Worpress.org Repository](http://wordpress.org/plugins/dev-monitor)
 
### What You’ll See

1. Queries How many queries, how long they took, what they were, where they were called. The main Queries menu will tell you how many queries were executed, and the percentage of your total execution time they took. 
2. Load Time How long the page took to load 
3. Memory How much memory the page load took 
4. PHP Includes A complete list of included theme and plugin files so you can track down problems. 
5. Javascript Includes A complete list of included javascript handles and their file sizes. 
6. CSS Includes 
A complete list of included CSS handles and their file sizes.
7. Widgets A list of Active and Inactive Widgets. 

### Installation

1. Download the plugin and copy it to your plugin directory
2. Activate the plugin
3. Visit the Settings Page (Settings &gt; Dev Monitor) and select the items you would like to be displayed

### Usage

> Note: To view queries, you need to add to your wp-config.php file. Because SAVEQUERIES can slow down your site considerably, make sure you disable it again when you are done troubleshooting.

    define('SAVEQUERIES',true); // To View Dev Monitor Queries

![enter image description here](https://monosnap.com/file/BSnwjFgIGpll9C2pcOlHhtZqXfoBYT.png)
