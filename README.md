## ViPER4Android Magisk v13 and v14 module

This is a simple V4A module, for no frills setup - you simply grab it, flash it and use it.

No configuration, no additional frameworks, no special requirements, no hacks, no mess. It just works.

Module is based on [original module](https://github.com/Magisk-Modules-Repo/ViPER4Android/) made by [topjohnwu](https://github.com/topjohnwu).

Uses ViPER4Android 2.5.0.4 driver and **includes** [ViPER4Android FX Materialized](https://labs.xda-developers.com/store/app/com.pittvandewitt.viperfx), so you don't have to install anything.

**WARNING**: Since V4A app is systemlessly installed into /system/priv-app (just to stop your ROM from killing V4A too often), this module is possibly incompatible with AppSystemizer and similar modules and may cause undesirable/unpredictable behaviour when installed in conjuction with it. Be aware of this. If you want to use this module without provided app, edit updater-script manually or open an issue here/contact me on XDA to make flashable module without provided app.

## Compatibility
* Android 5.0 - Android 7.1.2
* Magisk v13.1 and later (uses template v4/1400)
* arm, arm64, x86 and x86_64 devices

## Module changelog
* 08.10.2017 - Merged SELinux fixes
	* Thanks to [zertyuiop](https://github.com/zertyuiop/ViPER4Android)
* 06.09.2017 - Update to template version 1400
	* New template patchup
	* Changes in installation logic (removed unecessary unzip)
* 06.08.2017 - Initial commit. Included changes
	* Magisk Module Template v4
	* New update-binary script, based on original one
	* Changes for SELinux policy injection mechanism

## Credits
* [topjohnwu](https://github.com/topjohnwu): [Magisk](https://github.com/topjohnwu/Magisk) and [original Magisk module](https://github.com/Magisk-Modules-Repo/ViPER4Android/)
* [ViPER520 and ZhuHang](http://vipersaudio.com/blog/): ViPER4Android development ([official XDA thread](https://forum.xda-developers.com/showthread.php?t=2191223))
* [pittvandewitt and mr_white_214](https://forum.xda-developers.com/android/themes/app-viper4android-materialized-t3624655): [ViPER4Android Materialized](https://github.com/MrWhite214/v4a_material/) app
