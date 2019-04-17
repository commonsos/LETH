# Commons Wallets 
The Only mobile ligthwallet built with Ξthereum community in mind!

# About
Commons Wallets (Ligth Ξthereum Mobile Wallet) is the first hybrid mobile app to manage an Ethereum wallet built using Ionic framework with the aim to serve the open community.

# Features
Thanks to the great job of library of ConsenSys (eth-lightwallet), the app could manage the key-pairs securely on smartphone side without send any password out of the wallet.
Every transaction could be signed directly with the smartphone and sent to an ethereum node public/private.

With podular you could:

- Create a HD ligthwallet 
- Manage an Ethereum wallet address
- Set host node address private/test/public
- Send / Receive ETH
- Send / Receive TOKENS
- List your transactions
- Share Address via SMS, Email or Whisper v5 (Shh)
- Share your geolocation
- Request payments via SMS, Email or Whisper (Shh)
- Send messages / images to friends and community using Whisper protocol in unpersisted chat
- Send private unpersisted crypted messages to friends
- Backup / Restore wallet using Mnemonic passphrase
- Protect access with TouchID / PIN code
- Currency convertion value via Kraken API
- Add Custom Token and Share it with friends
- Run DApppodular (Decentralized external dapps embedded at runtime)

# Beta Testers
Become a BETA tester, install the App and help the community to grow up.
Visit <a href="http://www.commonsos.com">Commons OS website</a>


# References
```
https://github.com/ConsenSys/eth-lightwallet
```

# Stuff and info for the project (Draft!)

Install some stuff lke Node.js and npm  
```bash
https://nodejs.org/dist/v4.2.3/node-v4.2.3.pkg
```

Install ionic and cordova
```bash
sudo npm install -g cordova ionic
```

Clone the project
```bash
git clone https://github.com/inzhoop-co/podular.git
```

Test on browser in localhost:8100
```bash
ionic serve
```

ANDROID RELEASE
```
IONIC ANDROID RELEASE
- ionic cordova build --release android

JARSIGNER APK KEYSTORE
- jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore my-release-key.keystore [realease_file.apk] commons-wallet

GO TO ANDROID SDK FOLDER EX: C:\Users\Andy\AppData\Local\Android\Sdk\build-tools\27.0.3

- zipalign -v 4 [RELEASE APK] [OUTPUT APK]
EX : zipalign -v 4 D:\jELLYFISH\commons-wallets-bk\commons-wallet.apk D:\jELLYFISH\commons-wallets-bk\commons-walletsout.apk

```
# License
 GNU GENERAL PUBLIC LICENSE 3.0
