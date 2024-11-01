=== WP JV Custom Email Settings ===
Contributors: janosver
Tags: admin, administration, email, e-mail, newsletter, notification, simple, wordpress, post, automatic, user, multisite
Requires at least: 4.6
Tested up to: 5.3.2
Stable tag: 2.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Notify users about new posts published and customize your e-mail notification settings

== Description ==

By default when you send any notification from your blog (including many of the plugins as well) sender is "WordPress" and the sender e-mail address is <wordpress@yourdomain.com>. I wanted to have personalized sender name and e-mail address that is why I created this plugin. Then I added features to send out e-mail notifications about newly published posts to users who are interested either automatically (on publish) or manually.

This plugin will enable you to

* Replace default <wordpress@yourdomain.com> to any e-mail address

* Replace default e-mail from "WordPress" name to anything you want

* Send e-mail notifications automatically/manually to all registered users about new public posts

* Easily customize notification e-mail subject and content templates

* Re-send e-mail notifications manually as well

* Send notifications about password protected posts as well (password will NOT be included in notification e-mail)

* If you have [WP JV Post Reading Groups plugin](https://wordpress.org/plugins/wp-jv-post-reading-groups/) installed then entitled users can receive notifications about new private posts as well

* Users can opt-out if they don't want to receive e-mails (they can choose to get all/nothing)

* Bulk subscribe/unsubscribe users to/from e-mail notifications (go to Users->All Users and see bulk actions)

* Maintain e-mail log about sent e-mail notifications

Translations

* Hungarian - Janos Ver (last updated for plugin v2.3.1)

* Serbian - Andrijana Nikolic (last updated for plugin v2.2)

* German - Matthias Siebler (last updated for plugin v2.3.1)

== Installation ==

1. Download wp-jv-custom-email-settings.zip
2. Extract to `/wp-content/plugins/wp-jv-custom-email-settings` directory
3. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Where can I define new "Email From" name and from "Email Address"? =

Go to Settings -> General -> "WP JV Custom Email Settings" section.

= How this works? What is the difference between Auto/Manual notification mode? =
In Settings -> Writing -> "WP JV Custom Email Settings - Notifications" section you can select to send notifications automatically or manually. If it is set to Auto whenever you publish a post notification e-mails will be sent out automatically for users with access to the post and opted to receive such notifications. In case of Manual you will be provided a "Send/Re-send notification email(s)" button to notify your readers.

= I'm not getting any notification e-mails, what is wrong? =
In order to receive notification e-mails users have to go to their profile and check “Notify me by e-mail when a new post is published” checkbox in WP JV Custom Email Settings section (or an admin has to do it for them). Further more user has to have access to the post as well, but this applies to private posts only (see FAQ of [WP JV Post Reading Groups plugin](https://wordpress.org/plugins/wp-jv-post-reading-groups/faq/) for more details).

= What kind of tags I can use and for what? =
You can customize notification e-mail template (both subject and content) In the content you can use any standard html tags as well on top of the following ones:
%title% means title of the post
%permalink% means URL of the post
%title_with_permalink% means URL with title of the post
%author_name% means the name of the post author
%excerpt% means excerpt of the post
%words_n% means the first n (must be an integer number) number of word(s) extracted from the post
%recipient_name% means display name of the user who receives the e-mail

= Where are the logs? =
Log of notifications is available at Posts -> JV CES Email Log, where you can view which users were notified about which post and if e-mail sending was successful or not (please note that bounce messages are not processed).

= I've multisite. Does this plugin works for me as well? =
Yes, it does, but in that case each site will have its own log in Posts -> JV CES Email Log.

== Screenshots ==

1. Settings -> General -> "WP JV Custom Email Settings"
2. Settings -> Writing -> "WP JV Custom Email Settings - Notifications"
3. User profile
4. Posts-> JV CES Email Log

== Changelog ==

= 2.6 =
Release date: October 5, 2016

* When deleting a post related e-mail log entries will be deleted as well

= 2.5 =
Release date: December 14, 2015

* Fix a compatibility issue with WP 4.4 when it was not possible to view log about sent e-mail notifications

= 2.4 =
Release date: December 12, 2015

* Improved spam score ( make it less likely these e-mails end up in spam folder) by fixing e-mail formatting issues - thanks to Neil James

= 2.3.1 =
Release date: October 18, 2015

* Performance improvement by loading javascript only on admin pages
* German translation by Matthias Siebler added

= 2.3 =
Release date: July 26, 2015

* Performance improvement by using minified js code
* Bulk subscribe/unsubscribe users to/from e-mail notifications (go to Users->All Users and see the new bulk actions)
* Hungarian translation updated

= 2.2 =
Release date: April 25, 2015

* Serbian translation by Andrijana Nikolic added

= 2.1 =
Release date: April 19, 2015

* Other small fixes to improve compatibility with other plugins
* Hungarian translation added

= 2.0 =
Release date: January 30, 2015

New features added:

* Send e-mail notifications automatically/manually to all registered users about new public posts

* Easily customize notification e-mail subject and content templates

* Re-send e-mail notifications manually as well

* Send notifications about password protected posts as well (password will NOT be included in notification e-mail)

* If you have [WP JV Post Reading Groups plugin](https://wordpress.org/plugins/wp-jv-post-reading-groups/) installed then entitled users can receive notifications about new private posts as well

* Users can opt-out if they don't want to receive e-mails (they can choose to get all/nothing)

* Maintain e-mail log about sent e-mail notifications

= 1.4 =
Release date: August 19, 2014

* Previous release caused another saving issue which is fixed now

= 1.3 =
Release date: August 19, 2014

* Fixed issue with saving options

= 1.2 =
Release date: August 15, 2014

* Code refactoring
* Minor bugfixes

= 1.1 =
Release date: August 14, 2014

* Added Contact Form 7 compatibility

= 1.0 =
Release date: August 14, 2014

* Initial release.

== Upgrade Notice ==

= 1.0 =
Release date: August 14, 2014

* Initial release.

= 1.1 =
Release date: August 14, 2014

* Added Contact Form 7 compatibility

= 1.2 =
Release date: August 15, 2014

* Minor bugfixes

= 1.3 =
Release date: August 19, 2014

* Fixed issue with saving options

= 1.4 =
Release date: August 19, 2014

* Previous release caused another saving issue which is fixed now

= 2.0 =
Release date: January 30, 2015

New features added:

* Send e-mail notifications automatically/manually to all registered users about new public posts

* Easily customize notification e-mail subject and content templates

* Re-send e-mail notifications manually as well

* Send notifications about password protected posts as well (password will NOT be included in notification e-mail)

* If you have [WP JV Post Reading Groups plugin](https://wordpress.org/plugins/wp-jv-post-reading-groups/) installed then entitled users can receive notifications about new private posts as well

* Users can opt-out if they don't want to receive e-mails (they can choose to get all/nothing)

* Maintain e-mail log about sent e-mail notifications

= 2.1 =
Release date: April 19, 2015

* Other small fixes to improve compatibility with other plugins
* Hungarian translation added

= 2.2 =
Release date: April 25, 2015

* Serbian translation by Andrijana Nikolic added

= 2.3 =
Release date: July 26, 2015

* Performance improvement by using minified js code
* Bulk subscribe/unsubscribe users to/from e-mail notifications (go to Users->All Users and see the new bulk actions)
* Hungarian translation updated

= 2.3.1 =
Release date: October 18, 2015

* Performance improvement by loading javascript only on admin pages
* German translation by Matthias Siebler added

= 2.4 =
Release date: December 12, 2015

* Improved spam score ( make it less likely these e-mails end up in spam folder) by fixing e-mail formatting issues - thanks to Neil James

= 2.5 =
Release date: December 14, 2015

* Fix a compatibility issue with WP 4.4 when it was not possible to view log about sent e-mail notifications

= 2.6 =
Release date: October 5, 2016

* When deleting a post related e-mail log entries will be deleted as well
