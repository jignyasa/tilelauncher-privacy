---
layout: default
title: Tile Launcher – Privacy Policy
---

# Tile Launcher – Privacy Policy

**Effective date:** October 27, 2026<br>
**Developer:** JYS Studio<br>
**Contact:** [jignyasatandel2380@gmail.com](mailto:jignyasatandel2380@gmail.com)

This Privacy Policy explains how the Tile Launcher app for Android ("Tile Launcher",
"the app", "we", "us") handles information. It applies to the app as distributed on
Google Play under the package name `com.jysstudio.tilelauncher`.

## Summary

- Tile Launcher has **no accounts and no servers of its own**. We do not receive,
  store or have access to your personal data.
- Almost everything the app reads (your apps, contacts, calendar, photos, step count,
  screen time, notification counts) is **processed only on your phone** and never
  leaves it.
- Data leaves your phone in only two cases: the **weather** feature (an approximate
  location sent to Open-Meteo) and **ads** (served by Google AdMob).
- We **do not sell** your data, and we do not run analytics or crash reporting of our own.
- Every sensitive feature is **optional**, is off until you allow it, and can be
  turned off at any time in Android Settings.

## 1. Information processed only on your phone

The features below need a permission or special access that you grant. The data they
read is used only to show it to you inside the launcher. It is **not uploaded to us
or to any third party**, and it is not used for ads.

| Feature | Permission or access | What the app reads | Why |
|---|---|---|---|
| Home grid, app drawer, App Library | Package visibility (installed apps) | Names and icons of apps installed on your phone | To show and launch your apps, the core function of a launcher |
| App shortcuts and pinned shortcuts | Default home app role | Shortcuts that other apps publish | To show them in long-press menus and on your home screen |
| Contacts in search | Contacts (`READ_CONTACTS`) | Names of contacts that match what you type in search | To show matching contacts. Asked for only when you tap "Allow access". |
| Contact tiles | Android contact picker | The contact you choose for a custom tile | To call, message or open that contact when you tap the tile |
| Calendar card (Today view) | Calendar (`READ_CALENDAR`) | Titles and times of today's events | To show your agenda |
| Photo tile and gallery | Photos (`READ_MEDIA_IMAGES`, or selected photos only on Android 14+) | Your recent photos and album names | To show a photo on the tile and let you browse them |
| Steps tile | Physical activity (`ACTIVITY_RECOGNITION`) | The phone's step counter | To show today's step count |
| Screen Time card | Usage access (`PACKAGE_USAGE_STATS`) | How long you used apps today | To show your total screen time |
| Notification badges and WhatsApp tile | Notification access | **Only** which app posted a notification, how many are active, and when the latest WhatsApp notification arrived | To show unread counts on tiles. **Notification titles and text, including message content, are never read or stored.** |
| Badge counts (Samsung phones) | Samsung badge provider | The badge number Samsung shows on an app icon | To keep tile badges in line with the system |
| Double-tap to lock | Accessibility service (see section 4) | **Nothing** | To lock the screen when you double-tap empty space |
| Swipe down for notifications | `EXPAND_STATUS_BAR` | Nothing | To open the notification shade |
| Notifications from the app | `POST_NOTIFICATIONS` | Nothing | To tell you when a cleanup task has finished |
| Weather tile | Approximate location (`ACCESS_COARSE_LOCATION`) | Your approximate location | See section 2. The app never asks for precise location. |

Your home-screen layout, custom tiles, settings and the data above are stored in the
app's private storage on your phone, which other apps cannot read.

## 2. Information that leaves your phone

### Weather (Open-Meteo)

If you use the weather tile and allow approximate location, the app sends your
location, **rounded to about 1 km** (two decimal places), over HTTPS to
[Open-Meteo](https://open-meteo.com) (`api.open-meteo.com`) to get the local
forecast. The request contains no name, account, device ID or advertising ID. Like
any web server, Open-Meteo receives your IP address when the request is made. See the
[Open-Meteo terms and privacy policy](https://open-meteo.com/en/terms).

To show a city name, the app asks Android's built-in geocoder to turn that location
into a place name. On most phones this service is provided by Google and is subject
to the [Google Privacy Policy](https://policies.google.com/privacy).

If you do not allow location, the weather tile simply does not show local weather.

### Advertising (Google AdMob)

The free version of Tile Launcher may show ads served by Google AdMob. It uses
Google's User Messaging Platform (UMP) to ask for consent where the law requires it.
These Google SDKs may automatically collect:

- your device's advertising ID,
- your IP address and the approximate location it implies,
- device and app information (such as model, OS version and language),
- how you interact with ads (views and taps), and diagnostics.

Google uses this information to serve, personalize (where you allow it) and measure
ads, and to prevent fraud. It is processed by Google under the
[Google Privacy Policy](https://policies.google.com/privacy). See also
[how Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites).

- **Consent:** In the European Economic Area, the United Kingdom and Switzerland,
  you are asked for consent before personalized ads are shown. You can change your
  choice at any time from the app's Settings.
- **Opting out of personalized ads:** You can reset or delete your advertising ID,
  or opt out of ad personalization, in Android Settings > Google > Ads (or
  Settings > Privacy > Ads, depending on your phone).

The personal data that the app reads on your phone (section 1) is **never** shared
with Google AdMob or used to target ads.

### Links that open other apps

Some actions hand you over to another app or website, for example web search
(Google), Play Store search, map links, website tiles or opening a WhatsApp chat from
a contact tile. Tile Launcher only opens the link. What happens next is governed by
that app's or website's own privacy policy.

## 3. What we do not do

- We do not create accounts or ask for your name, email or phone number.
- We do not run our own servers, so we do not collect or store your data.
- We do not sell, rent or trade personal data.
- We do not use our own analytics, tracking or crash-reporting tools.
- We do not read the content of your messages or notifications.
- We do not use the Accessibility API to observe your screen or what you type.

## 4. Accessibility service (double-tap to lock)

Tile Launcher includes an optional accessibility service, used **only** for the
"double-tap to lock" gesture on Android 9 and later. Before you are sent to turn it
on, the app explains what it does and asks you to agree.

The service is configured so that it receives **no accessibility events** and **cannot
retrieve window content**. It cannot see what is on the screen, what you type, or
which apps you use. The only thing it does is perform Android's "lock screen" action
when you double-tap empty space on the home screen. No data is collected through it,
and nothing is shared. You can turn it off at any time in Android Settings >
Accessibility.

## 5. Notification access

Notification access is optional and is used only for unread-count badges and the
WhatsApp tile. Before you are sent to grant it, the app explains what it reads. The
app counts active notifications per app and records when the latest WhatsApp
notification arrived. It does not read notification titles, message text or images.
Nothing is stored outside your phone or shared. You can turn it off in Android
Settings > Notifications > Device & app notifications (the exact path varies by phone).

## 6. Backups

- **Android backup:** If Android backup is on, Android may back up your app settings
  (such as theme and grid size) to your Google account. Your home-screen layout
  database and activity-derived data (notification counts, photo and step data) are
  **excluded** from both cloud backup and device-to-device transfer.
- **"Back up layout":** This feature saves a file with your layout, settings, custom
  tiles and hidden-apps list to a location **you choose**. It may include the
  contacts, phone numbers or website addresses you set on custom tiles. We never
  receive this file. Keep it somewhere safe, and delete it when you no longer need it.

## 7. Data retention and deletion

Data that the app stores stays on your phone until you remove it. You can:

- turn off any permission in Android Settings to stop the related feature,
- remove a tile or clear a setting to delete its data, or
- **uninstall the app**, or use Android Settings > Apps > Tile Launcher > Storage >
  Clear data, to delete everything the app has stored.

Because we hold no data about you, there is no server-side data for us to delete.
Data processed by Google (ads, geocoder) and Open-Meteo (weather) is kept under their
own retention policies, linked above.

## 8. Security

Your data stays in the app's private, sandboxed storage on your phone. All network
requests the app makes (weather and ads) use encrypted HTTPS connections. The app asks
for approximate location only, never precise location, and every sensitive
permission can be revoked at any time.

## 9. Your rights

Depending on where you live, you may have rights over your personal data, such as the
right to access, correct, delete or object to its processing, or to withdraw consent.
These include rights under the EU/UK GDPR, the California Consumer Privacy Act
(CCPA/CPRA) and India's Digital Personal Data Protection Act, 2023.

Because Tile Launcher does not collect personal data on any server, you can exercise
most of these rights directly on your phone (section 7). For data collected by Google
for ads, use the controls in section 2 or contact Google. For any question or
request, email us at the address below. We aim to reply within 30 days.

Where the GDPR applies, the legal basis for processing is your **consent** (for
location, ad personalization and each optional permission). For non-personalized
ads, it is our **legitimate interest** in funding the free version of the app.

## 10. Children

Tile Launcher is a general-audience app and is not directed at children under 13
(or the minimum age in your country). We do not knowingly collect personal data from
children. If you believe a child has provided personal data through the app, contact
us and we will help remove it.

## 11. International transfers

Google and Open-Meteo may process data in countries other than your own. They apply
their own safeguards to such transfers, as described in their privacy policies.

## 12. Changes to this policy

If we change this policy, we will post the new version on this page and update the
effective date above. If a change significantly affects how your data is handled, we
will also tell you in the app or in the Google Play release notes.

## 13. Contact

For any question about this Privacy Policy or your data, contact:

**JYS Studio**<br>
Email: [jignyasatandel2380@gmail.com](mailto:jignyasatandel2380@gmail.com)
