# Command Mobile Penetration Testing Cheatsheet for iOS

**Caution** : iOS application has a different environment with Android application, some command in here is only working with MacOS.

## Preparation
**Install Brew**, Open terminal (Finder -> Application -> Utilities -> Terminal) and run this command :</br>
`$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`</br></br>
**Install XCode**, Open terminal and run this command : </br>
`$ xcode-select --install`</br>
Or you can download manualy on [Apple Website](https://developer.apple.com/downloads)</br></br>

Regist your apple ID as [Apple Developer Account](http://developer.apple.com/account). You dont need to pay as Apple Developer Program on this section just register your account into developer, because we just need to get Certificate for signing ipa file on XCode or other tools.

## SSH Over USB (iPROXY)
http://iphonedevwiki.net/index.php/SSH_Over_USB

## Download .ipa file from app store or iPhone/iPad device

### Need Jailbroken 
#### Clutch
[Clutch](https://github.com/KJCracks/Clutch)

#### Frida Script
[Frida-ios-dump](https://github.com/AloneMonkey/frida-ios-dump)
command:
`$ iproxy 2222 22`
`$ ./dump.py BundleID`
