# Epic Ride Weather for Karoo Beta
Welcome to the beta for Epic Ride Weather for Karoo, an extension for the Hammerhead Karoo device that brings personalized weather forecasts to your ride.

This extension features a Wind Conditions tile for Karoo's in-ride data pages. When in a ride following a route, the tile displays the current wind conditions, as well as the upcoming wind conditions and when they will change. This will allow you to make informed decisions about exertion through different stages of your ride.

The Wind Conditions tile has two modes:
- When placed in a large grid tile, it shows wind conditions for current and upcoming segments of the ride.
- When placed iin a small grid tile, it only shows wind conditions for the current segment of the ride.

In the display for each wind segment, the arrow indicates the wind direction relative to your average heading for that section of the ride. In the screenshot below, the relative wind direction changes suddenly between segments because of a left turn in the route ahead.

The number in the center of the display shows the average wind speed for that segment, in the unit specified in the bottom corner.

The time in the upper right corner shows the estimated duration of the segment based on your average speed. The time for the current segment will count down as you ride.

<img src="/images/Screenshot_20250206_150531.png" width="240" height="400"><img src="/images/Screenshot_20250206_150353.png" width="240" height="400">

Any bug reports or feedback is greatly appreciated. Please submit feedback to the Issues tab on this website, or email James at james@epicrideweather.com.

Epic Ride Weather for Karoo is available to subscibers of the Epic Ride Weather app for android/ios. You can get the app with [this link](https://www.epicrideweather.com/get-app/).

## Installation
Follow the instructions below, or the [sideloading guide](https://support.hammerhead.io/hc/en-us/articles/31576497036827-Companion-App-Sideloading) from Hammerhead.

- Open this page on your smartphone with the Hammerhead Companion app installed.
- Navigate to the [releases]() page.
- Depending on your device type:<br>
&nbsp;**Karoo 3:**
Long press on ``app-release.apk``.<br>
&nbsp;**Karoo 2:**
Download ``app-release.apk``, then locate and long press on the downloaded file.
- Open the share menu, and select the Hammerhead Companion app.
- The Hammerhead Companion app will open and start uploading the file to your Karoo.
- Once completed, tap ``install`` on your Karoo device.

## Setup
Opening the app on your Karoo for the first time will walk you through a simple setup process. More detailed instructions are below.

### Prerequsites
- A smartphone with Epic Ride Weather installed
- An subscription for Epic Ride Weather
- An internet connection
- The Epic Ride Weather extension installed on your Karoo (see above)

### Steps
- Open Epic Ride Weather on your Karoo from the extensions library.
- Tap on the ``Sync Account`` button, and scan the QR code on your smartphone.
- The Epic Ride Weather app should open on your phone.
  - If you are taken to the website, follow the instructions there to open the app.
- Tap ``Add Device`` on your phone.
- Tap ``Done`` on your Karoo.
- Add a "Wind Conditions" data tile to your ride profile.
- Start a ride following one of your saved routes.

## Troubleshooting
Sometimes the Wind Conditions tile might display a message, indicating that it needs conditions to be met before it can show wind data. Here are some messages you might see:
### No Internet
To recieve weather forecasts, make sure that your Karoo is either paired to your phone via the Hammerhead Companion app or connected to the internet through other means. Karoo devices automatically turn off wifi when starting a route to save power, so if you're relying on wifi, you'll need to turn it back on.
### No Route
The extension will only show weather conditions if you are following a route in your ride. To follow a route, navigate to the Routes page, select your desired route, and tap ``Follow`` or on the checkmark button.
### Check Account
You need a synced Epic Ride Weather account to use the extension. This message indicates that either your account is not synced or you subscription is no longer valid. If you think this is a mistake, first try re-syncing your account by following the setup instructions above, then contact support if the issue persists.
### Other Issues
If you've addressed the problems described above and the display still shows the error message, try restarting your ride. If the extension makes enough unsuccessful requests during a ride, it will stop trying to save on battery.

If you are still having trouble or if you find a bug, don't hesitate to contact support at james@epicrideweather.com
