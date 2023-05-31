[<img src="comcast_logo.png" alt="React Native WebRTC" style="height: 6em;" />](https://github.com/555platform/react-native-webrtc/tree/webrtc-m111)

# React-Native-WebRTC

A WebRTC module for React Native.

## Feature Overview

|  | Android | iOS | macOS* | Windows* | Web* | Expo* |
| :-: | :-------: | :---: | :-----: | :--------: | :----: | :-----: |
| Audio/Video | :heavy_check_mark: | :heavy_check_mark: | - | - | :heavy_check_mark: | :heavy_check_mark: |
| Data Channels | :heavy_check_mark: | :heavy_check_mark: | - | - | :heavy_check_mark: | :heavy_check_mark: |
| Screen Capture | :heavy_check_mark: | :heavy_check_mark: | - | - | :heavy_check_mark: | :heavy_check_mark: |
| Plan B | - | - | - | - | - | - |
| Unified Plan* | :heavy_check_mark: | :heavy_check_mark: | - | - | :heavy_check_mark: | :heavy_check_mark: |
| Simulcast* | :heavy_check_mark: | :heavy_check_mark: | - | - | :heavy_check_mark: | :heavy_check_mark: |


> **Unified Plan** - As of version webrtc-m106 Unified Plan is the only supported mode.  
Those still in need of Plan B will need to use an older release (1.94.1)


## WebRTC Revision

* Currently used revision: [M111](https://github.com/jitsi/webrtc/tree/M111)
* Supported architectures
  * Android: armeabi-v7a, arm64-v8a, x86, x86_64
  * iOS: arm64, x86_64


## Getting Started

Add https://github.com/555platform/react-native-webrtc.git in your package.json under dependencies. Then do npm install.

```json
{
  "dependencies": {
    ...
    "react-native-webrtc": "git+https://github.com/555platform/react-native-webrtc.git#webrtc-m111"
  }
}
```

## Guides

- [Android Install](./Documentation/AndroidInstallation.md)
- [iOS Install](./Documentation/iOSInstallation.md)
- [Basic Usage](./Documentation/BasicUsage.md)
- [Step by Step Call Guide](./Documentation/CallGuide.md)
- [Improving Call Reliability](./Documentation/ImprovingCallReliability.md)

## Example Projects

We have some very basic example projects included in the [examples](./examples) directory.  
Don't worry, there are plans to include a much more broader example with backend included.  
 
