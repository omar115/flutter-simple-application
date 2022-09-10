# my_app

My simple application in flutter. Here I will cover most of the beginner friendly topics in flutter.

# Installation Instructions
### Step-1: Install Dart SDK on Mac
- Get the Dart SDK <br>
```
        $ brew tap dart-lang/dart
        $ brew install dart
```
- for other versions (Linux, Windows) follow this link <br>
https://dart.dev/get-dart


### Step-2: Install Flutter
#### For Linux version, run these commands:
```
        $ sudo snap install flutter --classic
        $ flutter sdk-path
        $ sudo snap install android-studio --classic
```

#### For MacOS (M1) go through these steps:
* Step-1: install rosetta in MacOS
```
        $ sudo softwareupdate --install-rosetta --agree-to-license
```
* Step-2: download the SDK from this link <br> https://docs.flutter.dev/get-started/install/macos
* Step-3: update your path from this link <br> https://docs.flutter.dev/get-started/install/macos#update-your-path

#### Step-3 Clone the repo
* Clone the repository called rakizo-ui from bitbucket <br> https://bitbucket.org/rakizo/rakizo_ui/src/master/

#### Step-4 (Optional)
* (Optional) Install Android SDK Command-line tools from Android SDK Manager
```
        Open Tools > SDK Manager
        From the left choose, Appearance & Behavior > System Settings > Android SDK
        Select SDK Tools from the top menu
        Check Android SDK Command-line tools and click 'apply'.
```
- (Optional) Set android-studio-directory
```
        $ flutter config --android-studio-dir /snap/android-studio/current/android-studio
```
- (Optional) Accept licences
```
        $ flutter doctor --android-licenses
        $ flutter doctor
```

### Step-5: Run the flutter in Chrome

- Step-1: run flutter web app in Google Chrome
```
        $ flutter run -d chrome --no-sound-null-safety --web-renderer=html --web-port=5000
```
If every commands work fine, you can run the flutter web successfully on Google
Chrome browser.


## Getting Started with Flutter learning

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
