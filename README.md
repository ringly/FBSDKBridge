# FBSDKBridge

This repository contains an Xcode workspace that references the Facebook frameworks with [CocoaPods](https://github.com/CocoaPods/CocoaPods), then shares the generated schemes, allowing them to be used with [Carthage](https://github.com/Carthage/Carthage).

Facebook doesn't support Carthage for their SDKs, so we need to do this to use the Facebook frameworks without using two separate dependency managers.
