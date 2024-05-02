# faves

A Flutter app enabling users to save favorite places on their device while attaching a photo of the said place. Data is persisted using an on-device SQLite database.

## HOW TO USE THE PROJECT ONCE DOWNLOADED
1. Go to the apikeys.dart file under the lib/keys folder and change the value of 'GMAP_API_KEY' to your Google Maps API key.
2. Go the AndroidManifest.xml file under the following folder path: faves/android/app/src/main/ . Add the same Google Maps API key on the following entry (ONLY ADD IT WHERE IT SAYS 'PUT YOUR API KEY HERE'): 
 < meta-data android:name="com.google.android.geo.API_KEY"
                android:value="PUT YOUR API KEY HERE"/>
3. Go the AppDelegate.swift file under the following folder path: faves/ios/Runner/ . Add the same Google Maps API key on the following entry (ONLY ADD IT WHERE IT SAYS 'PUT YOUR API KEY HERE'): 
    GMSServices.provideAPIKey("PUT YOUR API KEY HERE")


