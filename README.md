# Flutter Template

Flutter app for FlutterTemplate

## Using this template

1. Replace "flutter_template" by "your_project_package_name"
2. Replate "FlutterTemplate" by "your_project_name"
3. Rename folder "android/app/src/main/kotlin/com/enlabsoftware/flutter_template" to "your_project_package_name"
4. Install dependencies and run "flutter_launcher_icons"


## Translate

Generate Keys

```bash
$ get generate locales
```

## Automatic Json Serializing in Flutter Using Json Annotation

Run:

```bash
$ flutter packages pub run build_runner build --delete-conflicting-outputs
```

## Build release

Android .apk

```bash
$ flutter build apk --release
```

## Using FVM

If using FVM, in all command need to add "fvm" before the old command

```bash
$ fvm flutter pub get
```