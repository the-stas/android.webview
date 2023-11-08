```xml
    <uses-feature
        android:name="android.hardware.camera"
        android:required="true" />

    <uses-permission android:name="android.permission.INTERNET"></uses-permission>
    <uses-permission android:name="android.permission.CAMERA"></uses-permission>
    <uses-permission android:name="android.permission.RECORD_AUDIO"></uses-permission>
    <uses-permission android:name="android.permission.MODIFY_AUDIO_SETTINGS"></uses-permission>
```


+ java

```java
webView.getSettings().setMediaPlaybackRequiresUserGesture(false);
```
