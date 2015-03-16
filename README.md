# BlankAppBundle

This is a Blank OS X App Bundle that runs Script.sh contained in the Contents/MacOS folder.
I created it just compiling a Blank Cocoa application in XCode and editing Info.plis to suit my needs.

## How to use it ##
Just edit Script.sh inside Contents/MacOS.

## How to add an icon

To add an icon it must be in **ICNS** format. First of all you have to copy it in Contents/Resources, then you have to add a new key to Info.plist this way:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<!-- Lots of stuff

	~~~~~~~~~~
	~~~~~~~
	~~~~~~~~~
	~~~~~~~~~~

	-->
	<!-- And now your icon stuff -->
	<key>CFBundleIconFiles</key>
	<string>MySuperCoolIcon.icns</string>
	<!-- That's all folks! -->
</dict>
</plist>
```

## Questions?
Feel free to ask me!