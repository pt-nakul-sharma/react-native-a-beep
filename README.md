
# react-native-a-beep
A very lite module to play system sounds and beep for react-native apps (no sound files)
## Sponsor by
[Go Noter app](https://gonoter.com "Go Noter - Group travel asssistant") - Group travel and expenses assistant!
## Getting started

`$ npm install @pt-nakul-sharma/react-native-a-beep --save`

## Android 15 Compatibility

This package is fully compatible with **Android 15 (API Level 35)** and supports:
- ✅ **Target SDK**: 35 (Android 15)
- ✅ **Compile SDK**: 35 (Android 15)  
- ✅ **Min SDK**: 21 (Android 5.0)
- ✅ **React Native**: 0.69.0+

### (RN < 0.60) Mostly automatic installation

`$ react-native link @pt-nakul-sharma/react-native-a-beep`

### Manual installation

### Using CocoaPods
> If the CocoaPods package manager is new to you, please first review
> its [installation guide](https://guides.cocoapods.org/using/getting-started.html)
pod 'RNReactNativeABeep', :path => '../node_modules/@pt-nakul-sharma/react-native-a-beep'
```ruby
# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target '_YOUR_PROJECT_TARGET_' do
pod 'RNReactNativeABeep', :path => '../node_modules/@pt-nakul-sharma/react-native-a-beep'
end
```

```sh
cd ios
pod install
```
#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `@pt-nakul-sharma/react-native-a-beep` and add `RNReactNativeABeep.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNReactNativeABeep.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.trietho.RNReactNativeABeepPackage;` to the imports at the top of the file
  - Add `new RNReactNativeABeepPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':@pt-nakul-sharma/react-native-a-beep'
  	project(':@pt-nakul-sharma/react-native-a-beep').projectDir = new File(rootProject.projectDir, '../node_modules/@pt-nakul-sharma/react-native-a-beep/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':@pt-nakul-sharma/react-native-a-beep')
  	```

## Usage
```javascript
import RNReactNativeABeep from 'react-native-a-beep';

// TODO: What to do with the module?
RNReactNativeABeep;
```
  
