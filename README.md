
![android_undercovewr](https://user-images.githubusercontent.com/123765654/234373954-eecb21ac-30d4-4d22-bc55-43944117e332.jpg)


# Android Undercover
During this talk, I dive into how native code is used as an effective obfuscation technique. Implementing partial or fully-native Android application code creates challenges for reverse engineers and antiviruses. We will explore the techniques for writing native code and watch as the new app goes undetected. Then I will demonstrate how to reverse engineer and thwart an application using this obfuscation method.

## Required Software
If you want to follow along during the talk, make sure you have the following tools and code downloaded:

- [JADX](https://github.com/skylot/jadx)
- [Android Studio](https://developer.android.com/studio)
  - Make sure the NDK is installed [Install ![Uploading Ft9HfijWwAEP6dC.jpg…]()
and configure the NDK and CMake](https://developer.android.com/studio/projects/install-ndk)
- [Ghidra](https://ghidra-sre.org/)

## Link References

### Anubis Sample Links
- Partial Anubis APK source code: PartialAnubis_source.zip (in repo)
- Partial Anubis compiled APK: PartialAnubis_apk.zip (in repo)
- Full Android Anubis source code (Android.Anubis.b.7z): 

  - https://github.com/vxunderground/MalwareSourceCode/tree/main/Android\

- Password: infected

### Java Native Interface (JNI)
- [JNI Functions](https://docs.oracle.com/javase/7/docs/technotes/guides/jni/spec/functions.html)
- [JNI Types and Signatures](https://docs.oracle.com/javase/8/docs/technotes/guides/jni/spec/types.html#type_signatures)
