# KakaoOpenSDK-SPM

###### ![Swift](https://img.shields.io/badge/Version-2.8.4-bright%20green)![Swift](https://img.shields.io/badge/platform-iOS-orange)

#### KakaoSDK V2를 Swift Package Manager로 사용하기 위한 Repository 입니다.  
v2.8.3 이후 변동내역이 많아져 기존에 사용되던 repository를 대신하여 새롭게 작성하였습니다.
https://github.com/fbdlrghks123/KakaoSDK_SPM.git


## Requirements
- iOS 11+ (소스코드에 UIKit만 존재하여 iOS만 지원하도록 처리함)
- Xcode 11+

## Installation

#### Swift Package Manager

```swift
dependencies: [
    .package(url: "https://github.com/gwonii/KakaoOpenSDK-SPM.git", .upToNextMajor(from: "2.8.3"))
]
```