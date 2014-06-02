# SWFrameButton

This UIButton subclass replicate single line border button see in iOS 7 App Store.

## Installation

SWFrameButton is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

    pod "SWFrameButton"

## Requirements

Requires iOS 7.0+ and ARC.

## Usage

`SWFrameButton` design to use `tintColor` to determine its color, so try to avoid set text color by `setTitleColor:forState:` it won't break your button, but may raise inconsistent highlighted/selected color state. `Text Color` property in Interface Builder will be ignore for this reason, use `Tint` property in view section instead.

If you use Interface Builder, add a UIBUtton to your interface and set Class to `SWFrameButton`.

![Use with storyboard](/Documentation/Images/use-with-storyboard.png)

## Author

[Sarun Wongpatcharapakorn](https://github.com/sarunw)

[@sarunw](https://twitter.com/sarunw)

## License

SWFrameButton is available under the MIT license. See the LICENSE file for more info.
