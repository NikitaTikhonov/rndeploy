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
## iOS
### ios test
```
fastlane ios test
```
Runs all the tests
### ios write_to_env
```
fastlane ios write_to_env
```
Add env variables
### ios adhoc
```
fastlane ios adhoc
```
Ad-hoc build
### ios adhoc_staging
```
fastlane ios adhoc_staging
```

### ios te
```
fastlane ios te
```

### ios dev
```
fastlane ios dev
```
Deploy to Firebase internal tester group
### ios staging
```
fastlane ios staging
```

### ios publish_to_firebase
```
fastlane ios publish_to_firebase
```
Deploy to Firebase

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
