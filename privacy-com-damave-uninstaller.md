# Privacy Policy for Uninstaller: Remove Many Apps

_Last updated: 2 October 2026_

Uninstaller helps you remove several apps at once. It has no account, no sign-in, no analytics and no advertising. The app itself never sends information about you or your apps off your device. The only network traffic comes from Google Play Billing, used if you choose to buy or restore Uninstaller Pro.

## What the app reads, and where it stays

**Your list of installed apps.** To show the apps you can uninstall, the app reads the names, icons, sizes and install dates of apps that have a launcher icon. This is read on your device, shown on your screen, and never transmitted or stored elsewhere.

**Your home screen layout (optional, Pro).** Android does not share home screen layouts with other apps. If you choose to use the "Home screens" order, you can turn on the app's accessibility service, *Uninstaller – home screen order*. It does nothing until you tap **Scan home screens**. When you do, it:

- opens your home screen and pages through it once;
- reads only the names and on-screen positions of app icons on those pages;
- saves a list of which app sits on which screen, in which position, in the app's private storage on your device;
- then returns you to the app.

It does not read the content of any other app, notifications, text you type, passwords or anything else, and it is not active at any other time. The saved layout never leaves your device. You can turn the service off at any time in **Settings → Accessibility**, and uninstalling Uninstaller deletes the saved layout.

**Your preferences.** Your chosen sort order and whether you own Pro are saved in the app's private storage on your device.

## Purchases

Uninstaller Pro is an optional one-time in-app purchase handled entirely by Google Play. When you buy or restore Pro, the app uses the Google Play Billing library to ask Google Play whether you own Pro. Payment details are handled by Google and are never seen by the app or the developer. Google provides the developer with standard order records (for example, an order number, date, country and price) as it does for every Play purchase. Google's handling of this data is covered by the [Google Privacy Policy](https://policies.google.com/privacy).

## Permissions this app requests

- **REQUEST_DELETE_PACKAGES**: Asks Android to uninstall an app when you choose to remove one. Android shows its own confirmation for each app. The system, not this app, performs the removal.
- **Accessibility service (BIND_ACCESSIBILITY_SERVICE)**: Optional. Used only for the home screen scan described above, only when you start it.
- **com.android.vending.BILLING**: Lets the app offer the optional Pro purchase through Google Play.
- **INTERNET** and **ACCESS_NETWORK_STATE**: Added by the Google Play Billing library so it can reach Google Play for purchases. The app does not use them for anything else.
- **DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION**: An internal Android safeguard that stops other apps from sending messages to this app's internal components. It grants no access to your data.

## Data sharing

The developer does not collect, sell or share any personal data. Nothing the app reads about your apps or home screens is transmitted. Purchase records are handled by Google as described above.

## Data deletion

All data the app keeps is on your device. Uninstalling the app deletes it. Clearing the app's storage in Android Settings deletes it too.

## Children

This app is not directed at children under 13 and does not knowingly collect personal information from them.

## Changes

If this policy changes, the revised version will be posted at this URL with an updated date above.

## Contact

Questions about this policy: open an issue at https://github.com/deVirtuoso/app-privacy-policies/issues
