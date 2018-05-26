# Anidea-SmartThings &copy; Graham Johnson (orangebucket)
Assorted SmartThings bits and bobs.

## URL or AutoRemote Switch
This is a device handler implementing a virtual switch that calls URLs for each of the 'on' and 'off' states. The URLs should be specified as full URLs with appropriate encoding. If the 'AutoRemote Key' is defined, the device handler will create URLs in the same format as the AutoRemote Send Message Service and the 'on' and 'off' options should be defined as AutoRemote messages instead.

The 'AutoRemote Key' can be found by going to your 'personal URL' (the URL is shown when you open up the AutoRemote app on Android). If you start typing something in the 'Message' field a URL will appear in a dialog box on the page. This URL is of the form <code>https:<i></i>//autoremotejoaomgcd.appspot.com/sendmessage?key=**&lt;key&gt;**&message ...</code> and <code>**&lt;key&gt;**</code> is the rather long bit that you need to copy into the device preferences.
