# opencv-android
[![](https://jitpack.io/v/d-kicinski/opencv-android.svg)](https://jitpack.io/#d-kicinski/opencv-android)

OpenCV for Android but packaged.

No idea why they won't push it do maven repository. I hope that I'm not breaking their license or something :thinking:

### Usage

1. Add jitpack package index 
```groovy
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```

2. Add opencv as dependency to your module.
```groovy
dependencies {
	        implementation 'com.github.d-kicinski:opencv-android:v4.4.0'
	}
```
