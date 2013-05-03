## PhoneGap Toast Plugin

+ Author: Tanin Srivaraphong (Original : munnadroid)
+ License: The MIT License
+ Tested on PhoneGap/Cordova 2.3.0 - 2.6.0


## Installation Instruction

1. Copy **ToastPlugin.java** to your src folder in package **org.apache.cordova.plugin**

1. Edit res\xml\plugins.xml, add `<plugin name="ToastPlugin" value="org.apache.cordova.plugin.ToastPlugin"/>` into `<plugins> </plugins>`

1. Add `<script src="toast.js"></script>` in your html file.

## How To Use

 1. Use Toast.longshow

``` javascript
Toast.longshow(Message [,SuccessCallback, FailureCallback]);
```

 1. Use Toast.shortshow

``` javascript
Toast.shortshow(Message [,SuccessCallback, FailureCallback]);
```

## Contributors

Original work by [@munnadroid](https://github.com/munnadroid).

## Example

``` javascript
Toast.longshow("Hello, I am long Toast");
Toast.shortshow("Hello, I am short Toast");
```
