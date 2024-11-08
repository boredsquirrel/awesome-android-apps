# Awesome Android Apps
Modern, user friendly Apps that I can recommend.

This list should help people with setting up a barebones install of GrapheneOS, LineageOS, etc. or make the switch towards a more privacy friendly phone.

## Disclaimers
Just installing some FOSS (free and open source software) apps on a regular Android phone looking like this, will not make you private, protect your data or the data of your friends and family.

Only removing all of these invasive apps, which mostly includes installing a different Android variant (preferrably GrapheneOS), will make you fully private.

## App Stores
### Google Play
Android traditionally uses the Google Play Store. Other Android vendors like Huawei (which were blocked from using the Playstore) may have their own one.

But the Playstore is really restrictive. It requires developers to give control to Google, and may prevent updating apps, like [it recently happened with Syncthing](https://github.com/syncthing/syncthing-android/issues/2064). It is also pretty invasive, only on GrapheneOS you can use it with some level of privacy, and it always requires a Google Account.

So we want to use other ways to get our apps.

### Obtainium
Use [Obtainium](https://github.com/ImranR98/Obtainium/releases/latest) if you
- trust the developers
- want to get updates as fast as possible

You may not want to use it, if you
- don't know if you can trust developers
- fear that developers may include things in the .apk file that are not in the open source code
- don't want to make a Github account

Obtainium is not an app store. It searches for app updates from various sources and allows you to update the apps easily. But you need to find the apps in different ways.

[Many apps can be found here](https://apps.obtainium.imranr.dev/) and added to Obtainium with a single press.

### F-Droid
You can use this for all your apps, or just for discovering them. F-Droid is a store of only opensource apps. You will want to use it if
- it is important for you that all apps are built from 100% open source code
- you want to be sure that they built on a controlled build system ("reproducible")
- you dont fully trust the app developers

You may not want to use F-Droid if you
- want to get the apps directly from the developers, who you trust
- want the fastest updates

For discovering more Apps, no matter if you use it to *download* them, I recommend using [F-Droid Basic](https://f-droid.org/en/packages/org.fdroid.basic/).

This is the more modern and simpler App for finding and getting updates from the F-Droid "repository" (place where software is stored and served) and it allows to add [many more repositories too](https://forum.f-droid.org/t/known-repositories/721)

### Finding app URLs with F-Droid
To use it only for discovering, while getting the APKs directly from the developers:
- copy the repo URL to Obtainium, in F-Droid basic share the App link, use the `org.app.name` in Obtainium to download the correct appa
- example: [DivestOS Official repo](https://divestos.org/apks/official/fdroid/repo), `us.spotco.fennec_dos`
- Often you can just copy the "source URL" to Obtainium and it will get the official releases

### Getting proprietary apps:
Use a "work profile" or, since Android 15, the "private space" feature, to isolate your "malicious apps". The private space may be more secure, but it is not as comfortable to use as Shelter.

Use [Shelter](https://gitea.angry.im/PeterCxy/Shelter) and setup a work profile, to isolate hostile apps
- clone "Obtainium" and/or "F-Droid Basic" to that work profile
- For getting apps from Google Play:
  - install [AuroraStore](https://apps.obtainium.imranr.dev/) through Obtainium or F-Droid
  - On GrapheneOS, you could also install the Google Play store only in that work profile, it works very well
- For getting apps without Google Play:
  - You can use [APKPure](https://apkpure.com) or [Aptoide](https://aptoide.com) through the browser
  - long press the app's name in the search, copy the link, add it in Obtainium

Backing up APKs
- **Sharing is caring**: use "[APK Kit](https://github.com/ghmxr/apkextractor)" to extract the APKs and upload them to APKPure!
- If an update introduces something you dont like, you can uninstall the app and install the older version

## Recommended Apps
todo
