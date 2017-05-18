# RSLoadingView

## Introduction

`RSLoadingView` bring your app to the new age of loading animations using 3D engine.
- Written with Swift
- Customizable
- Using Apple's SceneKit with OpenGL
- Include HUB feature: show full screen loading HUB with one line of code
- Or use as standalone view
- Configurable in interface builder

## Requirements
- Swift 3.2
- iOS 9+

## Demo
SpinAlone - Base Variant
![SpinAlone Base Variant](./screenshots_normal.png "SpinAlone Base Variant")

## Installation
RSLoadingView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "RSLoadingView"
```

## Customization
##### Loading View Related
| Field | Default Value |
| ------ | ------ |
| speedFactor | 1.0 |
| mainColor | UIColor.white |
| colorVariation | 0.0 |
| sizeFactor | 1.0 |
| spreadingFactor | 1.0 |
| lifeSpanFactor | 1.0 |
| variantKey | "" |
##### HUB Related
| Field | Default Value |
| ------ | ------ |
| shouldDimBackground | true |
| dimBackgroundColor | UIColor.black.withAlphaComponent(0.6) |
| isBlocking | true |
| shouldTapToDismiss | false |
| sizeInContainer | CGSize(width: 180, height: 180) |

## Author

Roy Ng, roytornado@gmail.com
@ Redso, https://www.redso.com.hk/

## License

RSLoadingView is available under the MIT license. See the LICENSE file for more info.

