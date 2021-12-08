![version][version-shield]
[![License][license-shield]](LICENSE)

# cordova-plugin-quick-fix-svc

Quick fix for SafaariViewController Plugin for supporting new ChromeTab query on Android 11+.

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

## Install

```bash
cordova plugin add cordova-plugin-quick-fix-svc
```

## Upgrade

```bash
cordova plugin rm cordova-plugin-quick-fix-svc
cordova plugin add cordova-plugin-quick-fix-svc
cordova prepare
```





[license-shield]:https://img.shields.io/github/license/WuglyakBolgoink/cordova-plugin-quick-fix-svc?style=flat
[version-shield]: https://img.shields.io/github/package-json/v/WuglyakBolgoink/cordova-plugin-quick-fix-svc?color=green
