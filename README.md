# EditText-with-Border
Customize EditText Android

You can save this code in drawable folder on Android Studio

<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="rectangle">
    <gradient
        android:angle="270"
        />
    <corners android:radius="0dp" />

    <stroke
        android:width="2dp"
        android:color="#000000" />

</shape>

After create it, you can attach in your layout xml using "android:background="@drawable/edit_text_border""

