=== Multiple Sidebar Generator ===
Contributors: deepaksharma
Donate link: http://www.dswebsolutions.in/
Tags: sidebars, custom sidebars, dynamic sidebar, simple, widgets, widget sidebar area, multiple sidebars
Requires at least: 3.0

Tested up to: 4.1.1

Stable tag: 4.1


Easily assign custom, widget-enabled sidebars to any page.

== Description ==

Multiple Sidebar Generator Plugin to easily create many custom sidebars. These sidebars can then select in the creation of a post / page / custom post type. We give an order, and select several at once.

Features:

* Add Multi Widget Sidebar.
* Select Different Sidebar in Page/ Post/Costom Posts
* Display in Appearance Options.


= Advanced Usage =

If you want to assign custom sidebars to archive pages or replace multiple sidebars per page, this plugin likely won't be the best solution. However it's flexible enough to handle a wide range of page-based use cases. It can even be configured to work with Custom Post Types by adding a couple lines of code:

`function myprefix_init() {
	add_post_type_support( '{{post_type}}', 'multiple-sidebar-generator' );
}
add_action( 'init', 'myprefix_init' );`


== Installation ==

1. Upload the `multiple-sidebar-generator` folder to the `/wp-content/plugins/` directory

2. Activate the plugin through the 'Plugins' menu in WordPress

3. Create and Select Different Sidebar for Page/ Post/Costom Posts

== Frequently Asked Questions ==

See documentation at http://www.dswebsolutons.in/