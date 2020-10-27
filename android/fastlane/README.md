fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## Android
### android test
```
fastlane android test
```
Runs all the tests
### android write_to_env
```
fastlane android write_to_env
```
Add env variables
### android build_staging
```
fastlane android build_staging
```
Build application staging release
### android build
```
fastlane android build
```

### android dev
```
fastlane android dev
```
Deploy to Firebase internal developer/tester group
### android staging
```
fastlane android staging
```

### android publish_to_firebase
```
fastlane android publish_to_firebase
```
Deploy to Firebase

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
