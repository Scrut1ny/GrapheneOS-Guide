![image-1313240240](https://github.com/Scrut1ny/GrapheneOS-Guide/assets/53458032/fd537eec-0144-47aa-9e72-4bd65eb3964c)

#### I collaborated with Naomi Brockwell [NBTV](https://www.youtube.com/@NaomiBrockwellTV) to craft a YouTube video accompanying this guide. The process involved significant dedication and effort, resulting in the creation of [this video](https://youtu.be/wg00QkcpOOM). Whether you stumbled upon it from the YouTube video, discovered it by chance, or were referred by a friend, your feedback is highly valued. Please don't hesitate to propose any additions or improvements to this guide. Whether it's links, configurations, apps, or any other suggestions, I welcome your input. Your recommendations will be thoroughly reviewed, and I'll consider their integration into this guide.




## 💵 Purchasing

<details>
<summary>Click to expand...</summary>

- 📱 Mobile Phone
  - Purchase a new `Google Pixel` with `cash` from a local store and avoid Verizon, as they lock the OEM.
    - *Ensure the transaction remains anonymous to avoid linking the phone's IMEI to your identity.*

- 📶 Mobile Carrier
  - Buy a pre-paid [Mint Mobile](https://www.mintmobile.com/) (T-Mobile) SIM card with `cash` from a local store.
    - Wire it up to a [privacy.com](https://privacy.com/) card.
      - For $15/month*, it provides unlimited* 4G/5G domestic data with relatively little attributable information on the account (e.g., no name, address, SSN, etc.)
  - [Calyx hotspot](https://calyxinstitute.org/membership/internet) for unlimited, unthrottled, anonymous connectivity. 

- 📳 Configuring Mobile Carrier
  - Use a free public Wi-Fi network far from your home to configure your recently acquired mobile carrier.

- 📲 Mobile Accessories (optional)
  - Protective Case/Cover
      - [Google Pixel](https://www.amazon.com/stores/page/1AEDD91F-AFDC-49AA-A7F4-2BF2A6AEBD57)
  - Privacy Screen Protector
      - [Google Pixel](https://www.amazon.com/stores/page/EE20BD00-A914-460E-B3CC-12A13BB945E2/search?terms=Google%20Pixel)

</details>




## 🔓 Unlocking the OEM

<details>
<summary>Click to expand...</summary>

1. Remove physical SIM card
2. Factory reset (Settings > System > Reset options > `Erase all data (factory reset)` ✅
3. Setup Wi-Fi Connection (Settings > Network & internet > Internet)
4. Settings > System > Dev > `Allow OEM unlocking` ✅

</details>




## ⬇️ Install Google USB Driver

<details>
<summary>Click to expand...</summary>

1. Download: [Link](https://dl.google.com/android/repository/usb_driver_r13-windows.zip)
2. Unzip "usb_driver_r13-windows.zip"
3. `WIN + R` enter: `devmgmt.msc`
4. Portable Devices > Google Pixel
5. Right click device > `Properties` > `Driver` > `Update Driver` > `Browse my computer for drivers` > `Browse` > Select *unzipped* "usb_driver_r13-windows" file once located.

</details>




## ⬇️ Installation

<details>
<summary>Click to expand...</summary>

### Official Site > [https://grapheneos.org](https://grapheneos.org)
- [Web Install Guide](https://grapheneos.org/install/web)
- [CLI Install Guide](https://grapheneos.org/install/cli)

### System is bricked, boot looping, corrupted, or showing critical errors
- [Fix Guide](https://forum.xda-developers.com/t/guide-flashing-a-factory-image-with-fastboot-return-to-stock.1907796/)

</details>




## ⚙️ Settings

<details>
<summary>Click to expand...</summary>

#### Network & internet
* Settings > Network & internet > Internet > Carrier Settings ⚙️ > Preferred network type > `LTE only` ✅ (*if you don't have 5G*)
* Settings > Network & internet > Internet > Carrier Settings ⚙️ > `Allow 2G` ❌ (*if option exists*)
* Settings > Network & internet > Internet > *Select your Wi-Fi* ⚙️ > *select pen icon* > Advanced options > Privacy > `Use per-connection randomized MAC (default)` ✅
* Settings > Network & internet > Private DNS > Private DNS provider hostname: `dns.quad9.net` ✅
* Settings > Network & internet > Internet connectivity checks > `Disabled` ❌
  * **IMPORTANT:** *Make sure to enable again for captive portals used via public Wi-Fi!*

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
- Settings > Security > `Scramble PIN input layout` ✅

#### Privacy
- Settings > Privacy > Permission manager > Customize Everything! ✅
  - Use [exodus-privacy](https://reports.exodus-privacy.eu.org/) to assess if an app has excessive trackers or questionable permissions.

#### System
- Settings > System > Language & Input > on screen keyboard > GraphineOS Keyboard > Appearance & Layouts > Theme > `Material Dark` ✅

</details>




## 🛍️ Apps

<details>
<summary>Click to expand...</summary>

### FOSS Essential Apps
- Web Browser
  - [Mull](https://f-droid.org/packages/us.spotco.fennec_dos/) - Privacy oriented web browser (FF Based)
    - Add-ons
      - [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
      - [Tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
        - User Scripts (JS)
          - [Greasy Fork](https://greasyfork.org/)
            - [Simple YouTube Age Restriction Bypass](https://greasyfork.org/scripts/423851-simple-youtube-age-restriction-bypass)
- YouTube Alt
  - [LibreTube](https://github.com/libre-tube/LibreTube/releases/latest) - An alternative frontend for YouTube, for Android.
  - [NewPipe](https://github.com/TeamNewPipe/NewPipe/releases/latest) - A libre lightweight streaming front-end for Android. 
- Movie/Show Streaming Alt
  - [CloudStream](https://github.com/recloudstream/cloudstream/releases/latest) - Android app for streaming and downloading media.
    - [repos](https://rentry.org/cs3-repos#cloudstream-3-repositories)
- Music
  - [Auxio](https://github.com/OxygenCobalt/Auxio/releases/latest) - A simple, rational music player for Android
  - [InnerTune](https://github.com/z-huang/InnerTune/releases/latest) - A Material 3 YouTube Music client for Android
- Photo/Video Gallery
  - [Fossify Gallery](https://github.com/FossifyOrg/Gallery/releases/latest) - A premium app for managing and editing your photos, videos, GIFs without ads
- Notes
  - [Fossify Notes](https://github.com/FossifyOrg/Notes/releases/latest) - A simple textfield for adding quick notes without ads.
- Secure Messaging
  - [Signal](https://signal.org/android/apk/) - A private messenger for Android. 
  - [Session](https://github.com/oxen-io/session-android/releases/latest) - A private messenger for Android.
- Email Service
  - [Proton Mail](https://github.com/ProtonMail/proton-mail-android/releases/latest)
  - [Tuta](https://f-droid.org/en/packages/de.tutao.tutanota/)
    - [Github Link](https://github.com/tutao/tutanota/releases)
- Navigation
  - [OsmAnd](https://github.com/osmandapp/OsmAnd/releases/latest) - Global Mobile Map Viewing & Navigation for Offline and Online OSM Maps
- Weather
  - [Rain](https://github.com/DarkMooNight/Rain/releases/latest) - Weather app.
- Updates
  - [Obtainium](https://github.com/ImranR98/Obtainium/releases/latest) - Get Android App Updates Directly From the Source. 

### App Stores
- [F-Droid](https://f-droid.org/) - The app store that respects freedom and privacy
- [accrescent](https://github.com/accrescent/accrescent/releases/latest) - A novel Android app store focused on security, privacy, and usability
- [Aurora Store](https://f-droid.org/packages/com.aurora.store/) - An open-source alternative to Google Play Store with privacy and modern design

### F-Droid Apps
- Web Browser
  - [Mull](https://f-droid.org/packages/us.spotco.fennec_dos/) - Privacy oriented web browser (FF Based)
  - [cromite](https://github.com/uazo/cromite/releases/latest) - Cromite a Bromite fork with ad blocking and privacy enhancements; take back your browser! 
- Navigation
  - [Organic Maps](https://f-droid.org/packages/app.organicmaps/) - Open-source, community-driven maps for travelers, tourists, cyclists & hikers
  - [OsmAnd~](https://f-droid.org/packages/net.osmand.plus/) - Global Mobile Map Viewing & Navigation for Offline and Online OSM Maps
- Weather
  - [Rain](https://github.com/DarkMooNight/Rain/releases/latest) - Weather app.
  - [Breezy Weather](https://github.com/breezy-weather/breezy-weather/releases/latest) - A Material Design Weather Application
- Onlne Video, Music, Streaming, Podcasts, etc
  - [NewPipe](https://f-droid.org/packages/org.schabi.newpipe/) - Lightweight YouTube frontend
  - [LibreTube](https://github.com/libre-tube/LibreTube/releases/latest) - An alternative frontend for YouTube, for Android.
  - [ViMusic](https://f-droid.org/packages/it.vfsfitvnm.vimusic/) - Seamlessly stream music from YouTube Music
  - [InnerTune](https://github.com/z-huang/InnerTune/releases/latest) - A Material 3 YouTube Music client for Android
  - [Spotube](https://github.com/KRTirtho/spotube/releases/latest) - 🎧 Open source Spotify client that doesn't require Premium nor uses Electron! Available for both desktop & mobile!
  - [Transistor](https://f-droid.org/packages/org.y20k.transistor/) - Transistor is an app for listening to radio stations over the internet.
  - [AntennaPod](https://f-droid.org/packages/de.danoeh.antennapod/) - Easy-to-use, flexible and open-source podcast manager and player
  - [Podverse](https://f-droid.org/packages/com.podverse.fdroid/) - Podcast app with clips, video, livestreams, playlists, profiles, and cross-platform
- Social Media
  - [Squawker](https://f-droid.org/en/packages/org.ca.squawker/) - An open-source anonymous Twitter/X client
  - [Infinity for Reddit](https://f-droid.org/en/packages/ml.docilealligator.infinityforreddit/) - A beautiful, feature-rich Reddit client.
  - [Mastodon](https://f-droid.org/packages/org.joinmastodon.android/) - Decentralized social network
  - [Shitter](https://f-droid.org/en/packages/org.nuclearfog.twidda/) - A lightweight Mastodon client focused on privacy and low data consumption
- Offline Media
  - [VLC Media Player](https://f-droid.org/packages/org.videolan.vlc/) - The best video and music player. Fast and “just works”, plays any file
  - [Video Transcoder](https://f-droid.org/packages/protect.videoeditor/) - Video transcoding between common formats
  - [Standard Notes](https://f-droid.org/packages/com.standardnotes/) - An end-to-end encrypted note-taking app for digitalists and professionals
  - [SimpleTextEditor](https://f-droid.org/packages/com.maxistar.textpad/) - Simple Text Editor
- Messenger (Private, Secure, etc)
  - [Brair](https://f-droid.org/packages/org.briarproject.briar.android/) - Secure Messaging, Anywhere
  - [Jami](https://f-droid.org/packages/cx.ring/) - Audio & Video Calls / Chat Take Control of your Communication!
  - [Session F-Droid](https://f-droid.org/en/packages/network.loki.messenger.fdroid/) - Encrypted private messenger
- Email Service
  - [Proton Mail](https://github.com/ProtonMail/proton-mail-android/releases/latest)
  - [Tuta](https://f-droid.org/en/packages/de.tutao.tutanota/)
  - [Github Link](https://github.com/tutao/tutanota/releases)
- VPNs
  - [Mullvad VPN](https://f-droid.org/packages/net.mullvad.mullvadvpn/) - Protect your online privacy with a fast, trustworthy, and easy-to-use VPN.
  - [IVPN](https://f-droid.org/packages/net.ivpn.client/) - Privacy focused VPN service with WireGuard
  - [Calyx VPN](https://f-droid.org/packages/org.calyxinstitute.vpn/) - Free VPN Service offered by The Calyx Institute
  - [ProtonVPN](https://f-droid.org/packages/ch.protonvpn.android/) - Free Swiss VPN with advanced security and privacy features.
- App Control & Container/Isolator
  - [NetGuard](https://f-droid.org/packages/eu.faircode.netguard/) - A simple way to block access to the internet per application
  - [Insular](https://f-droid.org/packages/com.oasisfeng.island.fdroid/) - Isolate your Big Brother apps
- Misc. Apps
  - [PCAPdroid](https://f-droid.org/packages/com.emanuelef.remote_capture/) - No-root network monitor and traffic dump tool for Android devices
  - [Seal](https://f-droid.org/en/packages/com.junkfood.seal/) - 🦭 Video/audio downloader for Android (YT-DLP), designed with Material You 
  - [PrivacyBlur](https://f-droid.org/packages/de.mathema.privacyblur/) - Blur or pixelate faces or sensitive areas in pictures
  - [KeePassDX](https://f-droid.org/packages/com.kunzisoft.keepass.libre/) - Secure and open source password manager compatible with KeePass files.
  - [Lemuroid](https://f-droid.org/packages/com.swordfish.lemuroid/) - All in one emulator on Android
  - [Lawnchair](https://f-droid.org/en/packages/ch.deletescape.lawnchair.plah/) - Pixel Launcher features plus customizability
  - [Public IP](https://f-droid.org/en/packages/net.guildem.publicip/) - App and Widget allowing user to find its current public IP address
  - [Catima](https://f-droid.org/packages/me.hackerchick.catima/) - Catima, a Loyalty Card & Ticket Manager for Android

### Aurora Store Apps
- Magic Earth
  - [Google Play Store](https://play.google.com/store/apps/details?id=com.generalmagic.magicearth)
  - Direct Download: [https://www.magicearth.com/apk/](https://www.magicearth.com/apk/) - Password: `7h6Q7\9AsF:a7"Ja`
- Tor Browser
  - [Google Play Store](https://play.google.com/store/apps/details?id=org.torproject.torbrowser)

</details>




## Personal Layout Design

<details>
<summary>Click to expand...</summary>

## Personal Current Phone Layout
![image](https://github.com/Scrut1ny/GrapheneOS-Guide/assets/53458032/48b8fe77-1c37-4e1c-afb9-6be1c2d23787)

- If you would like your system to look like mine, please check out these apps:
  - [KISS](https://github.com/Neamar/KISS/releases/latest) - Lightning fast, open-source, < 250kb Android launcher
  - [Lawnchair](https://github.com/LawnchairLauncher/lawnchair/releases) - Pixel Launcher features plus customizability
  - [Public IP](https://f-droid.org/packages/net.guildem.publicip/) - App and Widget allowing user to find its current public IP address
  - Arcticons
    - [Arcticons Dark](https://f-droid.org/packages/com.donnnno.arcticons/) - A monotone line-based icon pack
    - [Arcticons Light](https://f-droid.org/packages/com.donnnno.arcticons.light/) - A monotone line-based icon pack
    - [Arcticons You](https://f-droid.org/packages/com.donnnno.arcticons.you/) - A Material You line-based icon pack

</details>




## Other Awesome Guides
- [https://alternativeto.net/list/35462/grapheneos-appverse/](https://alternativeto.net/list/35462/grapheneos-appverse/)
- [https://www.devilreef.net/securing-a-personal-android-phone/](https://www.devilreef.net/securing-a-personal-android-phone/)
- [https://redandblack.io/blog/2020/how-to-set-up-grapheneos/](https://redandblack.io/blog/2020/how-to-set-up-grapheneos/)
- [https://craignuzzo.tech/grapheneos/](https://craignuzzo.tech/grapheneos/)
