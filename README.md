# XcodeExtensionSample

Xcode Source Editor Extension is strictly restricted in its sandbox.
This project introduces the way to jump over the barrier.

Associated presentation: Xcode Source Editor Extensionの世界 (Japanese)
https://speakerdeck.com/takasek/20170916-number-iosdc

## This extension includes example commands which realize:

- Pasteboard as input
- Pasteboard as output
- Another App as output
- Another App as output using URL scheme
- Linux command execution
- Network connection
- Linux command execution beyond Sandbox using XPC
    - not worked yet I don't know why... any advices are welcome!
    - refer to another worked example at https://github.com/norio-nomura/SwiftLintForXcode
- GUI presentation with the bundled App

## Language Version

Swift 4

## Refered to

Using and Extending the Xcode Source Editor - WWDC 2016 - Videos - Apple Developer 
https://developer.apple.com/videos/play/wwdc2016/414/

Cocoa Interprocess Communication with XPC - WWDC 2012 - Videos - Apple Developer 
https://developer.apple.com/videos/play/wwdc2012/241/

## License

MIT
