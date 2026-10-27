# I Wanna Be The Guy: Remastered Tribute Edition (Android)

<img src="sce_sys/icon0.png" width="128" align="right">

Android build of *I Wanna Be The Guy: Remastered*, version 1.6.6.6, on a new GameMaker 8 runtime.
A sideloadable APK for phones and tablets running Android 7.0 or newer (arm64-v8a and armeabi-v7a).

## Download (v1.6.6.6)
- [IWBTGR-TributeEdition-Android.apk](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-android/releases/download/v1.6.6.6/IWBTGR-TributeEdition-Android.apk)
- [SHA256SUMS.txt](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-android/releases/download/v1.6.6.6/SHA256SUMS.txt)

[Latest release](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-android/releases/latest)

## Install
1. Download the APK on your phone.
2. Allow installing unknown apps for the app you open it with (Settings → Apps → Special app access →
   Install unknown apps; on older Android versions, *Unknown sources* in Settings → Security).
3. Open the APK and tap *Install*, or sideload it from a computer with `adb install IWBTGR-TributeEdition-Android.apk`.

If you installed an earlier debug-signed test APK, uninstall it first: this release is signed with a new key, so
Android will not install it over the old one. Later updates use the same key and install over this release.

## What's in it
- Tribute mode, playable as the Tribute Kid
- Boss Rush modes once unlocked, each with its own best time
- File select with a picture of each save, New Game on empty slots
- 16 languages, with some Brazilian Portuguese voice acting
- Landscape and portrait ("GBC style") layouts, auto-rotating or locked in *Options → Dipswitches → Screen*

## Controls
- **Touch (default):** d-pad on the left; **Jump** low on the right and **Shoot** to the left of it and higher.
  Reset, Skip, Pause and Back sit above. In the DS level, touch the game screen itself for its touch-screen controls.
- **Controllers and keyboards:** Bluetooth or USB controllers and physical keyboards work; the touch buttons fade while one is in use.
- **Rebinding:** controls can be remapped in *Options*; *Volume Keys as Buttons* makes Vol+ / Vol- game buttons (assignable).
- Touch controls can be turned off only while a controller or keyboard is connected.

## Dumb ways to play (optional, phone only)
Off by default, in *Options → Dipswitches*, and active only while playing a stage (never in menus):
tilt to walk, flick the phone up to jump, and say "pew" into the mic to shoot.
The mic is only measured for loudness, never recorded.

## Credits
- Michael "Kayin" O'Reilly: *I Wanna Be The Guy*
- Kayin / Cherry Treehouse: *I Wanna Be The Guy: Remastered* (Natsu & Renko, Floogle & renex, Midoru, Koala,
  Roaming97 and everyone in the game's credits)
- shaman: *I Wanna be the Tribute* — the 1.6.6.6 patch and extras
- Emoji graphics: [Twemoji](https://github.com/jdecked/twemoji) by Twitter, Inc and other contributors,
  licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Source
This repository only hosts the releases. The source code is kept in a private repository.
The runtime is GPL-3.0-or-later (`LICENSE`); the games' own content belongs to their authors.
