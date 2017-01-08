---
layout: post
title:  "Welcome to menilv page!"
date:   2016-12-30 16:10:23 +0100
categories: jekyll update
---

As of Marshmallow 6.0 (API 23), Android has introduced runtime permissions model which aditional developers' attention when working with different permission within the application. They are diversified in two sets: 'Normal Permissions' and 'Dangerous Permissions'. Normal Permissions behave the same why as pre Marshmallow not requiring any user input when using them, but the Dangerous Permissions are on the other a different story.

Full list of permissions by typs:

Normal Permissions (android.permission prefix)		|Dangerous Permissions (android.permission prefix)					||
			 										|Permission Group(-group prefix)	|Permissions 					|
:--------------------------------------------------:| :--------------------------------:| -----------------------------:|
ACCESS_LOCATION_EXTRA_COMMANDS 						| group.CALENDAR 					|READ_CALENDAR|
ACCESS_NETWORK_STATE 								| 									|WRITE_CALENDAR|

ACCESS_NOTIFICATION_POLICY 							| group.CAMERA 						|CAMERA|

ACCESS_WIFI_STATE 									| group.CONTACTS 					|READ_CONTACTS|
ACCESS_WIMAX_STATE 									| 									|WRITE_CONTACTS|
BLUETOOTH 											| 									|GET_ACCOUNTS|

BLUETOOTH_ADMIN 									| group.LOCATION 					|ACCESS_FINE_LOCATION|
BROADCAST_STICKY 									| 	 								|ACCESS_COARSE_LOCATION|

CHANGE_NETWORK_STATE 								| group.MICROPHONE 					|RECORD_AUDIO|

CHANGE_WIFI_MULTICAST_STATE 						| group.PHONE 						|READ_PHONE_STATE|
CHANGE_WIFI_STATE 									| 									|CALL_PHONE|
CHANGE_WIMAX_STATE 									| 									|READ_CALL_LOG|
DISABLE_KEYGUARD 									| 									|WRITE_CALL_LOG|
EXPAND_STATUS_BAR 									|									|*ADD_VOICEMAIL|
FLASHLIGHT 											| 									|USE_SIP|
GET_ACCOUNTS 										| 									|PROCESS_OUTGOING_CALLS|

GET_PACKAGE_SIZE 									| group.SENSORS 					|BODY_SENSORS|

INTERNET 											| group.SMS 						|SEND_SMS|
KILL_BACKGROUND_PROCESSES 							| 									|RECEIVE_SMS|
MODIFY_AUDIO_SETTINGS 								| 									|READ_SMS|
NFC 												| 									|RECEIVE_WAP_PUSH|
READ_SYNC_SETTINGS 									| 									|RECEIVE_MMS|
READ_SYNC_STATS 									| 									|READ_CALL_BROADCASTS|

RECEIVE_BOOT_COMPLETED 								| group.STORAGE 					|READ_EXTERNAL_STORAGE|
REORDER_TASKS 										| 									|WRITE_EXTERNAL_STORAGE|
REQUEST_INSTALL_PACKAGES 							| 
SET_TIME_ZONE 										| 
SET_WALLPAPER 										| 
SET_WALLPAPER_HINTS 								| 
SUBSCRIBED_FEEDS_READ 								| 
TRANSMIT_IR 										| 
USE_FINGERPRINT 									| 
VIBRATE 											| 
WAKE_LOCK 											| 
WRITE_SYNC_SETTINGS 								| 
**SET_ALARM 										| 
***INSTALL_SHORTCUT 								| 
***UNINSTALL_SHORTCUT 								| 

*prefix: com.android.voicemail.permission.
**prefix: com.android.alarm.permission.
***prefix: com.android.launcher.permission.

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
