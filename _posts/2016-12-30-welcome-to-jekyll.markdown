---
layout: post
title:  "Welcome to menilv page!"
date:   2016-12-30 16:10:23 +0100
categories: jekyll update
---

As of Marshmallow 6.0 (API 23), Android has introduced runtime permissions model which aditional developers' attention when working with different permission within the application. They are diversified in two sets: 'Normal Permissions' and 'Dangerous Permissions'. Normal Permissions behave the same why as pre Marshmallow not requiring any user input when using them, but the Dangerous Permissions are on the other a different story.

Full list of permissions by typs:

Normal Permissions									|Dangerous Permissions 				||
Permissions 										|Permission Group					| Permissions|
-------------- | :-----------:
android.permission.ACCESS_LOCATION_EXTRA_COMMANDS 	| android.permission-group.CALENDAR |android.permission.READ_CALENDAR
android.permission.ACCESS_NETWORK_STATE| |android.permission.READ_CALENDAR|
android.permission.ACCESS_NOTIFICATION_POLICY| android.permission-group.|
android.permission.ACCESS_WIFI_STATE| android.permission-group.|
android.permission.ACCESS_WIMAX_STATE| 1|1
android.permission.BLUETOOTH| 1|2
android.permission.BLUETOOTH_ADMIN| 1|2
android.permission.BROADCAST_STICKY| 1|2
android.permission.CHANGE_NETWORK_STATE| 1|2
android.permission.CHANGE_WIFI_MULTICAST_STATE| 1|2
android.permission.CHANGE_WIFI_STATE| 1|2
android.permission.CHANGE_WIMAX_STATE| 1|2
android.permission.DISABLE_KEYGUARD| 1|2
android.permission.EXPAND_STATUS_BAR| 1|2
android.permission.FLASHLIGHT| 1|2
android.permission.GET_ACCOUNTS| 1|2
android.permission.GET_PACKAGE_SIZE| 1|2
android.permission.INTERNET| 1|2
android.permission.KILL_BACKGROUND_PROCESSES| 1|2
android.permission.MODIFY_AUDIO_SETTINGS| 1|2
android.permission.NFC| 1|2
android.permission.READ_SYNC_SETTINGS| 1|2
android.permission.READ_SYNC_STATS| 1|2
android.permission.RECEIVE_BOOT_COMPLETED| 1|2
android.permission.REORDER_TASKS| 1|2
android.permission.REQUEST_INSTALL_PACKAGES| 1|2
android.permission.SET_TIME_ZONE| 1|2
android.permission.SET_WALLPAPER| 1|2
android.permission.SET_WALLPAPER_HINTS| 1|2
android.permission.SUBSCRIBED_FEEDS_READ| 1|2
android.permission.TRANSMIT_IR| 1|2
android.permission.USE_FINGERPRINT| 1|2
android.permission.VIBRATE| 1|2
android.permission.WAKE_LOCK| 1|2
android.permission.WRITE_SYNC_SETTINGS| 1
com.android.alarm.permission.SET_ALARM| 1|2
com.android.launcher.permission.INSTALL_SHORTCUT| 1|2
com.android.launcher.permission.UNINSTALL_SHORTCUT| 1|2

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
