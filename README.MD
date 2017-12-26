Installation
==
```
cordova plugin add cordova-plugin-android-fragmentactivity
```

Usage
==
No manual configuration required.

How it works
==

This plugin comes bundled with a CordovaFragment (which is a Fragment similar to CordovaActivity) and a MainActivity that extends AppCompatActivity and adds CordovaFragment using FragmentTransactions.

AndroidManifest.xml is automatically updated to use the new MainActivity.

Credits
==
Based on cordova-android-fragments (https://github.com/rajivnarayana/CordovaFragments)