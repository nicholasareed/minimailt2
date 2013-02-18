

## Contents  

Source for the minimail mobile email client for Android. The app works in conjunction with a server-side component (receiving and sending emails, Push Notifications, leisure filters) and the Emailbox API (https://getemailbox.com/docs).  


## Requirements:  
- Android 2.2+

## Option 1: Build with PhoneGap Build  
1. Fork this repo 
1. Sign up for Adobe PhoneGap Build: http://build.phonegap.com/plans/free 
1. Create a new project in PhoneGap Build using your forked GitHub URL 
1. Build the project and download the Android build (only Android is currently supported)

## Option 2: Build locally with Eclipse SDK
1. (coming soon)
1. Follow the instructions at https://github.com/emailbox/minimail_mobileapp_full (coming soon)

bq. **Note:** Push Notifications don't work when building locally

## Server-side  
Want to run your own server-side minimail code as well? (available soon)  

## App Todos
- switch to Require.js, Component, Browserify, etc. (easier plugins)

## Build Todos:
- Tests  
- Add instructions for Trigger.io Forge (easier builds)  
- Build and test for iPhone  

## Major Gotchas/Issues:  
- Please post (additional) issues in GitHub's issue tracker! 

## How to build (coming soon):  
1. Download the Android SDK tools  
1. Configure Eclipse IDE and ADT Plugin (download from one place)  
1. Run `./create <path> <com.name> <app_name>`  
1. Clone minimail app and overwrite files in created directory  
1. Create Android project  
1. Build and Run on your phone  
1. (add Support Library to project by right-click Android Tools -> Add...)
