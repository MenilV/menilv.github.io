---
layout: post
title:  "Welcome to menilv page!"
date:   2016-12-30 16:10:23 +0100
categories: jekyll update
---

As of Marshmallow 6.0 (API 23), Android has introduced runtime permissions model which aditional developers' attention when working with different permission within the application. They are diversified in two sets: 'Normal Permissions' and 'Dangerous Permissions'. Normal Permissions behave the same why as pre Marshmallow not requiring any user input when using them, but the Dangerous Permissions are on the other a different story.

Full list of permissions by typs:

Normal Permissions									|Dangerous Permissions 												||
			 										|Permission Group					|Permissions 					|
--------------------------------------------------- | :--------------------------------:| -----------------------------:|
android.permission.ACCESS_LOCATION_EXTRA_COMMANDS 	| android.permission-group.CALENDAR |android.permission.READ_CALENDAR|
android.permission.ACCESS_NETWORK_STATE 			| 									|android.permission.WRITE_CALENDAR|
android.permission.ACCESS_NOTIFICATION_POLICY 		| android.permission-group.CAMERA 	|android.permission.CAMERA|
android.permission.ACCESS_WIFI_STATE 				| android.permission-group.CONTACTS |android.permission.READ_CONTACTS|
android.permission.ACCESS_WIMAX_STATE 				| 									|android.permission.WRITE_CONTACTS|
android.permission.BLUETOOTH 						| 									|android.permission.GET_ACCOUNTS|
android.permission.BLUETOOTH_ADMIN 					| android.permission-group.LOCATION |android.permission.ACCESS_FINE_LOCATION|
android.permission.BROADCAST_STICKY 				| 	 								|android.permission.ACCESS_COARSE_LOCATION|
android.permission.CHANGE_NETWORK_STATE 			| android.permission-group.MICROPHONE|android.permission.RECORD_AUDIO|
android.permission.CHANGE_WIFI_MULTICAST_STATE 		| android.permission-group.PHONE 	|android.permission.READ_PHONE_STATE|
android.permission.CHANGE_WIFI_STATE 				| 									|android.permission.CALL_PHONE|
android.permission.CHANGE_WIMAX_STATE 				| 									|android.permission.READ_CALL_LOG|
android.permission.DISABLE_KEYGUARD 				| 									|android.permission.WRITE_CALL_LOG|
android.permission.EXPAND_STATUS_BAR 				| 							|com.android.voicemail.permission.ADD_VOICEMAIL|
android.permission.FLASHLIGHT 						| 									|android.permission.USE_SIP|
android.permission.GET_ACCOUNTS 					| 									|android.permission.PROCESS_OUTGOING_CALLS|
android.permission.GET_PACKAGE_SIZE 				| android.permission-group.SENSORS 	|android.permission.BODY_SENSORS|
android.permission.INTERNET 						| android.permission-group.SMS 		|android.permission.SEND_SMS|
android.permission.KILL_BACKGROUND_PROCESSES 		| 									|android.permission.RECEIVE_SMS|
android.permission.MODIFY_AUDIO_SETTINGS 			| 									|android.permission.READ_SMS|
android.permission.NFC 								| 									|android.permission.RECEIVE_WAP_PUSH|
android.permission.READ_SYNC_SETTINGS 				| 									|android.permission.RECEIVE_MMS|
android.permission.READ_SYNC_STATS 					| 									|android.permission.READ_CALL_BROADCASTS|
android.permission.RECEIVE_BOOT_COMPLETED 			| android.permission-group.STORAGE 	|android.permission.READ_EXTERNAL_STORAGE|
android.permission.REORDER_TASKS 					| 									|android.permission.WRITE_EXTERNAL_STORAGE|
android.permission.REQUEST_INSTALL_PACKAGES 		| 
android.permission.SET_TIME_ZONE 					| 
android.permission.SET_WALLPAPER 					| 
android.permission.SET_WALLPAPER_HINTS 				| 
android.permission.SUBSCRIBED_FEEDS_READ 			| 
android.permission.TRANSMIT_IR 						| 
android.permission.USE_FINGERPRINT 					| 
android.permission.VIBRATE 							| 
android.permission.WAKE_LOCK 						| 
android.permission.WRITE_SYNC_SETTINGS 				| 
com.android.alarm.permission.SET_ALARM 				| 
com.android.launcher.permission.INSTALL_SHORTCUT 	| 
com.android.launcher.permission.UNINSTALL_SHORTCUT 	| 

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
