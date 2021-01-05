# Android C++ Command Line NDK

Serve a creare velocemente un helloworl in c usabile da shell android

Installare SDK e NDK (si fa prima da android studio)

Per compilare:
```
cd project/
export NDK_PROJECT_PATH=.
export NDK_APPLICATION_MK=./Application.mk
export APP_BUILD_SCRIPT=./Android.mk
export PATH="da qualche parte/sdk/ndk/22.0.7026061/:$PATH"
ndk-build
```

`/sdcard/` has `noexec` flag, use another dir

## Source
https://software.intel.com/content/www/us/en/develop/articles/building-an-android-command-line-application-using-the-ndk-build-tools.html

http://alokprasad7.blogspot.com/2019/01/pure-c-program-native-command-line-on.html

https://android.stackexchange.com/questions/35658/adb-permission-denied-to-run-a-configure-file
