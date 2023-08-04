## 💵 Purchase Guide

- 📱 Mobile Phone
  - Purchase a new `Google Pixel 6a`> with `cash` from a local physical store and avoid Verizon, as they lock the OEM.

- 📶 Mobile Carrier
  - Buy a pre-paid [Mint Mobile](https://www.mintmobile.com/) (T-Mobile) SIM card with `cash` from a local store.
    - Wire it up to a [privacy.com](https://privacy.com/) card.
      - For $30/month, it provides unlimited* 4G/5G domestic data with relatively little attributable information on the account (e.g., no name, address, SSN, etc.)
  - [Calyx hotspot](https://calyxinstitute.org/membership/internet) for unlimited, unthrottled, anonymous connectivity. 

- 📲 Mobile Accessories (optional)
  - Protective Case/Cover
      - [Google Pixel](https://www.amazon.com/stores/page/1AEDD91F-AFDC-49AA-A7F4-2BF2A6AEBD57)
  - Privacy Screen Protector
      - [Google Pixel](https://www.amazon.com/stores/page/EE20BD00-A914-460E-B3CC-12A13BB945E2/search?terms=Google%20Pixel)
  
## ⬇️ Install Guide

Official Site > [https://grapheneos.org](https://grapheneos.org)

- Web Install Guide > [Link](https://grapheneos.org/install/web)

- CLI Install Guide > [Link](https://grapheneos.org/install/cli)

## 🔓 Unlocking the OEM

- Remove SIM
- Factory reset
- Setup Wi-Fi Connection
- Settings > System > Dev > `Allow OEM unlocking` ✅

## ⬇️ Installing Google USB Driver

Install the Google USB Driver > [Link](https://dl.google.com/android/repository/usb_driver_r13-windows.zip), after that hit `WIN + R` then enter `devmgmt.msc` and select your pixel device and install a custom update (select the unzipped file you just downloaded).

## ⚙️ Settings

#### Network & internet
- Settings > Network & internet > Internet > Carrier Settings ⚙️ > Allow 2G ❌
- Settings > Network & internet > Internet > Select your WiFi ⚙️ > select pen icon > Advanced options > Privacy > Use per-connection randomized MAC (default) ✅
- Settings > Network & internet > Private DNS > Private DNS provider hostname: `dns.quad9.net` ✅
- Settings > Network & internet > Internet connectivity checks ❌
- Settings > Network & internet > Attestation key provisioning ✅

#### Apps
- Settings > Apps > Default apps (Set your favorite default apps here) ✅

#### Battery
- Settings > Battery > Battery Percentage ✅

### Sound & vibration
- Settings > Sound & vibration > Vibration & haptics ❌
- Settings > Sound & vibration > Dial pad tones ❌
- Settings > Sound & vibration > Screen locking sound ❌
- Settings > Sound & vibration > Charging sounds and vibration ❌
- Settings > Sound & vibration > Touch sounds ❌
- Settings > Sound & vibration > Always show icon when in vibrate mode ❌

### Display
- Settings > Display > Adaptive Brightness ✅
- Settings > Display > Auto-rotate screen ✅
- Settings > Display > Lock Screen > Notifications on Lock Screen > Don’t show notifications at all ✅
- Settings > Display > Lock Screen > Show lockdown option ✅
- Settings > Display > Lock Screen > Wake screen for notifications ❌
- Settings > Display > Dark Theme ✅
- Settings > Display > Night Light ✅
  - Don’t use sunset to sunrise (uses device location data) use a specified custom time to time.
- Settings > Security > Auto reboot > 12 Hours ✅
- Settings > Security > Enable native code debugging ❌
- Settings > Security > PIN scrambling > Scramble PIN ✅
- Settings > Privacy > Permission manager > Customize Everything! ✅
  - Use [exodus-privacy](https://exodus-privacy.eu.org/).
- Settings > System > Language & Input > on screen keyboard > GraphineOS Keyboard > Appearance & Layouts > Theme > Material Dark ✅

## 🛍️ Apps

- FOSS Essential Apps
  - Web Browser
    - [Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/)
  - YouTube Alt
    - [NewPipe](https://github.com/TeamNewPipe/NewPipe/releases/latest)
  - Movie/Show Streaming Alt
    - [CloudStream](https://github.com/recloudstream/cloudstream/releases/latest)
  - Music
    - [ViMusic](https://github.com/vfsfitvnm/ViMusic/releases/latest)
  - Secure Messaging
    - [Signal](https://signal.org/android/apk/)
  - Orbot
    - [Google Play Store](https://play.google.com/store/apps/details?id=org.torproject.android)
  - Navigation (Magic Earth)
    - [Google Play Store](https://play.google.com/store/apps/details?id=com.generalmagic.magicearth)
  - Weather
    - [Rain](https://github.com/DarkMooNight/Rain/releases/latest)

- App Stores
  - [F-Droid](https://f-droid.org/)
  - [Aurora Store](https://f-droid.org/en/packages/com.aurora.store/)

- F-Droid Apps
  - Web Browser
      - [Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/)
  - Navigation
      - [Organic Maps](https://f-droid.org/en/packages/app.organicmaps/)
      - [OsmAnd~](https://f-droid.org/en/packages/net.osmand.plus/)
  - Onlne Video, Music, Streaming, Podcasts, etc
      - [NewPipe](https://f-droid.org/en/packages/org.schabi.newpipe/)
      - [ViMusic](https://f-droid.org/en/packages/it.vfsfitvnm.vimusic/)
      - [Transistor](https://f-droid.org/en/packages/org.y20k.transistor/)
      - [AntennaPod](https://f-droid.org/en/packages/de.danoeh.antennapod/)
      - [Podverse](https://f-droid.org/en/packages/com.podverse.fdroid/)
  - Social Media
      - [Fritter](https://f-droid.org/en/packages/com.jonjomckay.fritter/)
  - Offline Media
      - [VLC Media Player](https://f-droid.org/en/packages/org.videolan.vlc/)
      - [Standard Notes](https://f-droid.org/en/packages/com.standardnotes/)
      - [SimpleTextEditor](https://f-droid.org/en/packages/com.maxistar.textpad/)
  - Messenger (Private, Secure, etc)
      - [Brair](https://f-droid.org/en/packages/org.briarproject.briar.android/)
  - VPNs
      - [Mullvad VPN](https://f-droid.org/en/packages/net.mullvad.mullvadvpn/)
      - [IVPN](https://f-droid.org/en/packages/net.ivpn.client/)
      - [Calyx VPN](https://f-droid.org/en/packages/org.calyxinstitute.vpn/)
      - [ProtonVPN](https://f-droid.org/en/packages/ch.protonvpn.android/)
      - [Riseup VPN](https://f-droid.org/en/packages/se.leap.riseupvpn/)
  - App Container/Isolator, sniffer, etc
      - [NetGuard](https://f-droid.org/en/packages/eu.faircode.netguard/)
      - [Insular](https://f-droid.org/en/packages/com.oasisfeng.island.fdroid/)
      - [PCAPdroid](https://f-droid.org/en/packages/com.emanuelef.remote_capture/)

- Aurora Apps
  - Magic Earth
    - [Google Play Store](https://play.google.com/store/apps/details?id=com.generalmagic.magicearth)
  - Session
    - [Google Play Store](https://play.google.com/store/apps/details?id=network.loki.messenger)
    - [GitHub](https://github.com/oxen-io/session-android/releases)
  - Signal
    - [Signal Website](https://signal.org/android/apk/)
  - Orbot
    - [Google Play Store](https://play.google.com/store/apps/details?id=org.torproject.android)
  - Tor Browser
    - [Google Play Store](https://play.google.com/store/apps/details?id=org.torproject.torbrowser)

- External Apps
  - [CloudStream](https://cloudstream.cf/)

## Spoofing (DON'T ATTEMPT ON GRAPHENEOS, SYSTEM IS NOT MEANT TO BE ROOTED.)
- Spoofing Device Information
  - Install [tutorial](https://www.youtube.com/watch?v=4ZS5QiWB8WI)
  - [Magisk](https://github.com/topjohnwu/Magisk/releases/latest)
  - [Riru](https://github.com/RikkaApps/Riru/releases/latest)
  - [EdXposed](https://github.com/ElderDrivers/EdXposed/releases/latest)
- Best Spoofing Apps
  - [Android Faker](https://github.com/Xposed-Modules-Repo/com.android1500.androidfaker/releases/latest)
  - [MACsposed](https://github.com/DavidBerdik/MACsposed/releases/latest)

## If your system is bricked, boot looping, system is corrupted, showing critical errors, etc. use this.
- [Guide](https://forum.xda-developers.com/t/guide-flashing-a-factory-image-with-fastboot-return-to-stock.1907796/)
- After that make sure to do the GrapheneOS install again.
- [GrapheneOS](https://grapheneos.org/install/)

## Credits

- https://www.devilreef.net/securing-a-personal-android-phone/
- https://redandblack.io/blog/2020/how-to-set-up-grapheneos/
- https://github.com/ivoarch/GrapheneOS-Setup
- https://craignuzzo.tech/grapheneos/

## Phone Layout
![signal-2023-02-08-204304](https://user-images.githubusercontent.com/53458032/217694195-43b1c3bc-f72c-435b-86c6-110fe0110938.png)
