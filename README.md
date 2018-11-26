# rekotlin-multiplatform
Experimental conversion of [ReKotlin](https://github.com/ReKotlin/ReKotlin)
to multiplatform library

## Integration

Add following maven repository

```gradle
maven {
    url "https://dl.bintray.com/rekotlin/rekotlin-multiplatform/"
}
```

Common
```gradle
implementation 'org.rekotlin:rekotlin-multiplatform-metadata:0.0.1'
```

Android/JVM
```gradle
implementation 'org.rekotlin:rekotlin-multiplatform-jvm:0.0.1'
```

iOS
```gradle
implementation 'org.rekotlin:rekotlin-multiplatform-ios-sim:0.0.1'
```

## Building

Run `./gradlew clean build`

- iOS frameworks will be located at `build/bin/ios/main/`
- JVM .jar file will be present at `build/libs/` along with metadata
.jar file for multiplatform projects

## TODO
- Figure out publishing library for both iOS simulator and phone.
- Add sample
