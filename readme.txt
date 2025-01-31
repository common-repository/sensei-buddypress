=== BuddyPress for Sensei ===
Contributors: buddyboss
Donate link: https://www.buddyboss.com/donate/
Tags: buddypress, sensei, woothemes sensei, woothemes, lms, learning management system, learning, courses, courseware, education, social networking, activity, profiles, messaging, friends, groups, forums, notifications, settings, social, community, networks, networking
Requires at least: 3.8
Tested up to: 4.8.2
Stable tag: 1.2.3
Sensei requires at least: 1.9.0
Sensei tested up to: 1.9.12
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

BuddyPress for Sensei integrates the WooThemes Sensei plugin with BuddyPress, so you can add groups, activity, members, and forums to your courses.

== Description ==

Want your students and teachers to interact with each other? **BuddyPress for Sensei** turns your course driven website into a social education platform, creating a seamless bridge between BuddyPress and [Sensei](http://www.woothemes.com/products/sensei/).

= BuddyPress Groups =

Easily tie any Sensei Course to a BuddyPress Group.

* Course participants automatically get added as members to the group
* Group becomes private to course participants and invited members
* Course Lessons become visible at the group
* Course activity gets streamed into the group feed (optional)
* Forum gets added to the group (if bbPress is enabled)
* Course featured image becomes group avatar (if no group avatar has been set)

= BuddyPress Activity =

Activity is one of the core features of BuddyPress, allowing users to interact with each other in real-time. When a course is tied to a group, course actions are optionally added to the group’s activity stream. Group admins can determine which actions to allow in their group, including:

* User starts a course
* User completes a course
* User creates a lesson
* User completes a lesson
* User passes a quiz
* User comments on single lesson page

= BuddyPress Members =

* Your members can view their Active and Completed courses in their profiles.
* Teachers and Students get added as filterable tabs in your Members directory.
* Teachers get a quick link in their profile to the “Add Course” area in the WordPress dashboard.
* All Sensei user links redirect to member profiles (instead of author pages).

= BuddyPress Messages =

Sensei comes with a basic messaging component. If BuddyPress Messaging is enabled, all Sensei messaging is replaced with native BuddyPress messaging, giving users a consistent experience and more powerful messaging capabilities.

= bbPress Forums =

If bbPress is enabled, a forum will be tied to every “course group” automatically, using the same name as the course for the forum title. Group members can then discuss the course in one central location.



== Installation ==

= Before Installing =

1. Make sure you have [WooThemes Sensei](http://www.woothemes.com/products/sensei/) installed and activated.
2. Make sure you have [BuddyPress](https://wordpress.org/plugins/buddypress/) installed and activated.

= From your WordPress dashboard =

1. Visit 'Plugins > Add New'
2. Search for 'BuddyPress for Sensei'
3. Activate BuddyPress for Sensei from your Plugins page.

= From WordPress.org =

1. Download BuddyPress for Sensei.
2. Upload the 'sensei-buddypress' directory to your '/wp-content/plugins/' directory, using your favorite method (ftp, sftp, etc...)
3. Activate BuddyPress for Sensei from your Plugins page.

= Configuration =

1. Enable 'User Groups' at 'Settings > BuddyPress > Components'
2. Enable Forums for Groups by downloading [bbPress](https://wordpress.org/plugins/bbpress/).
3. Visit 'Settings > BP for Sensei' and select your desired options.

== Frequently Asked Questions ==

= Does it come with the Sensei plugin? =

No, it does not. You will need to purchase [WooThemes Sensei](http://www.woothemes.com/products/sensei/) separately.

= Where can I find documentation and tutorials? =

For help setting up and configuring any BuddyBoss plugin please refer to our [tutorials](https://www.buddyboss.com/tutorials/).

= Does this plugin require BuddyPress? =

Yes, it requires [BuddyPress](https://wordpress.org/plugins/buddypress/) to work.

= Will it work with my theme? =

Yes, BuddyPress for Sensei should work with any theme, and will adopt your BuddyPress styling along with CSS from the Sensei plugin. It may require some styling to make it match perfectly, depending on your theme.

= Does it come with a language translation file? =

Yes. Want to translate BuddyPress for Sensei into your own language? We'll be happy to add your translation into the plugin :)

= Where can I request customizations? =

For BuddyPress customizations, submit your request at [BuddyBoss](https://www.buddyboss.com/buddypress-developers/).

== Screenshots ==

1. **Course Group** - Associate Sensei courses with BuddyPress groups.
2. **Members Index** - Display Teachers and Students in separate tabs in your Members directory. 
3. **Course Group Settings** - Add a course to a BuddyPress group and configure its activity actions.
4. **Plugin Settings** - Configure the core plugin options.

== Changelog ==


= 1.2.3 =

* Fix - Fatal error when course group has forum attached
* Fix - Courses are not showing in new groups dropdown on frontend after deleting attached group from the course
* Fix - Fixed warning when BP Group component is disabled. 


= 1.2.2 =
* Updated readme info

= 1.2.1 =
* Fix - When we save a group, it create a new forum
* Tweak - Moved contact teacher button at the bottom of the lesson page

= 1.2.0 =
* Fix - Message link updated
* Fix - Depreciated hooks sensei_complete_quiz fix
* Fix - Notice/Warning while adding course to group fix
* Fix - Random User joined group activity posts fix
* Fix - Course settings fix
* Fix - Add WordPress filter to avoid linking to course in group creation fix 
* Fix - Contact Teacher on quiz page not open buddypress compose message with teacher profiled fix
* Fix - Missing resource files
* Fix - Issue with activity feed for teachers/admins fix
* Fix - Course Images are getting displayed incorrectly fix
* Tweak - added hook for sensei course settings extension
* Fix - Avoid linking to course in group creation
* Fix - Student and Teacher members dir fix
* Fix - Group discussion link broken fix
* Fix - Code cleanup
* Fix - Lesson count zero fix

= 1.1.1 =
* Compatibility up to Sensei 1.9.3
* Fix - Error: Allowed memory size exhausted in members directory
* Fix - Sensei Settings, default featured image placeholder not working
* Fix - Disable the private message functions between learners and teachers
* Fix - Enqueue version number added
* Fix - PHP notices

= 1.1.0 =
* Compatibility with Sensei 1.9.0+
* Correctly turn off course group activities account settings
* Correctly check course-group association
* Ajax member type migration added
* Fix course description disappearing after clicking home tab
* Fix send private message appearing twice on contact lesson teacher page
* Added missing translation strings
* WPMU sites course activity fix

= 1.0.9 =
* Optimised member type conversion query
* Added new course filters
* Added new hook in bp_sensei_create_courses_page
* Fixed no admin inside a newly created group
* Fixed issue to create a forum only if checked
* Added .pot translation file

= 1.0.8 =
* Removed "My Messages"
* Various CSS fixes
* Fixed php error during bulk plugin activation
* Added support for plugin bbPress Topics for Posts

= 1.0.7 =
* Added notice if no lesson found in Course Group
* Fixed a translation string

= 1.0.6 =
* Fixed error on Course Group creation with bbPress disabled

= 1.0.5 =
* Fixed error on Settings page with BuddyPress disabled
* Added notice if Sensei is not installed
* Better CSS compatibility with certain themes
* Removed "Course Discussion" button from Compose Message screen

= 1.0.4 =
* Plugin loads correctly with bbPress disabled

= 1.0.3 =
* Plugin loads correctly with BuddyPress Groups disabled

= 1.0.2 =
* Updated readme

= 1.0.1 =
* Updated readme

= 1.0.0 =
* Initial public release
