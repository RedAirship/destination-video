# Destination Video

This app is a multiplatform video playback app for visionOS, iOS, and tvOS. It demonstrates how to use the unique features of Apple Vision Pro to create an immersive playback experience that leverages 3D video and spatial audio.

For more information about the app and how it works, see
[Destination Video](https://developer.apple.com/documentation/visionos/destination-video) in the developer documentation.


# RedAirship
Apple's multi-platform demo as found at this link: https://developer.apple.com/documentation/visionos/destination-video. This one app runs on these 4 platforms: `visionOS`, `iOS`, `ipadOS`, and `tvOS`. This project highlights how little code is necessary to code a multiplatform app using `SwiftUI`. 

- Total lines of code: `2047`
- visionOS lines of code: `334`, `16%`
- iOS (and ipadOS) lines of code: `97`, `4%`
- tvOS lines of code: `55`, `2%`
- `78%` of the code is used by all 4 platform variants of the app!

The app uses little UIKit objects, 4 to be precise: 4 properties, and 1 method property:
- Video.swift for a UIImage property
- VideoWatchingActivity.swift for a CGImage property
- PlayerModel.swift uses a UIViewControllerTransitionCoordinator
- SystemPlayerView.swift uses a UIViewController, a UIAction

Commiting this repository to our company's Github space as a good example app to encourage us to start adopting SwiftUI.
