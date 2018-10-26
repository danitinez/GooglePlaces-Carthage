This is a fork from  https://github.com/leoneparise/GooglePlaces-Carthage repositorie. I have updated it to last 2.7 version.

### Installation with Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks.

You can install Carthage with [Homebrew](http://brew.sh/) using the following command:

```bash
$ brew update
$ brew install carthage
```

To integrate AFNetworking into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "danitinez/GooglePlaces-Carthage" ~> 2.7.0
```

Run `carthage update --platform ios` to build the framework and drag the built `Google*.framework` into your Xcode project.
