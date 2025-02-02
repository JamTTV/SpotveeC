# SpotveeC

<h1 align="center">

![GitHub all releases](https://img.shields.io/github/downloads/SpotCompiled/SpotveeC/total?label=Downloads&style=for-the-badge) 
![GitHub Repo stars](https://img.shields.io/github/stars/SpotCompiled/SpotveeC?label=Stars&style=for-the-badge) 
![GitHub release (latest by date)](https://img.shields.io/github/v/release/SpotCompiled/SpotveeC?label=Release&style=for-the-badge) 
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/SpotCompiled/SpotveeC?include_prereleases&label=PRE-Release&style=for-the-badge) 

</h1>

This is my repo for compiled EeveeSpotify IPAs. EeveeSpotify is a Spotify IOS app tweak that removes ads, removes limited skips, and almost every other premium feature. The only main premium feature that does not work is offline downloads, as this is done server-side.

## Adding to AltStore/SideStore<br/>

### Option One:<br/>
You can add my repo to AltStore *Beta* or SideStore for automatic updates and convenience, by following the steps below:<br/>
[Click this link](https://tinyurl.com/SpotC-Import) on your device with SideStore/AltStore and it will open SideStore/AltStore with it prompting you to add the source.

### Option Two:<br/>
You can add my repo to AltStore *Beta* or SideStore for automatic updates and convenience, by following the steps below:<br/>
1. Tap "Sources" in the top-right corner of the Browse tab.<br/>
2. Tap the ”+” button and add my source by entering its URL "https://tiny.one/SpotC"
3. Now any "SpotC" Apps will show up in AltStore/SideStore under the "Browse" tab where you can install and update your apps easily from within AltStore/SideStore.<br/>

## How it's Made<br/>
I post a new release everytime their is an EeveeSpotify Update, or there is a new major Spotify update that is compatible with the latest Spotilife. I get the vanilla Spotify IPA from IOS God's [Decrypted AppStore](https://armconverter.com/decryptedappstore/us/spotify) or from green verified links on [AppDB](https://appdb.to/app/ios/324684580), I will specify details on each release page. Then I download the latest EeveeSpotify .deb and SwiftProtobuf framework .deb (dependency) from Eevee's release page [here](https://github.com/whoeevee/EeveeSpotify/releases/latest) and Orion Runtime (iOS 14 - 16) off of Chariz [here](https://chariz.com/get/orion-runtime14) (it's a dependency) using [cydownload](https://github.com/borishonman/cydownload). I then inject the .deb into the IPA using [Sidloadly](https://sideloadly.io) or [Azule](https://github.com/Al4ise/Azule), and change the IPA version to the SpotveeC version. I do not do anything else to the IPA (Unless otherwise specified in the release notes)... However please note that theoretically, IOSGod's decrypted app store could insert malware, same with Sideloadly/Azule, cydownload and Eevee's tweak, these are, however, considered trusted by the community and/or Open-Source. This is use at your own risk, and I am not responsible for *ANY* damage.

Version Format is *SpotveeC Version*\_*Spotify Version*<br/>
Ex. *v1.3.6*\_*v8.7.78*<br/>

## Credits:<br/>
[IOS God's Dycrypted App Store](https://armconverter.com/decryptedappstore/us/spotify) and [AppDB](https://appdb.to/app/ios/324684580)- *Dycrypted Vanilla Spotify IPA*<br/>
[julioverne-  Spotilife](https://julio.hackyouriphone.org/) *For the original Spotilife tweak*<br/>
[Whoeevee-  EeveeSpotify](https://github.com/whoeevee/EeveeSpotify) *For EeveeSpotify tweaked .deb*<br/>
[Theos Team-  Orion Runtime (iOS 14 - 16)](https://chariz.com/get/orion-runtime14) *For Orion Runtime (iOS 14 - 16) tweaked .deb*<br/>
[Am1nCmd- Spotify++](https://appdb.to/app/cydia/1900000540) *For ScreenShots*<br/>
[@RobyRew](https://github.com/RobyRew) *For helping me setup a lot of things*
***
<sup>We are not affiliated, associated, authorized, endorsed by, or in any way officially connected with any other company, agency, or government agency. All product and company names are trademarks™ or registered® trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them.</sup>
