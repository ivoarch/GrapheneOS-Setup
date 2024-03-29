# GrapheneOS-Setup Guide✍🏻

### 📝 Complete install Guide

- https://grapheneos.org/install/

### 📝 Practices that I personally try to follow in my setup

> - Secure device with strong password.
> - Keep devices up to date to ensure I recieve the latest security patches.
> - Encrypt sensitive data.
> - Do not plug my device into unknown ports.
> - Never leave my device unattended.
> - Check the legitimacy of the application before installation.
>   - verify the name of developers and their actual existence .
>   - reading the description of the application and its permissions.
>   - reading user reviews & privacy guides.
> - Reduce the number of apps .

### 👥 Profiles

- (**Owner** **#**)
- Password protected ✅
- Google Services ✅
- Push Services ✅

#### Enable "Push services"

You need to install all three apps: Google Services Framework, Google Play Services, and Google Play from GrapheneOS Apps Store .

**Important** install them before other apps (Proton Mail, Signal etc...) so notifications are "registered" correctly.

### ⚙️ Settings

#### Network & Internet
- Select your WiFi gear icon > select pen icon > Advanced options > Privacy > Use per-connection randomized MAC (default) ✅
- Internet > LTE connection from your carrier > ⚙️ Allow 2G ❌
- Internet > Network preferences > Turn Off Wi-Fi automatically (15 seconds if no network connected)
- Internet > Network preferences > Notify for public networks ❌
- Internet > VPN > Proton VPN > ⚙️ Always-on VPN ✅
- Internet > VPN > Proton VPN > ⚙️ Block connections without VPN ✅

#### Connected devices
- Bluetooth timeout ✅ (15 seconds if no devices connected)
- Connection preferences > Printing ❌

#### Apps
- Apps > SEE ALL `X` APPS > Customize everything! ✅

#### Notifications
- App settings > Disable ❌ notifications for any apps you do not necessarily need it .
- Notification History
Disable ❌
- Notifications on lock screen > Disable ❌

#### Battery
- Battery Percentage ✅

#### Sound & vibration
- Do Not Disturb > Schedules > Sleeping ✅ use a specified custom time to time start 22:00 end 07:00
- Dial pad tones ❌
- Screen locking sound ❌
- Charging sounds and vibration ❌
- Touch sounds ❌
- Always show icon when in vibration mode ✅

#### Display
- Adaptive Brightness ✅
- Auto-rotate screen ❌
- Lock Screen > Privacy > Show sensitive content only when unlocked ✅
- Lock Screen > Wake screen for notifications ❌
- Lock Screen > Lift to check phone ❌
- Dark Theme ✅
- Night Light ✅
  - Don’t use sunset to sunrise (uses device location data) use a specified custom time to time start 22:00 end 07:00
- Screen saver ❌

#### Wallpaper and Style

- Lock screen > select Monochrome theme
- Home screen > delect Monochrome theme
- Home screen > Themed icons ✅

#### Security
- Fingerprint - Tap Fingerprint + PIN and follow the prompts
- Screen lock ⚙️ > Lock after screen timeout ✅ (5 seconds)
- Auto reboot > 18 Hours ✅
- USB Accessories > Allow new USB peripherals when unlocked ✅
- Enable native code debugging ❌
- USB-C port > Charging-only (see https://discuss.grapheneos.org/d/11178-grapheneos-version-2024022800-released/12 )
- PIN scrambling > Scramble PIN ✅
- Screen lock camera acces ❌
- More security settings > SIM card lock - Lock SIM card ✅

#### Location
- Use location ❌

#### Safety & emergency
- Wireless emergency alerts - toogle ❌ for operator and presidential

#### Privacy
- Permission manager > Customize Everything! ✅

#### Passwords and accounds
- Passwords, passkeys and date services > Proton Pass ✅

#### System
- Language & Input > on screen keyboard > GraphineOS Keyboard > Appearance & Layouts > Theme > Material Dark ✅
- Languages & input > Languages - Add English (UK), Spanish (Spain), Български (Bulgaria)
- Languages & input > On-screen keyboard > Preferences > Auto-capitalisation ❌
- Languages & input > On-screen keyboard > Preferences > Sound on keypress ❌
- Languages & input > On-screen keyboard > Apparience & Layouts > Theme > Material Dark ✅
- Languages & input > On-screen keyboard > Text correction > Auto-correction ❌
- Languages & input > On-screen keyboard > Text correction > Show correction sugguestions ❌
- Languages & input > On-screen keyboard > Text correction > Next-word sugguestions ❌
- Languages & input > Spell checker ❌
- Gestures > Quickly open camera ❌
- Gestures > System navigation > 3-button navigation ✅
- Gestures > System navigation > 3-button navigation ⚙️ Hold home for Assistant ❌
- Gestures > Tab to check phone ❌
- Gestures > Lift to check phone ❌
- Date & time - Toggle Use locale default ❌ (to allow the 24 hour time format to be used)

#### About Phone
- Device Name > Set "generic name"

### 🛍️ App stores

- [Apps](Default play store of GrapheneOS)
- [F-Droid](https://f-droid.org/) 🌍 - installable catalogue of FOSS (Free and Open Source Software) applications for the Android platform.
- Google Play Store

**Note:**
F-Droid is NOT recommended by [PrivacyGuide](https://www.privacyguides.org/android/#f-droid)!

#### F-Droid repository I use:

Collabora office

```
https://www.collaboraoffice.com/downloads/fdroid/repo/?fingerprint=573258C84E149B5F4D9299E7434B2B69A8410372921D4AE586BA91EC767892CC
```


Guardian Project

```
https://guardianproject.info/fdroid/repo/
```

NewPipe Upstream

```
https://archive.newpipe.net/fdroid/repo/?fingerprint=E2402C78F9B97C6C89E97DB914A2751FDA1D02FE2039CC0897A462BDB57E7501
```

IzzyOnDroid

```
https://apt.izzysoft.de/fdroid/repo?fingerprint=3BF0D6ABFEAE2F401707B6D966BE743BF0EEE49C2561B9BA39073711F628937A
```

### 📦 Apps

- **Web Browser**
  - Default Browser of GrapheneOS
- **Camera**
  - Default camera app of GrapheneOS
- **Photo and video gallery**
  - Default gallery app of GrapheneOS
- **File Manager**
  - Default file manager of GrapheneOS
- **Password Manager**
  - [Proton Pass](https://proton.me/pass) 🇨🇭 `EU`
- **2FA Authenticator App**
  - [Aegis](https://getaegis.app/) 🌍
  - [Proton Pass](https://proton.me/pass) 🇨🇭 `EU`
- **Email Service/Client/Contacts/Calendar**
  - [Proton, Proton Mail, Proton Calendar](https://proton.me) 🇨🇭 `EU`
  - [K-Mail](https://k9mail.app) 🇺🇸 `US`
- **Anti-spam email protection**
  - [Simple Login](https://simplelogin.io/) 🇫🇷 🇨🇭 `EU`
- **Encrypted E2EE cloud storage**
  - [Proton Drive](https://proton.me/drive) 🇨🇭 `EU` 
- **Notes**
  - [Notesnook](https://notesnook.com) 🇵🇰 `Pakistan`
- **Private Photo cloud backup**
  - [Ente](https://ente.io/) 
  - [Proton Drive](https://proton.me/drive) 🇨🇭 `EU`
- **YouTube frontend**
  - [NewPipe](https://f-droid.org/en/packages/org.schabi.newpipe/) 🌍
- **Video Player/Music player**
  - [VLC Media Player](https://f-droid.org/en/packages/org.videolan.vlc/) 🇫🇷 `EU`
- **Secure Messaging**
  - [Signal](https://signal.org/en/) 🇺🇸 `US`
- **VPN**
  - [Proton VPN](https://protonvpn.com/) 🇨🇭 `EU`
- **File Encryption**
  - [OpenKeychain](https://www.openkeychain.org) 🇩🇪 `EU`
- **Rss/Feed reader**
  - [Feeder](https://f-droid.org/en/packages/com.nononsenseapps.feeder/)
- **Editor**
  - [Acode](https://acode.app/)
- **Office Suite**
  - [Collabora Office](https://www.collaboraoffice.com/solutions/collabora-office-android-ios/) 🇬🇧 `UK`
- **PDF Reader**
  - Default pdf reader of GrapheneOS)
- **Shoping**
  - https://digitalgoods.proxysto.re/ 🇩🇪 - ([onion](http://digitazyyxyihwwzudp5syxxyn3qhcd63wqcha2dxpfqiyydmrgdiaad.onion/)) - Buy coupons for privacy-friendly services with Monero or Bitcoin...
  - https://shop.proxysto.re/ 🇩🇪 - Get hardware, books, privacy gadgets and physical voucher cards for Mullvad VPN.
  - https://shopinbit.com/ 🇲🇨 - Europes biggest Bitcoin Store, with over 300,000 products.


### ⚙️ App Preferences

**Camera**

- Settings menu
  - General
  - Gyroscope suggestion ✅ 
  - Camera sounds ❌

**Vanadium**

- Settings
  - Search engine - Add [StartPage](https://support.startpage.com/hc/en-us/articles/8623502498964-Make-Startpage-the-default-search-engine-in-Chrome-Android-) 🇳🇱
as a default search engine in Vanadium .
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
  - ❌
- Downloads
  - Ask where to save files ✅
- Enable Passkey
  - type in the address bar: **chrome://flags** then search PASSKEYS , Confirm this by tapping on Enabled for **Google Password Manager and 3rd party passkeys** (https://proton.me/support/pass-use-passkeys)

### The GrapheneOS home screen after setup

<img src="https://nothing" width="250" height="550" />

> Screenshot of my phone as of 08-03-2023

### Accessories

TODO
- [X] [Webcam cover](https://shop.nitrokey.com/shop/product/nk-cov-webcam-cover-104?page=2)
- [ ] [Upscreen privacy screen](https://shop.nitrokey.com/shop/product/privacy-screen-for-nitrophone-2-pro-257)
- [ ] [Pixel 6 pro protective case](https://shop.nitrokey.com/shop/product/protective-cover-for-nitrophone-2-pro-233?page=2)
- [X] [A Hardware Security Key - Yubikey](https://www.yubico.com/is/store/) 
> **Note!** To work is needed Sandboxed Google Play to be installed , how to setup here https://discuss.grapheneos.org/ .
- [ ] [Output Faraday Folio Wallet](https://slnt.com/collections/faraday-phone-sleeves/products/faraday-folio-wallet) or [Faraday Sleeves for Phones](https://slnt.com/collections/faraday-phone-sleeves/products/faraday-cage-sleeves-for-phones?variant=18335583010913)

### Additional Resources

GOS Official channel

- https://grapheneos.org
- https://grapheneos.org/articles
- https://discuss.grapheneos.org
