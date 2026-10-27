# Privacy Policy — Haukkuri - Haukkuträkkeri

**App:** Haukkuri - Haukkuträkkeri (`com.softaloossi.haukkuri`)
**Provider:** Softaloossi
**Last updated:** 28 October 2026

This app is designed to be privacy-friendly. It has **no user accounts**, **no
advertising**, **no analytics or tracking**, and we operate **no servers** that
collect or store your personal data. Everything the app does happens on your
device or directly between you and the group members you choose.

## Information the app handles

### Location
With your permission, the app accesses your device's **GPS location** to show
your position on the map and to record your trail. If you join a group, your
latest location is shared **directly, peer-to-peer**, with the other members of
that group so you can see each other on the map. This sharing uses an encrypted
peer-to-peer connection (the Holepunch/Pear distributed network) and does
**not** pass through, or get stored on, any server operated by us. Location data
is only shared while you are an active member of a group; leaving a group stops
the sharing. The app can use location in the background so tracking continues
while the screen is off.

### Microphone
With your permission, the app uses the **microphone** to detect dog barking
on-device using a local sound-classification model. Audio is processed in real
time on your device.

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
to join a group. Camera images are processed on-device and are **not stored or
transmitted**.

### Map tiles (third party)
To display maps, the app requests map imagery over HTTPS from the Finnish
National Land Survey (Maanmittauslaitos). As with any internet request, that
service can see your device's IP address and the map areas requested. We do not
control that service; see the Maanmittauslaitos privacy terms for details. No
other data is sent to it. Your own Maanmittauslaitos API key, if you enter one,
is stored only on your device and is never shared with other users.

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

## Data storage
Group membership, your trails, and app settings are stored **locally on your
device**. You can remove this data by leaving groups or uninstalling the app.

## Data sharing and selling
We do **not** sell your data and do **not** share it with any third party for
advertising or analytics. The only sharing that occurs is the peer-to-peer
location sharing with group members that you explicitly join, and the map tile
sharing described above.

## Children
This app is not directed at children and does not knowingly collect data from
children.

## Your choices
- Location, microphone, and camera access are optional and controlled by Android
  and iOS permissions. You can revoke any of them at any time in your device settings.
- Leaving a group stops sharing your location with its members.
- Map tile channels are opt-in; downloading tiles for others is on by default.
  Leave a channel or turn the setting off at any time in the app settings.
- Uninstalling the app removes the data stored on your device.

## Changes to this policy
If this policy changes, we will update this page and revise the "Last updated"
date above.

## Contact
Questions about this policy? Contact us at rami.ojala@softaloossi.fi.
