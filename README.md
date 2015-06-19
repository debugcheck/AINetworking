
[![Build Status](https://travis-ci.org/Alamofire/Alamofire.svg)](https://travis-ci.org/Alamofire/Alamofire)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)


## AINetworking
A delightful iOS and OS X networking framework.

## Features

- Chainable Request / Response methods
- URL / JSON / plist Parameter Encoding
- Upload File / Data / Stream
- Download using Request or Resume data
- Authentication with NSURLCredential
- HTTP Response Validation
- Progress Closure & NSProgress
- cURL Debug Output

## Requirements

- iOS 8.0+ / Mac OS X 10.11
- Xcode 7.0 beta


## Communication

- If you **need help**, use [Stack Overflow](http://stackoverflow.com/questions/tagged/alamofire). (Tag 'alamofire')
- If you'd like to **ask a general question**, use [Stack Overflow](http://stackoverflow.com/questions/tagged/alamofire).
- If you **found a bug**, open an issue.
- If you **have a feature request**, open an issue.
- If you **want to contribute**, submit a pull request.

## Installation

> **Embedded frameworks require a minimum deployment target of iOS 8 or OS X Mavericks.**
>
> To use AINetworking with a project targeting iOS 8, you must include all Swift files located inside the `Source` directory directly in your project. See the ['Source File'](#source-file) section for additional instructions.

### CocoaPods

[CocoaPods](http://cocoapods.org) is a dependency manager for Cocoa projects.

CocoaPods 0.36 adds supports for Swift and embedded frameworks. You can install it with the following command:

```bash
$ gem install cocoapods
```

To integrate Alamofire into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

pod 'AINetworking', '~> 1.0.1'

```

Then, run the following command:

```bash
$ pod install
```

## End
Thanks for [Alamofire Github](https://github.com/Alamofire)

## License

AINetworking is released under the MIT license. See LICENSE for details.


