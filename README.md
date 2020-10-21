# chromie-links
Cocoa-AppleScript Applet allow open links type 
**chromie://{path_on_filesystem}** for OSX by registering a new CFBundleURLTypes based 
on CFBundleURLSchemes **chromie**


**Build process**

Save app & edit .plist 

```
<key>CFBundleURLTypes</key>
<array>
	<dict>
		<key>CFBundleURLName</key>
		<string>Chromie</string>
		<key>CFBundleURLSchemes</key>
		<array>
			<string>chromie</string>
		</array>
	</dict>
</array>
```


Copy the app in the Applications folder


**Permissions**

Allow access to the app from Preferences>Security>Confidentiality