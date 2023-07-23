# Kirigami2 Tutorial
A tutorial on building convergent applications using Kirigami2 for Linux &amp; Android <br/>
This tutorial is intended for Ubuntu-based Distributions. <br/>

### :link: LINKS
+ Kirigami API Reference. [:arrow_upper_right:](https://api.kde.org/frameworks/kirigami/html/index.html) <br/>
+ Official Tutorial for Kirigami2. [:arrow_upper_right:](https://develop.kde.org/docs/getting-started/kirigami/)<br/>
+ KDE Human Interface Guidelines. [:arrow_upper_right:](https://develop.kde.org/hig/)<br/>
+ KDE Frameworks. [:arrow_upper_right:](https://api.kde.org/frameworks/index.html)

# Setting Up for Development
Installing IDE and Development Packages.

### Installing KDevelop
Although IDE's (Kate & VSCode) and Text Editors (KWrite, Emacs, and Vim *which I personally use*) will suffice, KDevelop is an optimized environment for applications running through the KDE Framework.
```
sudo apt install kdevelop
```

### Installing Dependencies
The following packages are needed in order for the sources to be built.
```
sudo apt install cmake extra-cmake-modules build-essential qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev kirigami2-dev libkf5i18n-dev gettext libkf5coreaddons-dev
```
### Installing Other Packages
It is not necessary to install the following packages, but they may be of help during the development process.
```
sudo apt install kirigami-gallery kapptemplate kommit cuttlefish
```
**Kirigami Gallery** lets you view and play around with Kirigami2 components. <br/>
**KAppTemplate** is a template creator for QT Application including Kirigami2. <br/>
**Kommit** is a GIT client. <br/>
**CuttleFish** lets you browse on icons. <br/>

Files and sources from this repository is still under development. Thanks!
