===Plugin Name===
Drop-down-taxonomy

Contributors: Niraj M Chauhan
Donate link: http://nirajchauhan.co.cc/
Tags: taxonomy, category, dropdown, custom-taxonomy
Requires at least: 2.9.2
Tested up to: 3.0.3
Stable tag: simplest way to add drop-down-custom-taxonomy box within 2 steps


==Description==
This plugin will help the user to add a drop-down-custom-taxonomy box with the help of small code on his desired location.



= Options =
just place this small code into your theme file and the drop-down box will appear on that page 
code:<?php the_dropdown_taxonomy('category'); ?>
for example, if you want to display it on home page,
then navigate to index.php, the inside that put this code, if you want to display the custom taxonomies, then just replace  category with your custom taxonomy name.


== Screenshots ==



= Support =
If you find that this plugin is has a bug, does not play nicely with other plugins or if you have a suggestion or comment, please <a href="http://nirajchauhan.co.cc/">comment your quesries over here</a>


==Installation==
1. Download
1. Unzip the package and upload to your /wp-content/plugins/ directory.
1. Log into WordPress and navigate to the "Plugins" panel.
1. Activate the plugin.
5. If you want to put the drop-down box on the home-page then goto your index.php file and add this code without quotes
	`<?php the_dropdown_taxonomy('category'); ?>` replace "category" with the name of your custom taxonomy

You can find the example demo on this website http://mbas.in


==Changelog==

= 0.1 =
* Original Release - Works With: wp 3.0.3.