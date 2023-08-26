![image-1313240240](https://github.com/Scrut1ny/GrapheneOS-Guide/assets/53458032/fd537eec-0144-47aa-9e72-4bd65eb3964c)

## 💵 Purchasing
- 📱 Mobile Phone
  - Purchase a new `Google Pixel` with `cash` from a local store and avoid Verizon, as they lock the OEM.

- 📶 Mobile Carrier
  - Buy a pre-paid [Mint Mobile](https://www.mintmobile.com/) (T-Mobile) SIM card with `cash` from a local store.
    - Wire it up to a [privacy.com](https://privacy.com/) card.
      - For $15/month, it provides unlimited* 4G/5G domestic data with relatively little attributable information on the account (e.g., no name, address, SSN, etc.)
  - [Calyx hotspot](https://calyxinstitute.org/membership/internet) for unlimited, unthrottled, anonymous connectivity. 

- 📲 Mobile Accessories (optional)
  - Protective Case/Cover
      - [Google Pixel](https://www.amazon.com/stores/page/1AEDD91F-AFDC-49AA-A7F4-2BF2A6AEBD57)
  - Privacy Screen Protector
      - [Google Pixel](https://www.amazon.com/stores/page/EE20BD00-A914-460E-B3CC-12A13BB945E2/search?terms=Google%20Pixel)


## 🔓 Unlocking the OEM
  1. Remove physical SIM card
  2. Factory reset (Settings > System > Reset options > `Erase all data (factory reset)` ✅
  3. Setup Wi-Fi Connection (Settings > Network & internet > Internet)
  4. Settings > System > Dev > `Allow OEM unlocking` ✅


## ⬇️ Install Google USB Driver
  1. Download: [Link](https://dl.google.com/android/repository/usb_driver_r13-windows.zip)
  2. Unzip "usb_driver_r13-windows.zip"
  3. `WIN + R` enter: `devmgmt.msc`
  4. Portable Devices > Google Pixel
  5. Right click device > `Properties` > `Driver` > `Update Driver` > `Browse my computer for drivers` > `Browse` > Select *unzipped* "usb_driver_r13-windows" file once located.


## ⬇️ Installation
Official Site > [https://grapheneos.org](https://grapheneos.org)
  - Web Install Guide > [Link](https://grapheneos.org/install/web)
  - CLI Install Guide > [Link](https://grapheneos.org/install/cli)


## ⚙️ Settings
#### Network & internet
- Settings > Network & internet > Internet > Carrier Settings ⚙️ > `Allow 2G` ❌
- Settings > Network & internet > Internet > *Select your WiFi* ⚙️ > *select pen icon* > Advanced options > Privacy > `Use per-connection randomized MAC (default)` ✅
- Settings > Network & internet > Private DNS > Private DNS provider hostname: `dns.quad9.net` ✅
- Settings > Network & internet > Internet connectivity checks > `Disabled` ❌
- Settings > Network & internet > Attestation key provisioning > `Enabled (GrapheneOS proxy)` ✅

#### Apps
- Settings > Apps > Default apps (*Set your favorite default apps here*) ✅

#### Battery
- Settings > Battery > `Battery Percentage` ✅

#### Sound & vibration
- Settings > Sound & vibration > `Vibration & haptics` ❌
- Settings > Sound & vibration > `Dial pad tones` ❌
- Settings > Sound & vibration > `Screen locking sound` ❌
- Settings > Sound & vibration > `Charging sounds and vibration` ❌
- Settings > Sound & vibration > `Touch sounds` ❌
- Settings > Sound & vibration > `Always show icon when in vibrate mode` ❌

#### Display
- Settings > Display > `Adaptive Brightness` ✅
- Settings > Display > `Auto-rotate screen` ✅
- Settings > Display > Lock Screen > Privacy > `Show sensitive content only when unlocked` ✅
- Settings > Display > Lock Screen > `Wake screen for notifications` ❌
- Settings > Display > Screen timeout > `1 minute` ✅
- Settings > Display > `Dark Theme` ✅
- Settings > Display > `Increase touch sensitivity` ✅ (If you have screen protector)

#### Security
- Settings > Security > Auto reboot > `12 Hours` ✅
- Settings > Security > `Native code debugging` ❌
- Settings > Security > `Scramble PIN input layout` ✅

#### Privacy
- Settings > Privacy > Permission manager > Customize Everything! ✅
  - Use [exodus-privacy](https://reports.exodus-privacy.eu.org/).

#### System
- Settings > System > Language & Input > on screen keyboard > GraphineOS Keyboard > Appearance & Layouts > Theme > `Material Dark` ✅


## 🛍️ Apps
- FOSS Essential Apps
  - Web Browser
    - [Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/) - Privacy oriented web browser (FF Based)
  - YouTube Alt
    - [NewPipe](https://github.com/TeamNewPipe/NewPipe/releases/latest) - Lightweight YouTube frontend
  - Movie/Show Streaming Alt
    - [CloudStream](https://github.com/recloudstream/cloudstream/releases/latest) - Android app for streaming and downloading media.
  - Music
    - [ViMusic](https://github.com/vfsfitvnm/ViMusic/releases/latest) - An Android application for streaming music from YouTube Music.
  - Photo/Video Gallery
    - [Simple Gallery](https://github.com/SimpleMobileTools/Simple-Gallery/releases/latest) - A premium app for managing and editing your photos, videos, GIFs without ads
  - Notes
    - [Simple Notes](https://github.com/SimpleMobileTools/Simple-Notes/releases/latest) -  A simple textfield for adding quick notes without ads.
  - Secure Messaging
    - [Signal](https://signal.org/android/apk/) - Signal is a messaging app with privacy at its core. It is free and easy to use, with strong end-to-end encryption that keeps your communication completely private.
  - Navigation
    - [OsmAnd](https://github.com/osmandapp/OsmAnd/releases/latest) - Global Mobile Map Viewing & Navigation for Offline and Online OSM Maps
  - Weather
    - [Rain](https://github.com/DarkMooNight/Rain/releases/latest) - Weather app.

- App Stores
  - [F-Droid](https://f-droid.org/) - The app store that respects freedom and privacy
  - [Aurora Store](https://f-droid.org/en/packages/com.aurora.store/) - An open-source alternative to Google Play Store with privacy and modern design

- F-Droid Apps
  - Web Browser
      - [Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/) - Privacy oriented web browser (FF Based)
  - Navigation
      - [Organic Maps](https://f-droid.org/en/packages/app.organicmaps/) - Open-source, community-driven maps for travelers, tourists, cyclists & hikers
      - [OsmAnd~](https://f-droid.org/en/packages/net.osmand.plus/) - Global Mobile Map Viewing & Navigation for Offline and Online OSM Maps
  - Onlne Video, Music, Streaming, Podcasts, etc
      - [NewPipe](https://f-droid.org/en/packages/org.schabi.newpipe/) - Lightweight YouTube frontend
      - [ViMusic](https://f-droid.org/en/packages/it.vfsfitvnm.vimusic/) - Seamlessly stream music from YouTube Music
      - [Transistor](https://f-droid.org/en/packages/org.y20k.transistor/) - Transistor is an app for listening to radio stations over the internet.
      - [AntennaPod](https://f-droid.org/en/packages/de.danoeh.antennapod/) - Easy-to-use, flexible and open-source podcast manager and player
      - [Podverse](https://f-droid.org/en/packages/com.podverse.fdroid/) - Podcast app with clips, video, livestreams, playlists, profiles, and cross-platform
  - Social Media
      - [Fritter](https://f-droid.org/en/packages/com.jonjomckay.fritter/) - A free, open-source Twitter client.
  - Offline Media
      - [VLC Media Player](https://f-droid.org/en/packages/org.videolan.vlc/) - The best video and music player. Fast and “just works”, plays any file
      - [Video Transcoder](https://f-droid.org/en/packages/protect.videoeditor/) - Video transcoding between common formats
      - [Standard Notes](https://f-droid.org/en/packages/com.standardnotes/) - An end-to-end encrypted note-taking app for digitalists and professionals
      - [SimpleTextEditor](https://f-droid.org/en/packages/com.maxistar.textpad/) - Simple Text Editor
  - Messenger (Private, Secure, etc)
      - [Brair](https://f-droid.org/en/packages/org.briarproject.briar.android/) - Secure Messaging, Anywhere
  - VPNs
      - [Mullvad VPN](https://f-droid.org/en/packages/net.mullvad.mullvadvpn/) - Protect your online privacy with a fast, trustworthy, and easy-to-use VPN.
      - [IVPN](https://f-droid.org/en/packages/net.ivpn.client/) - Privacy focused VPN service with WireGuard
      - [Calyx VPN](https://f-droid.org/en/packages/org.calyxinstitute.vpn/) - Free VPN Service offered by The Calyx Institute
      - [ProtonVPN](https://f-droid.org/en/packages/ch.protonvpn.android/) - Free Swiss VPN with advanced security and privacy features.
  - App Container/Isolator, sniffer, etc
      - [NetGuard](https://f-droid.org/en/packages/eu.faircode.netguard/) - A simple way to block access to the internet per application
      - [Insular](https://f-droid.org/en/packages/com.oasisfeng.island.fdroid/) - Isolate your Big Brother apps
      - [PCAPdroid](https://f-droid.org/en/packages/com.emanuelef.remote_capture/) - No-root network monitor and traffic dump tool for Android devices
  - Misc. Apps
      - [dvd](https://f-droid.org/packages/org.yausername.dvd/) - 📀 Download videos from anywhere (YT-DLP)
      - [PrivacyBlur](https://f-droid.org/packages/de.mathema.privacyblur/) - Blur or pixelate faces or sensitive areas in pictures
      - [KeePassDX](https://f-droid.org/en/packages/com.kunzisoft.keepass.libre/) - Secure and open source password manager compatible with KeePass files.
      - [Lemuroid](https://f-droid.org/en/packages/com.swordfish.lemuroid/) - All in one emulator on Android

- Aurora Apps
  - Magic Earth
    - [Google Play Store](https://play.google.com/store/apps/details?id=com.generalmagic.magicearth)
  - Tor Browser
    - [Google Play Store](https://play.google.com/store/apps/details?id=org.torproject.torbrowser)

### Spoofing (You *CANNOT* root GrapheneOS!)
- Spoofing Device Information
  - Install [tutorial](https://www.youtube.com/watch?v=4ZS5QiWB8WI)
  - [Magisk](https://github.com/topjohnwu/Magisk/releases/latest)
  - [Riru](https://github.com/RikkaApps/Riru/releases/latest)
  - [EdXposed](https://github.com/ElderDrivers/EdXposed/releases/latest)
- Spoofing Apps
  - [Android Faker](https://github.com/Xposed-Modules-Repo/com.android1500.androidfaker/releases/latest)
  - [MACsposed](https://github.com/DavidBerdik/MACsposed/releases/latest)

### System is bricked, boot looping, corrupted, or showing critical errors
- Using this [Guide](https://forum.xda-developers.com/t/guide-flashing-a-factory-image-with-fastboot-return-to-stock.1907796/) you should be able to fix your problem. After you have successfully fixed any prior issues, next just install [GrapheneOS](https://grapheneos.org/install/) again.

## Other Awesome Guides
- https://www.devilreef.net/securing-a-personal-android-phone/
- https://redandblack.io/blog/2020/how-to-set-up-grapheneos/
- https://craignuzzo.tech/grapheneos/

## Phone Layout
![image](https://github.com/Scrut1ny/GrapheneOS-Guide/assets/53458032/48b8fe77-1c37-4e1c-afb9-6be1c2d23787)
