# Privacy Policy — Haukkuri - Haukkuträkkeri

**App:** Haukkuri - Haukkuträkkeri (`com.softaloossi.haukkuri`)
**Provider:** Softaloossi
**Last updated:** 29 October 2026

This app is designed to be privacy-friendly. It has **no user accounts**, **no
advertising**, and **no analytics or tracking**. We run **no server that stores
your location or group data**: groups work directly between the devices of the
members you choose. The few things that do leave your device are listed below.

## Information the app handles

### Location
With your permission, the app accesses your device's **GPS location** to show
your position on the map and to record your trail. If you join a group, your
location is shared **directly, peer-to-peer**, with the other members of that
group so you can see each other on the map. This sharing uses an encrypted
peer-to-peer connection (the Holepunch/Pear distributed network) and does
**not** pass through, or get stored on, any server operated by us. Location data
is only shared while you are an active member of a group; leaving a group stops
the sharing. The app can use location in the background so tracking continues
while the screen is off.

Groups are mutual location sharing: the group features are available only while
the app has permission to use your location, so nobody can follow the others
without being visible to them. The map works without location.

### What group members see
When you are a member of a group, its other members' devices receive and store:

- the **name** you set and whether the device is a person or a dog;
- your **position**, speed and direction, and your **recorded trail**;
- your device's **battery level**;
- **barks** detected on a dog's phone, with the place they were detected;
- **stands** (passipaikat) and **areas** you add to the group, and the weather
  forecasts your device fetched for the group.

Members you connect with, and the nodes of the public peer-to-peer network the
app uses to find them, can see your device's **IP address**. They cannot read the
group's content, which travels encrypted.

Information already shared with a group stays on the other members' devices
after you leave the group; we cannot delete it from their devices.

### Microphone
With your permission, the app uses the **microphone** to detect dog barking
on-device using a local sound-classification model. Audio is processed in real
time on your device and is never transmitted.

Optionally (a per-device setting that is off by default and that you can turn on in the app's settings),
when a bark is detected the short (~1 second) audio clip that triggered the
detection is saved **only on that device** so it can be reviewed afterwards.
Saved clips are kept until you remove them; you can play or delete individual
clips, clear them all, or export them as a single ZIP file into the device's
Documents folder, from the app's settings. These clips are **never transmitted**
anywhere and never leave the device unless you copy the exported archive off it
yourself.

### Camera
With your permission, the app uses the **camera** solely to scan QR codes used
to join a group or a map tile channel. Camera images are processed on-device and
are **not stored or transmitted**.

### Map tiles (third parties)
To display maps, the app requests map imagery over HTTPS from the Finnish
National Land Survey (Maanmittauslaitos). As with any internet request, that
service can see your device's IP address and the map areas requested. We do not
control that service; see the Maanmittauslaitos privacy terms for details. No
other data is sent to it. Your own Maanmittauslaitos API key, if you enter one,
is stored only on your device and is never shared with other users.

If you choose the OpenStreetMap base map, or when a Maanmittauslaitos map square
cannot be loaded, the app loads map squares from **OpenStreetMap**'s tile servers
(OpenStreetMap Foundation). If you turn on
the **Suomen riistakeskus** map layers, the app requests them from
`kartta.riista.fi`. Like Maanmittauslaitos, these services can see your device's
IP address and the map areas requested, and no other data is sent to them.

To reduce those requests, devices also share already-downloaded **map tiles**
directly, peer-to-peer, with members of the groups you have joined and, only if
you join one, a **map tile channel** (a code shared between trusted groups, e.g.
a club). Only map images are exchanged on a tile channel — no location or other
group data — but its members can see which map areas your device asks for. If
you turn on **"Hae puuttuvat karttaruudut ryhmälle"**, your device may also
download map tiles from Maanmittauslaitos with your own API key on behalf of
those members; Maanmittauslaitos then sees your device's IP address for those
requests. This is on by default once you have saved a key — also over mobile
data, except on a phone set up as a dog's (collar) phone — and can be turned off
at any time.

### Wind and terrain (third party)
When you turn on the wind arrows, the app asks the Finnish Meteorological
Institute (Ilmatieteen laitos) for the weather forecast at points across the
visible map area. For the scent plume it also asks for the forecast at your
position, and asks Maanmittauslaitos for terrain heights around it (with your
own API key, if you have one). Those services can see your device's IP address
and these coordinates; no name, identifier or other data is sent. We do not
control those services. The forecasts are also shared peer-to-peer with the
members of the groups you have joined, so their devices need not fetch the same
data.

### App configuration
When it starts and when you return to it, the app downloads a small
configuration file from our website, `softaloossi.fi` (for example whether a
subscription is required and the oldest supported app version). Like any web
request, the server sees your device's IP address. No other data is sent, and we
do not use these requests to identify you.

### Problem reports
If you send a report from **"Raportoi ongelma"**, it is submitted through
**Google Forms** (Google) and stored in our report spreadsheet and issue tracker.
A report contains the report type, your description, the app version, the
operating system version and the device model. Unless you untick **"Liitä
vianetsintälokit"**, it also contains the app's diagnostic log: app events and
errors, with any positions **rounded to about 1 km**, and group invitations,
recovery codes, channel codes and API keys masked. Please do not write personal
information in the description. Google processes the submission under its own
privacy policy.

We use reports only to fix problems and improve the app, and delete them when
they are no longer needed for that. You can ask us to delete a report you sent
(see Contact).

**"Lataa lokit"** only saves or shares the diagnostic log where you choose to
send it; nothing is sent by the app. That export keeps positions at full
precision, so check it before sharing.

### Subscriptions
Subscriptions are bought through **Apple's App Store** or **Google Play**. The
store handles payment; we receive no payment details. The app checks your
subscription status with the store on your device.

### Links
Links in the app to YouTube, Facebook and our documents open in your browser or
those apps; their own privacy policies apply there.

## Data storage and deletion
Group membership, your trails, bark clips and app settings are stored **locally
on your device**. Leaving a group stops sharing with it; uninstalling the app
removes the data stored on your device. Information already shared with a group
remains on its other members' devices (see *What group members see*). Problem
reports are kept as described above and deleted on request.

## Data sharing and selling
We do **not** sell your data and do **not** share it with any third party for
advertising or analytics. Data leaves your device only as described above: to
the members of groups and tile channels you join, to the map and weather
services that deliver what you view, to our configuration file server, and to
Google Forms when you send a problem report.

## Children
This app is not directed at children and does not knowingly collect data from
children.

## Your choices
- Location, microphone, and camera access are optional and controlled by Android
  and iOS permissions. You can revoke any of them at any time in your device
  settings. Without location, the group features are unavailable.
- Leaving a group stops sharing your location with its members.
- Map tile channels are opt-in; downloading tiles for others is on by default.
  Leave a channel or turn the setting off at any time in the app settings.
- A problem report includes the diagnostic log only if you leave
  "Liitä vianetsintälokit" ticked.
- Uninstalling the app removes the data stored on your device.

## Changes to this policy
If this policy changes, we will update this page and revise the "Last updated"
date above.

## Contact
Questions about this policy, or a request to delete a problem report you sent?
Contact us at rami.ojala@softaloossi.fi.
