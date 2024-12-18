# GrapheneOS-Setup Guide✍🏻

### 📝 Complete install Guide

- https://grapheneos.org/install/

### 📖 Practices that I personally try to follow in my setup

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

You need to install all three apps: **Google Services Framework, Google Play Services, and Google Play** from GrapheneOS Apps Store .

> 📢 **Important** install them before other apps (Proton Mail, Signal etc...) so notifications are "registered" correctly.

### ⚙️ Settings

#### Network & Internet
- LTE connection from your carrier ➔ ⚙️ Allow 2G ❌
- Network preferences ➔ Notify for public networks ❌
- eSIM support ✅ *(eSIM management no longer requires sandboxed Google Play  https://grapheneos.org/releases#2024012600)*
- SIMs ➔ Add SIM "+" Scan QR Code
- VPN ➔ Mullvad VPN ➔ ⚙️ Always-on VPN ✅
- VPN > Mullvad VPN ➔ ⚙️ Block connections without VPN ✅

#### Connected devices
- Bluetooth timeout ✅ *(15 seconds if no devices connected)*
- Connection preferences ➔ NFC ❌
- Connection preferences ➔ Printing ❌

#### Apps
- Apps ➔ Customize all installed apps! ✅

#### Notifications
- App notifications ➔ Disable ❌ notifications for any apps you do not necessarily need it .
- Notification History
Disable ❌
- Notifications on lock screen ➔ Disable ❌

#### Battery
- Battery Percentage ✅
- Battery share ❌

#### Sound & vibration
- Do Not Disturb ➔ Schedules ➔ Sleeping ✅ use a specified custom time to time start 22:00 end 07:00
- Do not Disturb ➔ People ➔ Calls ➔ Starred Contacts *(family members)*
- Do not Disturb ➔ People ➔ Calls ➔  Allow repeat callers ❌
- Do not Disturb ➔ People ➔ Messages ➔  None ❌
- Media > Hide media player ❌
- Dial pad tones ❌
- Screen locking sound ❌
- Charging sounds and vibration ❌
- Touch sounds ❌
- Always show icon when in vibration mode ✅

#### Display
- Adaptive Brightness ❌
- Screen timeout ➔ After 15 seconds of inactivity
- Auto-rotate screen ❌
- Lock Screen ➔ Privacy ➔ Don't show notificationa at all ✅
- Use device controls ❌ *(without unlocking your phone)*
- Shortcuts ➔ set to None ❌
- Dinamic clock ➔ ❌
- Always show time and info ➔ ❌
- Lock Screen ➔ Wake screen for notifications ❌
- Lock Screen ➔ Lift to check phone ❌
- Lock Screen ➔ Tab to check phone ❌
- Locl Screen ➔ Wake screen for notifications ❌
- Dark Theme ✅
- Night Light ✅
  - *Don’t use sunset to sunrise (uses device location data) use a specified custom time to time start 22:00 end 07:00*
- Screen saver ❌

#### Wallpaper and Style

- Lock screen ➔ select Monochrome theme
- Lock screen ➔ Show notifications on the lock screen ❌
- Home screen ➔ select Monochrome theme
- Home screen ➔ Themed icons ✅

#### Privacy & Security
##### Device unlock
- Fingerprint unlock ➔ Add Fingerprint +
- Fingerprint ➔ Use for screen unlock ❌
- Durres Password ✅
##### Screen lock
- Scramble PIN input layout ➔ ✅
- Enhanced PIN privacy ➔ ✅ *(disabled animations while entering Pin)*
- Lock after screen timeout - 5 sec.
- Power buttin instantly locks ✅
- Allow camera access when locked - ❌
##### Privacy Controls
- Camera access ➔ ❌ *(for apps and services)*
- Microphone access ➔ ❌
- Show clipboard access ✅
- Location access ❌
##### Exploit protection  
- Auto reboot ➔ 18 Hours ✅
- USB-C port ➔ Charging-only when locked
- Turn off Wifi automatically - Set to 1 min.
- Turn off Bluetooth automatically - Set to 1 min.
##### More security and privacy
- Notifications on lock screen ➔ Don't show notifications at all ❌
- Show media on lock screen ❌
- Allow Sensors permissions to apps by default ❌
- Notify about system process crashes ✅
- Lock SIM card ✅

#### Location
- Use location ❌ *(Enable only when is using Maps for navegation)*

#### Safety & emergency
- Wireless emergency alerts - toogle ❌ for operator and presidential

#### Passwords and accounds
- Passwords, passkeys and accounts ➔ Preferred service (Bitwarden).

#### System
- Languages & Input ➔ on screen keyboard ➔ GraphineOS Keyboard ➔ Appearance & Layouts ➔ Theme ➔ Material Dark ✅
- Languages & input ➔ Languages - Add +
- Languages & input ➔ On-screen keyboard ➔ Preferences ➔ Auto-capitalisation ❌
- Languages & input ➔ On-screen keyboard ➔ Preferences ➔ Sound on keypress ❌
- Languages & input ➔ On-screen keyboard ➔ Apparience & Layouts ➔ Theme ➔ Material Dark ✅
- Languages & input ➔ On-screen keyboard ➔ Text correction ➔ Auto-correction ❌
- Languages & input ➔ On-screen keyboard ➔ Text correction ➔ Show correction sugguestions ❌
- Languages & input ➔ On-screen keyboard ➔ Text correction > Next-word sugguestions ❌
- Languages & input ➔ Spell checker ❌
- Gestures ➔ Quickly open camera ❌
- Gestures ➔ System navigation ➔ 3-button navigation ✅
- Gestures ➔ System navigation ➔ 3-button navigation ⚙️ Hold home for Assistant ❌
- Gestures ➔ Tab to check phone ❌
- Gestures ➔ Lift to check phone ❌
- Date & time - Toggle Use locale default ❌ (to allow the 24 hour time format to be used)

#### About Phone
- Device Name ➔ Set "generic name"

### 🛍️ App stores

- App Store (Default play store of GrapheneOS)
- <img src="https://accrescent.app/accrescent.svg" width="15" height="15"/> <a href="https://accrescent.app/">  [Accrescent](https://accrescent.app/) - A novel Android app store focused on security, privacy, and usability.
- <img src="https://github.com/ImranR98/Obtainium/blob/main/assets/graphics/icon_small.png" width="20" height="20"/> <a href="https://obtainium.imranr.dev/">[Obtainium](https://obtainium.imranr.dev/) Get Android app updates straight from the source.
- <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps"> Google Play Store

### 📦 Apps

- **Web Browser**
  - Default Browser
- **Camera**
  - Default Camera
- **Photo and video gallery**
  - Default Gallery
- **File Manager & Cloud File manager**
  - Default file manager
  - [Round Sync](https://github.com/newhinton/Round-Sync) <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **PDF Reader**
  - Default pdf reader
- **Contacts sync**
  - Default contacts app
  - [Tuta](https://tuta.com/) 🇩🇪 🇪🇺 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Password Manager & 2FA Authenticator App**
  - [Bitwarden](https://bitwarden.com/) 🇺🇸 + 🇪🇺 servers <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Email Service/Client/Contacts/Calendar**
  - [Tuta](https://tuta.com/) 🇩🇪 🇪🇺 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
  - [Thunderbird](https://www.thunderbird.net/en-GB/mobile/) 🇺🇸 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Anti-spam email protection**
  - [Addy](https://addy.io/) 🇬🇧 / android app 🇳🇱 <img src="https://github.com/ImranR98/Obtainium/blob/main/assets/graphics/icon_small.png" width="20" height="20"/> <a href="https://obtainium.imranr.dev/">
- **Online storage**
  - [Koofr](https://koofr.eu) 🇸🇮 🇪🇺 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
  - [Koofr Vault](https://vault.koofr.net/) 🇸🇮 🇪🇺 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
  - [Storagebox](https://docs.hetzner.com/storage/storage-box/) 🇩🇪 🇪🇺
- **Notes E2EE**
  - [Joplin](https://joplinapp.org/) (Self-hosted) 🏴󠁧󠁢󠁥󠁮󠁧󠁿 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Private Photo cloud backup**
  - [Ente](https://ente.io/) 🇵🇰 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **YouTube frontend**
  - [NewPipe](https://f-droid.org/en/packages/org.schabi.newpipe/) 🌍 <img src="https://github.com/ImranR98/Obtainium/blob/main/assets/graphics/icon_small.png" width="20" height="20"/> <a href="https://obtainium.imranr.dev/">
- **Video Player/Music player and Streaming**
  - [VLC Media Player](https://f-droid.org/en/packages/org.videolan.vlc/) 🇫🇷 🇪🇺 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
  - [Jellyfin](https://jellyfin.org/) (Self-hosted) <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Messaging**
  - Default messages app of GrapheneOS
  - [WhatsApp](https://www.whatsapp.com) 🇺🇸 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **VPN**
  - [Mullvad](https://mullvad.net/en) 🇸🇪  🇪🇺 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **File Encryption**
  - [OpenKeychain](https://www.openkeychain.org) 🇩🇪 🇪🇺 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
  - [Cryptomator](https://cryptomator.org/) <img src="https://github.com/ImranR98/Obtainium/blob/main/assets/graphics/icon_small.png" width="20" height="20"/> <a href="https://obtainium.imranr.dev/">
- **Rss/Feed reader**
  - [Feeder](https://f-droid.org/en/packages/com.nononsenseapps.feeder/) <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Bookmark Manager**
  - [Linkding](https://linkding.link/) (Self-hosted)
  - [Pinkt](https://github.com/fibelatti/pinboard-kotlin) Unofficial Android client for Linkding <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Private Text, Markdown Editor**
  - [BeauTyXT](https://beautyxt.app/) <img src="https://accrescent.app/accrescent.svg" width="15" height="15"/> <a href="https://accrescent.app/">
- **E2EE Office Suite**
  - [CryptPad](https://cryptpad.org/) 🇫🇷 🇪🇺
- **Navigation Maps**
  - Google Maps <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Social**
  - [Red Reader](https://github.com/QuantumBadger/RedReader) <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Cryptocurrency wallet**
  - [Tangem](https://tangem.com) 🇨🇭 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Hardware & System information**
  - [Cpu-info](https://github.com/kamgurgul/cpu-info) 🇵🇱 🇪🇺 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Translator**
  - [Deepl](https://www.deepl.com/en/translator)  🇩🇪🇪🇺 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Audio Recorder**
  - [Fossify Voice Recorder](https://github.com/FossifyOrg/Voice-Recorder) 🌍 <img src="https://external-content.duckduckgo.com/ip3/play.google.com.ico" width="15" height="15"/> <a href="https://play.google.com/store/apps">
- **Terminal emulator**
  - [Termux](https://github.com/termux/termux-app) <img src="https://github.com/ImranR98/Obtainium/blob/main/assets/graphics/icon_small.png" width="20" height="20"/> <a href="https://obtainium.imranr.dev/">
- **Shoping**
  - https://digitalgoods.proxysto.re/ 🇩🇪 🇪🇺 - ([onion](http://digitazyyxyihwwzudp5syxxyn3qhcd63wqcha2dxpfqiyydmrgdiaad.onion/)) - Buy coupons for privacy-friendly services with Monero or Bitcoin...
  - https://shop.proxysto.re/ 🇩🇪 🇪🇺  - Get hardware, books, privacy gadgets and physical voucher cards for Mullvad VPN.
  - https://shopinbit.com/ 🇲🇨 🇪🇺 - Europes biggest Bitcoin Store, with over 300,000 products.

### My home screen after setup

<img src="https://raw.githubusercontent.com/ivoarch/GrapheneOS-Setup/refs/heads/main/Screenshot_20241130-161553.png" width="250" height="550" />

> 🎴 Screenshot of my phone as of 30-11-24

### Accessories

#### ✔ TODO
- [X] [Webcam cover](https://shop.nitrokey.com/shop/product/nk-cov-webcam-cover-104?page=2)
- [ ] [Upscreen privacy screen](https://shop.nitrokey.com/shop/product/privacy-screen-for-nitrophone-2-pro-257)
- [ ] [Pixel 6 pro protective case](https://shop.nitrokey.com/shop/product/protective-cover-for-nitrophone-2-pro-233?page=2)
- [X] [A Hardware Security Key - Yubikey](https://www.yubico.com/is/store/) 
> 📢 **Important!** To work is needed Sandboxed Google Play to be installed!
- [ ] [Faraday Sleeves for Phones](https://slnt.com/collections/faraday-phone-sleeves/products/faraday-cage-sleeves-for-phones?variant=18335583010913)
- [ ] [Microphone Blocker](https://mic-lock.com/products/mic-lock-usb-c-single-end)

### Additional Resources

GOS Official channel

- https://grapheneos.org
- https://grapheneos.org/articles
- https://discuss.grapheneos.org

GrapheneOS Info app

App through which you can get information about the latest releases of GrapheneOS, links to our community spaces, and details on how to make donations .
