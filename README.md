# LiquidTabBar

[![Swift 5.2](https://img.shields.io/badge/Swift-5.2-green.svg?style=flat)](https://developer.apple.com/swift/)

![Animation](https://raw.githubusercontent.com/Cuberto/liquid-tabbar/master/Screenshots/animation.gif)

## Requirements

- iOS 11.0+
- Xcode 11

## Example

To run the example project, clone the repo, and open `LiquidTabBar.xcodeproj`

## Installation

Add content of `Classes` folder to your project

## Usage

### With Storyboard

1. Create a new UITabBarController in your storyboard or nib.

2. Set the class of the UITabBarController to `CBLiquidTabBarController` in your Storyboard or nib. 

3. Add a custom icon for UITabBarItem of each child ViewContrroller

4. If you need cutom bar animation color for each tab set `CBLiquidTabBarItem` class to tab bar items and use `barAnimationColor` property  

### Without Storyboard
1. Instantiate `CBLiquidTabBarController`
2. Add some child conrollers and don't forget to set them tabBar items with an image
3. If you need cutom bar animation color for each tab set `CBLiquidTabBarItem` class to tab bar items and use `barAnimationColor` property  

## Author

Cuberto Design, info@cuberto.com

## Source Code
You can find the source code [here](https://www.patreon.com/posts/39310865)
