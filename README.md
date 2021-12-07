# cordova-plugin-quick-fix-svc

Quick fix for SafaariViewController Plugin for supporting new ChromeTab query on Android 11+

This plugin append

```xml
<queries>
    <intent>
        <action android:name="android.support.customtabs.action.CustomTabsService" />
    </intent>
</queries>
```

into `AndroidManifest.xml` file.

Related to [cordova-plugin-safariviewcontroller#180](https://github.com/EddyVerbruggen/cordova-plugin-safariviewcontroller/pull/180)