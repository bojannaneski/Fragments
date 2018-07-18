## Fragments
Simple example of fragments in Android</br>

Only what I would mention is while importing Fragments in Android studio by default was importing </br><b>import android.app.Fragment</b> support library, which is native version of the Android SDK that was introduced in Android 3 (API 11), and it was giving me issues of no compatibility.</br>

![fragment_2](https://user-images.githubusercontent.com/15215620/42882089-c60c61e6-8a98-11e8-9f63-2452a690c128.jpg) </br>

Instead, it should be imported newer version <b>import android.support.v4.app.Fragment</b>,  which is a compatibility package that allows you to use some of the newer features. </br>

![fragment_1](https://user-images.githubusercontent.com/15215620/42881733-5bec5d66-8a98-11e8-8af4-f5ea59b54120.jpg) </br>
