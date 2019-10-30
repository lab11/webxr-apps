<img src="resources/ios/icon/icon-108@2x.png" height="108" align="left" hspace="6" />

# Lab11 XR

An iOS environment to display and test new WebXR content<br/><br/>


## WebXR Apps

A number of example WebXR apps are included in `www/examples/` ([preview](https://lab11.github.io/webxr-apps/www)). 

#### Lab11 Apps:

- `Paint the Lights` : Control LIFX bulbs by selecting a color and pointing camera at the lights.
- `Snap and Command` : Take a picture of devices and select from device specific-actions to perform.


## Build and Run

Assuming [requirements](#requirements) are satisfied, prepare within the main directory:

    cordova prepare

To run on iOS device:

    cordova run --device --developmentTeam=<TEAM_ID>

Alternatively, use `cordova build`, open `platforms/ios/Lab11 XR.xcodeproj`, and run from XCode. 


## Requirements

- [Node.js](https://nodejs.org)
- [Cordova](https://cordova.apache.org/)
- [XCode on Mac](https://developer.apple.com/xcode/)
- [Apple Developer Account](https://developer.apple.com/)
- iOS 12.0+ Device


## Credits

The iOS application uses [cordova-plugin-webxr](https://github.com/tzachari/cordova-plugin-webxr) to create the WebXR-compatible environment.

The plugin and examples are based on work by [Mozilla's WebXR Viewer project](https://github.com/mozilla-mobile/webxr-ios).
