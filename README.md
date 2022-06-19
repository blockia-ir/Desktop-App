# Blockia Desktop
Desktop app for Blockia

شروع رایگان و آسان با بلوکیا !

آزمون ساز رایگان و آنلاین برای مدرسه ها ، دانشگاه ها و مراکز آموزشی دیگر با بیشترین امکانات

# Installation
Download Node Js On System

Extrat Blockia Desktop On Folder

Go To Folder
```bash
npm install
```
 for run test app :
 ```bash
npm start
```

# Build the Application for platforms
First you need to install electron-builder package globally :
```bash
$ npm i electron-builder -g
```
To build all platform :
```bash
$ electron-builder -mwl
```
To build the macOS platform:
```bash
$ electron-builder --mac
```
To build the Windows platform:
```bash
$ electron-builder --win
```
To build the Linux platform:
```bash
$ electron-builder --linux
```

Built output applications are located in the newly created directory called “dist” which is inside your application directory.
