### Apktool
**This is the repository for Apktool. If you are looking for the Apktool website. Click [here](https://github.com/iBotPeaches/Apktool/tree/gh-pages).**

[![Join the chat at https://gitter.im/iBotPeaches/Apktool](https://badges.gitter.im/iBotPeaches/Apktool.svg)](https://gitter.im/iBotPeaches/Apktool?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/iBotPeaches/Apktool.svg?branch=master)](https://travis-ci.org/iBotPeaches/Apktool)
[![Software License](https://img.shields.io/badge/license-Apache%202.0-brightgreen.svg)](https://github.com/iBotPeaches/Apktool/blob/master/LICENSE)

It is a tool for reverse engineering 3rd party, closed, binary Android apps. It can decode resources to nearly original form and rebuild them after making some modifications; it makes possible to debug smali code step by step. Also it makes working with app easier because of project-like files structure and automation of some repetitive tasks like building apk, etc.

It is NOT intended for piracy and other non-legal uses. It could be used for localizing, adding some features or support for custom platforms and other GOOD purposes. Just try to be fair with authors of an app, that you use and probably like.

#### Support
- [Project Page](http://ibotpeaches.github.io/Apktool/)
- [#apktool on freenode](http://webchat.freenode.net/?channels=apktool)

#### Sponsored by

* [Sourcetoad](https://www.sourcetoad.com/cool-tools/apktool/) - helping with a weekly sponsorship for continued improvement and maintenance of the project.

#### IDE of Choice

![JetBrains IntelliJ](.github/intellij.png?raw=true "IntelliJ")


#### Security Vulnerabilities

If you discover a security vulnerability within Apktool, please send an e-mail to Connor Tumbleson at connor.tumbleson(at)gmail.com. All security vulnerabilities will be promptly addressed.

#### Links
- [Downloads](https://bitbucket.org/iBotPeaches/apktool/downloads)
- [Downloads Mirror](http://connortumbleson.com/apktool/)
- [How to Build](http://ibotpeaches.github.io/Apktool/build/)
- [Documentation](http://ibotpeaches.github.io/Apktool/documentation/)
- [Bug Reports](https://github.com/iBotPeaches/Apktool/issues)
- [Chat on Gitter](https://gitter.im/iBotPeaches/Apktool)
- [Changelog/Information](http://ibotpeaches.github.io/Apktool/changes/)
- [XDA Post](http://forum.xda-developers.com/showthread.php?p=28366939)
- [Source (Github)](https://github.com/iBotPeaches/Apktool)
- [Source (Bitbucket)](https://bitbucket.org/iBotPeaches/apktool/)


### Install Instructions
#### Quick Check
- Is at least Java 1.7 installed?
- Does executing java -version on command line / command prompt return 1.7 or greater?
- If not, please install Java 7+ and make it the default.
- Installation for Apktool
#### Windows:
- Download Windows wrapper script (Right click, Save Link As apktool.bat)
- Download apktool-2 (find newest here)
- Rename downloaded jar to apktool.jar
- Move both files (apktool.jar & apktool.bat) to your Windows directory (Usually C://Windows)
- If you do not have access to C://Windows, you may place the two files anywhere then add that directory to your Environment - - Variables System PATH variable.
- Try running apktool via command prompt
#### Linux:
- Download Linux wrapper script (Right click, Save Link As apktool)
- Download apktool-2 (find newest here)
- Rename downloaded jar to apktool.jar
- Move both files (apktool.jar & apktool) to /usr/local/bin (root needed)
- Make sure both files are executable (chmod +x)
- Try running apktool via cli
#### Mac OS X:
- Download Mac wrapper script (Right click, Save Link As apktool)
- Download apktool-2 (find newest here)
- Rename downloaded jar to apktool.jar
- Move both files (apktool.jar & apktool) to /usr/local/bin (root needed)
- Make sure both files are executable (chmod +x)
- Try running apktool via cli
#### Note - Wrapper scripts are not needed, but helpful so you don’t have to type java -jar apktool.jar over and over.
