# Run Xcode Archive step

Entirely the same as the [original step provided by Bitrise](https://github.com/bitrise-steplib/steps-xcode-archive) except that this step doesn't provide the `-destination` flag to `xcodebuild` by default wich allows the `-arch` flag to be set.
