# rekotlin-multiplatform
Experimental conversion of [ReKotlin](https://github.com/ReKotlin/ReKotlin)
to multiplatform library

Currently builds .jar for JVM/Android and .framework for iOS.

## Building

Run `./gradlew clean build`

- iOS frameworks will be located at `build/bin/ios/main/`
- JVM .jar file will be present at `build/libs/` along with metadata
.jar file for multiplatform projects

## TODO
A lot!
