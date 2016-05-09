### Introducing AlcatrazApp

[Alcatraz](http://alcatraz.io) is the Package manager for Xcode. Its self is originally designed as a Xcode plugin. But when Apple releases new version of Xcode which `DVTPlugInCompatibilityUUIDs` maybe also changed to some new value. It then causes all Xcode plugins - even Alcatraz - can not be loaded and this issue was been discussed [long long ago](https://github.com/alcatraz/Alcatraz/issues/73).

AlcatrazApp is simply a standalone container app for Alcatraz. It loads Alcatraz just like Xcode without checking `DVTPlugInCompatibilityUUIDs`. So you can still manage your plugins without openning Xcode. sometimes It's really helpful.

### Downloads

Download [latest verison](https://github.com/hewigovens/AlcatrazApp/releases/tag/1.0).

### Screenshot

![AlcatrazApp](doc/screenshot.png)

### Note

This repo is only for hosting releases. the code is [here](https://github.com/hewigovens/Alcatraz/tree/standalone-app).
