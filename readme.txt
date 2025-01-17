=== Support Ticket ===
Contributors: websupporter
Tags: support,ticket,contact,crm,helpdesk,help
Requires at least: 4.0
Tested up to: 4.9
Stable tag: 1.1.0
License: GPLv2 or later

The support ticket solution for WordPress

== Description ==
Support Ticket enables you to easily create your own ticket system on your WordPress page. Users can submit tickets, ticket agents can answer tickets, change the ticket status, enter private notes. With a shortcode, you can display the create ticket form on the frontend. Visitors who are not logged in will be registered, or - if the submitted email address exists in the database - asked to login.

[youtube https://www.youtube.com/watch?v=nhYDL84Z4o0]

Administrators can change the ticket agents and configure the plugin. You can define an HTML email template, which will be used for the correspondence with your clients. You can extend the ticket form with textfields and selectboxes of your own.

The plugin comes with dozens of filter and action hooks which enable your developer to extend the plugins functionality, so they fit exactly your needs.

For more information please visit [WP Support Ticket](http://wpsupportticket.com/ "WordPress Support Ticket Plugin").

== Installation ==
After installing the plugin, you will find a new section in your admin menu, called "Tickets". Go to the sub section "Settings" and follow the instructions there. After you have configured the plugin create a new page, where you can use the shortcode [ticket_create] to display the ticket create form.

== Screenshots ==
1. A ticket can be opened on the frontend.
2. Tickets will be ordered in a list on the backend
3. You can edit and answer tickets in the backend
4. Registered users can also create tickets in the backend.
5. The email settings
6. The user settings
7. The ticket settings

== Frequently Asked Questions ==
No questions asked yet :D Lets see.

== Upgrade Notice ==
No notices yet.

== Changelog ==

Version 1.1

* Add Russian translation
* Fixes a bug where tickets got deleted in bulk actions without properly selecting "delete"
* Follow phpcs coding standards.
* Rename text domain to follow WordPress standards.
* `sts_get_statusArr()` and `sts_get_statusClassArr()` are deprecated. Use `sts_get_status_arr()` and `sts_get_status_class_arr()` instead.
* minor bugfix where the pagination of the ticket table was out of sync with the no of tickets acutally shown.
* Moved shortcode templates in new directory (`templates/shortcodes/`) and using a renderer now.
* Fixed typo in assets/-folder
* Move asset-files from admin/-folder

Version 1.0.7

* Option to notify ticket owner on status update
* Notify a new agent, when assigned through the backend
* Link login URL in welcome mail properly
* Link view ticket URL in first agent contact mail
* New filter filters the standard agent who gets assigned to a ticket automatically while ticket creation
* Bugfix for admin-styles & scripts
* Small CSS tweaks


Version 1.0.6

* Ticket overview list is now mobile responsive.

Version 1.0.5

* Set the ticket-create/assign/delete-capabilites of each roles in the settings
* URLs in ticket will be linked automatically
* Shortcode extended: [ticket_create type="table"] will return the form wrappend in a table
* Agents see no. of unread tickets in the menu
* Admins can delete tickets in backend
* Classnames for status will not be translated
* Ticket line breaks won't be removed
* You can edit the senders name and email address for emails send with the ticket system

Version 1.0.0

* Initial release
