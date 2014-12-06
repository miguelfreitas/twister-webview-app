# twister simple webview app

---

= Android Mobile Sample App

This is a very simple app, that uses a webview. It's part of this tutorial: http://dev.tscolari.me/2011/09/19/android-webapp-in-3-minutes/

Note: to build the apk, two additional files are needed:

1) twisterd:
cp ../twister-android/src/twisterd libs/armeabi/libtwisterd.so

2) twister-html:
cd twister-html
git archive --format zip --output ../twister-webview-app/res/raw/html.mp3 master
