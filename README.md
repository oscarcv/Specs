# Carthage Specifications

There are some great frameworks out there, but unfortunately not all of them offer [Carthage](https://github.com/Carthage/Carthage) support. Luckily there is an easy workaround to include raw frameworks in your project. It works by hosting a JSON file that provides a mapping between the versions and the matching urls of the framework. After that, all you have to do is to refer to that JSON url in your Cartfile.

This repository was set up in an effort to centralize these JSON files.

## Frameworks

### OpenTok
The OpenTok iOS SDK lets you use OpenTok-powered video sessions in apps you build for iPad, iPhone, and iPod touch devices..<br>
Website: [https://tokbox.com/developer/sdks/ios/](https://tokbox.com/developer/sdks/ios/)

| Platform | Lines to add to your Cartfile |
| -------- | -------- |
| iOS      | `binary "https://oscarcv.github.io/Specs/Carthage/iOS/OpenTok.json"` |

## Contribute

If you want to add a popular framework to this list or if you notice that one of the JSON files is outdated, feel free to drop me a [pull request](https://github.com/oscarcv/Specs/pulls) and I'll merge it in.


