# Development and Evaluation of XR app using W3C, WebXR API 
## Education through 3D model visualization

We do not need to develop different app for different 3D model for education. They are just a link away.
Click on any item that you want to know about.

Tap on the screen to see the 3D model.

Tap on any part of the body to know about it.


The XR app is implemented on the top of webxr-polyfill framework. 

Apps are hosted on https://shaon-webxr.herokuapp.com

(this repo is exported from the common repo with other experiments https://github.com/shaondebnath/Web-base-Augmented-reality-with-Object-detection.git)


## Building and Running the examples

	npm install   # downloads webpack and an http server
	npm start     # builds the polyfill in dist/webxr-polyfill.js and start the http server in the current directory


Best works on WebXR Viewer on iOS

Browse http://YOUR_HOST_NAME:8080/	and select "Education: 3D Model"

Video Demo: https://www.youtube.com/watch?v=5aqUpPg2XOE



For other Demo Videos checkout playlist: https://www.youtube.com/watch?v=5aqUpPg2XOE&list=PLxchafb_QYe7kxxKm8bc1vkpz3yBo5i6g

### WARNING
The app is developed on unstable version of webxr-polyfill. for more information please go through webxr-polyfill Framework from https://github.com/mozilla/webxr-polyfill


## Supported Devices and browsers

### iOS users
Install XR Browser from Apple Store(iOS 11.0 or later)
https://itunes.apple.com/us/app/webxr-viewer/id1295998056?mt=8 


### Android Users:
Step1: Install Tango Core (https://github.com/google-ar/arcore-android-sdk/releases/download/sdk-preview/arcore-preview.apk) (also can be found in google play store)

Step2: Install Browser: WebARonARCore (https://github.com/google-ar/WebARonARCore/raw/webarcore_57.0.2987.5/apk/WebARonARCore.apk)

### Supported device list
Supported devices list can be found at https://developers.google.com/ar/discover/supported-devices 
