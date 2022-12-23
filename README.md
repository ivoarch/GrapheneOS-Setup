## GrapheneOS Setup Tutorial

Official Web - https://grapheneos.org

### Web Install Guide

- Buy a Google Pixel with `cash`
- Turn on phone by holding down power + volume button.
- Enable `OEM Unlocking`
  - Settings > About phone > tap `Build number` 7 times (until you're developer)
  - Settings > System > Developer options > `OEM unlocking` ✅
  - Developer options > `USB debugging` ✅

Complete install Guide : https://grapheneos.org/install/

### 📝 Practices that I personally try to follow in my setup

> - Secure device with strong password.
> - Use separate profiles for apps requiring Google Services.
> - Keep devices up to date to ensure I recieve the latest security patches.
> - Encrypt sensitive data.
> - Do not plug my device into unknown ports.
> - Never leave my device unattended.
> - Check the legitimacy of the application before installation.
>   - verify the name of developers and their actual existence .
>   - reading the description of the application and its permissions.
>   - reading user reviews & privacy guides.
> - Not using apps or services from 🇨🇳, 🇷🇺, 🇮🇳 and others famous who don't respect people's privacy.
> - Trying to replace popular apps and services with open-source and/or offline alternatives (for things like notes, document scanning, tasks, workout tracking, maps, code etc...).
> - Reduce the number of apps .

### 👥 Profiles

On my personal GrapheneOS setup I have several user profiles .

Settings > System > Multiple users ✅ .

- (**Owner** **#**) has nothing installed only Default apps - Password protected ✅
- (**Main** 👤) every day work profile only Privacy Android apps - Biometric (Fingerprint) protected ✅
- (**Google** 🖕) apps requiring Google Services - Biometric (Fingerprint) protected ✅

### ⚙️ Settings

- Settings > Network & internet > Internet > Select your WiFi gear icon > select pen icon > Advanced options > Privacy > Use per-connection randomized MAC (default) ✅
- Settings > Network & internet > Internet > LTE connection from your carrier > ⚙️ Allow 2G ❌
- Settings > Network & internet > Internet > Network preferences > Turn Off Wi-Fi automatically (15 seconds if no network connected)
- Settings > Network & internet > Internet > Network preferences > Notify for public networks ❌
- Settings > Network & internet > Internet > VPN > Mullvad VPN > ⚙️ Always-on VPN ✅
- Settings > Network & internet > Internet > VPN > Mullvad VPN > ⚙️ Block connections without VPN ✅
- Settings > Connected devices > Bluetooth timeout ✅ (15 seconds if no devices connected)
- Settings > Connected devices > Connection preferences > Printing ❌
- Settings > Apps > SEE ALL `X` APPS > Customize everything! ✅
- Settings > Notifications > App settings > Disable ❌ notifications for any apps you do not necessarily need it .
- Settings > Battery > Battery Percentage ✅
- Settings > Sound & vibration > Do Not Disturb > Schedules > Sleeping ✅ use a specified custom time to time start 22:00 end 07:00
- Settings > Sound & vibration > Dial pad tones ❌
- Settings > Sound & vibration > Screen locking sound ❌
- Settings > Sound & vibration > Touch sounds ❌
- Settings > Sound & vibration > Always show icon when in vibration mode ✅
- Settings > Display > Adaptive Brightness ✅
- Settings > Display > Auto-rotate screen ❌
- Settings > Display > Lock Screen > Privacy > Show sensitive content only when unlocked ✅
- Settings > Display > Lock Screen > Wake screen for notifications ❌
- Settings > Display > Lock Screen > Lift to check phone ❌
- Settings > Display > Dark Theme ✅
- Settings > Display > Night Light ✅
  - Don’t use sunset to sunrise (uses device location data) use a specified custom time to time start 22:00 end 07:00
- Settings > Display > Screen saver ❌
- Settings > Security > Fingerprint - Tap Fingerprint + PIN and follow the prompts
- Settings > Security > Screen lock ⚙️ > Lock after screen timeout ✅ (5 seconds)
- Settings > Security > Auto reboot > 24 Hours ✅
- Settings > Security > USB Accessories > Deny new USB peripherals ❌
- Settings > Security > Enable native code debugging ❌
- Settings > Security > PIN scrambling > Scramble PIN ✅
- Settings > Security > Screen lock camera acces ❌
- Settings > Security > More security settings > SIM card lock - Lock SIM card ✅
- Settings > Privacy > Permission manager > Customize Everything! ✅
- Settings > Passwords and accounts > Auto-fill service > Bitwarden ✅
- Settings > System > Language & Input > on screen keyboard > GraphineOS Keyboard > Appearance & Layouts > Theme > Material Dark ✅
- Settings > System > Languages & input > Languages - Add English (UK), Spanish (Spain), Български (Bulgaria)
- Settings > System > Languages & input > On-screen keyboard > Preferences > Auto-capitalisation ❌
- Settings > System > Languages & input > On-screen keyboard > Preferences > Sound on keypress ❌
- Settings > System > Languages & input > On-screen keyboard > Apparience & Layouts > Theme > Material Dark ✅
- Settings > System > Languages & input > On-screen keyboard > Text correction > Auto-correction ❌
- Settings > System > Languages & input > On-screen keyboard > Text correction > Show correction sugguestions ❌
- Settings > System > Languages & input > On-screen keyboard > Text correction > Next-word sugguestions ❌
- Settings > System > Languages & input > Spell checker ❌
- Settings > System > Date & time - Toggle Use locale default ❌ (to allow the 24 hour time format to be used)
- Settings > About Phone > Device Name > Set "generic name"

### 🛍️ App stores

- [Apps](https://github.com/GrapheneOS/Apps) (Default play store of GrapheneOS)
- [F-Droid](https://f-droid.org/) 🌍 - installable catalogue of FOSS (Free and Open Source Software) applications for the Android platform.
- Google Play Store in a separate profiles (for my bank’s apps, navigation and other apps that need google services etc...) fuck them 🖕

**Note:**
F-Droid is NOT recommended by [PrivacyGuide](https://www.privacyguides.org/android/#f-droid)! But the other alternatives (Droid-ify, Neo-store, Aurora-store, Obtainium) are not allowed according to my threat model that I try to follow.

#### F-Droid repository I use:

Bitwarden

```
https://mobileapp.bitwarden.com/fdroid/
```

Collabora office

```
https://www.collaboraoffice.com/downloads/fdroid/repo/?fingerprint=573258C84E149B5F4D9299E7434B2B69A8410372921D4AE586BA91EC767892CC
```

Cryptomator

```
https://static.cryptomator.org/android/fdroid/repo?fingerprint=F7C3EC3B0D588D3CB52983E9EB1A7421C93D4339A286398E71D7B651E8D8ECDD
```

Guardian Project

```
https://guardianproject.info/fdroid/repo/
```

NewPipe Upstream

```
https://archive.newpipe.net/fdroid/repo/?fingerprint=E2402C78F9B97C6C89E97DB914A2751FDA1D02FE2039CC0897A462BDB57E7501
```

### 📦 Apps

- **Web Browser**
  - [Vanadium](https://github.com/GrapheneOS/Vanadium) - (Default Browser of GrapheneOS)
- **Camera**
  - [Camera](https://github.com/GrapheneOS/Camera) (Default camera app of GrapheneOS)
- **Photo and video gallery**
  - Gallery (Default gallery app of GrapheneOS)
- **File Manager**
  - [Files](https://github.com/GrapheneOS/Files) - (Default file manager of GrapheneOS)
- **Password Manager & 2FA**
  - [Bitwarden](https://bitwarden.com/) 🇺🇸 `US`
- **Email Service/Client/Contacts/Calendar**
  - [Tutanota](https://tutanota.com/) 🇩🇪 `EU` 🌱
  - [K-Mail](https://k9mail.app) 🇺🇸 `US`
- **Anti-spam email protection**
  - [AnonAddy](https://anonaddy.com) 🇬🇧 `UK` 🌱 / android app 🇳🇱
- **Encrypted E2EE cloud storage**
  - [Filen](https://filen.io/) 🇩🇪 `EU` 
- **Notes**
  - [Quillpad](https://github.com/quillpad/quillpad)
- **YouTube frontend**
  - [NewPipe](https://f-droid.org/en/packages/org.schabi.newpipe/) 🌍
- **Social Media**
  - [Infinity for Reddit](https://github.com/Docile-Alligator/Infinity-For-Reddit) 🌍
- **Video Player/Music player**
  - [VLC Media Player](https://f-droid.org/en/packages/org.videolan.vlc/) 🇫🇷 `EU`
- **Secure Messaging**
  - [Threema](https://threema.ch/en) 🇨🇭 `EU`
- **VPN**
  - [Mullvad VPN](https://f-droid.org/en/packages/net.mullvad.mullvadvpn/) 🇸🇪 `EU`
- **Private Browsing**
  - [Tor browser](https://www.torproject.org/download/#android) 🇺🇸 `US`
- **File Encryption**
  - [Cryptomator](https://cryptomator.org/downloads/) 🇩🇪 `EU`
  -  [Droid-Fs](https://forge.chapril.org/hardcoresushi/DroidFS) 🇫🇷 `EU` 
  -  [OpenKeychain](https://www.openkeychain.org) 🇩🇪 `EU`
- **Rss/Feed reader**
  - [Feeder](https://f-droid.org/en/packages/com.nononsenseapps.feeder/)
- **Terminal emulator**
  - text here
- **Office Suite**
  - [Collabora Office](https://www.collaboraoffice.com/solutions/collabora-office-android-ios/) 🇬🇧 `UK`
- **PDF Reader**
  - [PdfViewer](https://github.com/GrapheneOS/PdfViewer) (Default pdf reader of GrapheneOS)
- **Hardware & System information**
  - [Cpu-info](https://github.com/kamgurgul/cpu-info)
- **Translator**
  - [Lingva](https://lingva.ml/) 🇪🇸 `EU`
- **Shoping**
  - https://digitalgoods.proxysto.re/ 🇩🇪 - ([onion](http://digitazyyxyihwwzudp5syxxyn3qhcd63wqcha2dxpfqiyydmrgdiaad.onion/)) - Buy coupons for privacy-friendly services with Monero or Bitcoin...
  - https://shop.proxysto.re/ 🇩🇪 - Get hardware, books, privacy gadgets and physical voucher cards for Mullvad VPN.

**To Be Continued...**

## ⚙️ App Preferences

**Vanadium**

- Settings
  - Search engine - Add [Mojeek](https://www.mojeek.com) 🇬🇧 🌱 as a search engine in Vanadium .
- Passwords
  - Save Passwords ❌
  - Auto Sign-in ❌
- Payment methods
  - Save and fill paymend methods ❌
- Addresses and more
  - Save and fill addresses ❌
- Privacy and security
  - Auto-complete searches and URLs ❌
  - Acces paymend methods ❌
  - Close tabs on exit ✅
  - Open external links in incognito ✅
- Notifications
  - All Vanadium notifications ❌
- Homepage
  - On ✅ (https://www.mojeek.com/?theme=dark&autocomp=0&hp=minimal)
- Downloads
  - Ask where to save files ✅

**Mullvad**

- Preferences
  - Auto-connect ✅
  - Local Network sharing ✅
- Adenced
  - Custom DNS ✅ "Set to block everything 100.64.0.31 (ad trackers, malware, adult content, gambling websites ) more - information here - https://github.com/mullvad/dns-blocklists .

**To Be Continued...**

## The GrapheneOS home screen after setup

<img src="https://raw.githubusercontent.com/ivoarch/GrapheneOS-Setup/844769a9a84724905fa4d1c524c88ef334e13783/Screenshot_20221222-184657.png" width="250" height="500" />

> Screenshot of my phone as of 18-12-2022

### Accessories

- [Webcam cover](https://shop.nitrokey.com/shop/product/nk-cov-webcam-cover-104?page=2)
- [Upscreen privacy screen](https://shop.nitrokey.com/shop/product/privacy-screen-for-nitrophone-2-pro-257)
- [Pixel 6 pro protective case](https://shop.nitrokey.com/shop/product/protective-cover-for-nitrophone-2-pro-233?page=2)


### Additional Resources

GOS Official channel

- https://grapheneos.org/articles
- https://discuss.grapheneos.org

Credits

- https://github.com/Scrut1ny/GrapheneOS-Setup
- https://www.devilreef.net/securing-a-personal-android-phone/
- https://redandblack.io/blog/2020/how-to-set-up-grapheneos/
- https://craignuzzo.tech/grapheneos/
