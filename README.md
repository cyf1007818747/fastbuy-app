<p align="center">
  <img src="https://fastbuy-fd9d7.firebaseapp.com/images/cover.png" alt="FastBuy" title="FastBuy">
</p>

<p align="center">
  👉👉 <a href="https://youtu.be/mxLl_HvANt8">Click to view a video demonstration.</a> 👈👈
  <br/><br/><br/>
</p>

[![React Native][react_native-badge]][react_native-url]
[![iOS Platform][ios_platform-badge]][ios_platform-url]
[![Xcode][xcode-badge]][xcode-url]
[![Android Platform][android_platform-badge]][android_platform-url]
[![Android Studio][android_studio-badge]][android_studio-url]


## Requirements

### Mandatory

- MacOS.
- [Xcode](https://itunes.apple.com/br/app/xcode/id497799835?mt=12) and [Android Studio](https://developer.android.com/studio/index.html).
- [Homebrew](https://brew.sh/).
- [Node](https://nodejs.org), [Watchman](https://facebook.github.io/watchman/) and [React Native](https://facebook.github.io/react-native/).

### Optional

- [Atom](https://atom.io/), [Linter](https://atom.io/packages/linter) and [ESLinter](https://atom.io/packages/linter-eslint).
- [Oh My ZSH!](http://ohmyz.sh/) (add the line `source ~/.bash_profile` to **~/.zshrc** file).


## Enviroment Settings

### Mandatory

- Install [Xcode](https://itunes.apple.com/br/app/xcode/id497799835?mt=12) and run `xcode-select --install` on [Terminal](ssh://).

- Install [Android Studio](https://developer.android.com/studio/index.html) and create an emulator.

- Install [Homebrew](https://brew.sh/).

- Install [Node](https://nodejs.org), [Watchman](https://facebook.github.io/watchman/) and [React Native](https://facebook.github.io/react-native/):

```
brew update
brew install node
brew install watchman
npm install -g react-native-cli
```

### Optional

- Install [Atom](https://atom.io/) and follow packages: `lint`, `lint-eslint` and `linter-ui-default`.


## Steps to Run

### 1. Clone project and install the dependencies

```
git clone git@github.com:Bruno-Furtado/fastbuy-app.git && cd fastbuy-app && bundle install
```

### 2. Open the project in Android Studio

```
open -a /Applications/Android\ Studio.app android
```
> Press 'OK' on first alert, and do not update gradle plugin on second.

### 3. Start the server

```
react-native start
```

### 4. Make sure you have a simulator installed and run the app on iOS

```
react-native run-ios
react-native run-ios --simulator "My Simulator (12.1)"
```

### 5. Make sure you have started an emulator and run the app on Android

```
react-native run-android
```
> For the first build, you must enable the overlay permission.


## Change-log

A brief summary of each [FastBuy](https://github.com/Bruno-Furtado/fastbuy-app) release can be found on the [releases](https://github.com/Bruno-Furtado/fastbuy-app/releases).


## License

This code is distributed under the terms and conditions of the [MIT](https://github.com/Bruno-Furtado/fastbuy-app/blob/master/LICENSE).


[react_native-badge]: https://img.shields.io/badge/React%20Native-0.57.4-blue.svg?style=flat
[react_native-url]: https://facebook.github.io/react-native/
[ios_platform-badge]: https://img.shields.io/badge/iOS-10.0+-lightgrey.svg
[ios_platform-url]: https://developer.apple.com/
[xcode-badge]: https://img.shields.io/badge/Xcode-10.1+-lightgrey.svg
[xcode-url]: https://developer.apple.com/xcode/
[android_platform-badge]: https://img.shields.io/badge/Android-4.1+-green.svg
[android_platform-url]: https://developer.android.com/index.html
[android_studio-badge]: https://img.shields.io/badge/Android%20Studio-3.2.1+-green.svg
[android_studio-url]: https://developer.android.com/studio/install
