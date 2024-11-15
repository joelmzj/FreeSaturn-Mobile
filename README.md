# FreeSaturn - Mobile
## Freezer Reborn

For non-premium Deezer users. (I've just removed premium account verification. Obviously premium features, as flac and 320kb qualities, doesn't work.)

### Donations
https://fund.saturnclient.dev/

# Featuring:
- FLAC & MP3 320 support
- BYO Last.fm Integration (Safer solution!)
- Fixed homepage
- Minor updates to make things work with newer API
- (aaand don't forget everything the older app had)

### You can download Saturn right away although it is highly advised to build it yourself, customized to your own liking.

# Links
- website: https://saturnclient.dev
- discord: https://saturnclient.dev/discord
- telegram: https://t.me/SaturnReleases

# Download from Releases or Telegram
https://github.com/SaturnMusic/mobile/releases
https://t.me/SaturnReleases

# Credits
Saturn Mobile is a modified version of ReFreezer which you can check out by [Clicking Here.](https://github.com/DJDoubleD/refreezer)

# Compile from source

Install flutter SDK 3.17.2: https://flutter.dev/docs/get-started/install  
(Optional) Generate keys for release build: https://flutter.dev/docs/deployment/android  

Download source:
```
git clone https://github.com/joelmzj/FreeSaturn-Mobile
cd FreeSaturn-Mobile
git submodule init 
git submodule update
```

Compile:  
```
flutter pub get
flutter build apk
```  
NOTE: You have to use own keys, or build debug using `flutter build apk --debug`

# Desktop Version
https://github.com/SaturnMusic/PC
