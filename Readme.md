PhoneGap Toast Plugin
--------------------------

+ Author: munnadroid
+ License: The MIT License
+ Test on PhoneGap/Cordova 2.3.0


Installation Instruction
--------------------------

1. Copy **ToastPlugin.java** to your src folder in package **org.apache.cordova.plugin**
2. Edit res\xml\plugins.xml, add `<plugin name="ToastPlugin" value="org.apache.cordova.plugin.ToastPlugin"/>` into `<plugins> </plugins>`
3. Add **<script src="toast.js"></script>** in your html file.

How To Use ?
---------------

 1. Normal Use
	window.plugins.Toast.show( Message, Duration, SuccessCallback, FailureCallback);

 2. Use Toast.longshow
	Toast.longshow( Message, SuccessCallback, FailureCallback);

 3. Use Toast.longshow
	Toast.shortshow( Message, SuccessCallback, FailureCallback);


Example
----------
	Toast.show("Hello Hi, I am Toast and bite me ! :p" , 500);
	Toast.longshow("Hello, I am long Toast");
	Toast.shortshow("Hello, I am short Toast");
