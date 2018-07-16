Repro case for https://github.com/firebase/firebase-ios-sdk/issues/1341

##Steps to reproduce
1. Copy `GoogleService-Info.plist`.
2. `pod update` and run from XCode -- it should be enough to trigger the crash
3. Note that the `Podfile` gets Firebase pods from Github.
