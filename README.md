# NativeScript CLI Basic

## Installation

### NativeScript Framework
```
npm install -g nativescript
```

### Android and iOS requirements
For Windows:
```
@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://www.nativescript.org/setup/win'))"
```
For MacOS:
```
sudo ruby -e "$(curl -fsSL https://www.nativescript.org/setup/mac)"
```

### Verift Setup
```
tns doctor
```

## Basic workflow

### Create new NativeScript project
```
tns create <ProjectName> --ng
```

### Project liveview
On Device
```
tns run android
tns run ios
```

On Simulator
```
tns run android --emulator
tns run ios --emulator
```

### Create config files before git commit

[.gitignore](.gitignore)

[.vscode/settings.json](.vscode/settings.json)

[.vscode/launch.json](.vscode/launch.json)

### Initial Git commit
```
git init
git add .
git commit -m "Initial Setup"
```

