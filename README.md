# flutter_app

![Android_IOS-CI](https://github.com/liudonghua123/flutter_app/workflows/Android_IOS-CI/badge.svg)
![WEB-CI](https://github.com/liudonghua123/flutter_app/workflows/WEB-CI/badge.svg)
![MacOS-CI](https://github.com/liudonghua123/flutter_app/workflows/MacOS-CI/badge.svg)
![Linux-CI](https://github.com/liudonghua123/flutter_app/workflows/Linux-CI/badge.svg)
![Windows-CI](https://github.com/liudonghua123/flutter_app/workflows/Windows-CI/badge.svg)
![TestFlight](https://github.com/liudonghua123/flutter_app/workflows/TestFlight/badge.svg)

This is a flutter quick starter template project which support mobile (android, ios), web and desktop (MacOS, Linux, Windows) platform.

It also integrates with github actions for CI/CD. When you push a tag, then after a few minutes, all these platform build files are available in the [release](https://github.com/liudonghua123/flutter_app/releases) page.

## Getting Started

Because of using the web and desktop features, you should config flutter to use `master` branch. And enable these features via the following commands.

Please Note Windows and Linux desktop platform support are still in technical preview.

```bash
flutter config --enable-web
flutter config --enable-macos-desktop
flutter config --enable-linux-desktop
flutter config --enable-windows-desktop
```

Dev command:

`flutter run -d android/ios/chrome/macos/linux/windows`

Build command: (Does not support build other desktop platform apps, in short does not support *cross-compilation*)

```bash
> flutter build -h
Flutter build commands.

Usage: flutter build <subcommand> [arguments]
-h, --help    Print this usage information.

Available subcommands:
  aar             Build a repository containing an AAR and a POM file.
  aot             Build an ahead-of-time compiled snapshot of your app's Dart
                  code.
  apk             Build an Android APK file from your app.
  appbundle       Build an Android App Bundle file from your app.
  bundle          Build the Flutter assets directory from your app.
  ios             Build an iOS application bundle (Mac OS X host only).
  ios-framework   Produces a .framework directory for a Flutter module and its
                  plugins for integration into existing, plain Xcode projects.
  macos           build the MacOS desktop target.
  linux           build the Linux desktop target.
  web             build a web application bundle.
  windows         build the desktop Windows target.

Run "flutter help" to see global options.
```

## License

MIT License

Copyright (c) 2020 liudonghua

## References

- [online documentation](https://flutter.dev/docs)
- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Web support for Flutter](https://flutter.dev/web)
- [Building a web application with Flutter](https://flutter.dev/docs/get-started/web)
- [Desktop support for Flutter](https://flutter.dev/desktop)
