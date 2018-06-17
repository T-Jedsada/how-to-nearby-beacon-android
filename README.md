# Setup Eddystone for Android

- **Step 1:** Get a beacon

    Eddystone beacons from these manufacturers will work well with all Google products that support beacons. [read more](https://developers.google.com/beacons/eddystone#beacon_manufacturers)

    ![string](image//product.png)

- **Step 2:** Download Application Config Beacon

    You must register beacon for Google Service Nearby in this application
    ([Beacon Tools](https://play.google.com/store/apps/details?id=com.google.android.apps.location.beacon.beacontools))

- **Step 3:** Configuration Nearby Notification

    You can set up URL and content notification nearby for your beacon on [Beacons Dashboard](https://developers.google.com/beacons/dashboard/)

- **Step 4:** Enable Mode Nearby

    Finally, you must enable nearby mode on your mobile (Android) **Setting -> Google -> Nearby**

    **Result:** you can see beacon contents or nearby places that don't show via notification, So you must change the priority. 👇

    ![string](image//step-setting.png)