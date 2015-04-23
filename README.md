# BAHFourCornersController

[![CI Status](http://img.shields.io/travis/BHughes3388/BAHFourCornersController.svg?style=flat)](https://travis-ci.org/BHughes3388/BAHFourCornersController)
[![Version](https://img.shields.io/cocoapods/v/BAHFourCornersController.svg?style=flat)](http://cocoapods.org/pods/BAHFourCornersController)
[![License](https://img.shields.io/cocoapods/l/BAHFourCornersController.svg?style=flat)](http://cocoapods.org/pods/BAHFourCornersController)
[![Platform](https://img.shields.io/cocoapods/p/BAHFourCornersController.svg?style=flat)](http://cocoapods.org/pods/BAHFourCornersController)

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

Runs smooth on IOS 8

Needs a little work to orientation detection to work on < IOS 8

## Installation

BAHFourCornersController is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "BAHFourCornersController"
```

## Setup

Import ```Objective-C #import "BAHFourCornersViewController.h" ```

get recerence to BAHFourCornersViewController or initalize and add to Self.window.rootViewController
```Objective-C
BAHFourCornersViewController *fourCorners = (BAHFourCornersViewController*)Self.window.rootViewController;
```

Build your view controllers and set them to the corner you want with
```Objective-C
[fourCorners setTopLeftViewController:UIViewController];
```

Build you buttons and add them using
```Objective-C
fourCorners.topLeftButton = button1;
```

Look at the DemoApp AppDelegate.m for more setup configurations to the buttons including button size, insets, image insets, and more.


## Author

BHughes3388, BHughes3388@gmail.com

## License

BAHFourCornersController is available under the MIT license. See the LICENSE file for more info.
