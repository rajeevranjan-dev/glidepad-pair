# GlidePad Pair

A small free app for Fire TV that pairs your Android phone with the TV, so GlidePad on your phone can be the TV's mouse, keyboard and remote.

Fire TV won't pair with a phone from its own Bluetooth settings: it hides phones from its list and refuses a pairing the phone starts. GlidePad Pair makes the TV start the pairing instead.

## What you need

- GlidePad on your Android phone.
- A Fire TV with **Fire OS 7 or newer**. To check, open Settings › My Fire TV › About on the TV: it says "Fire OS" and the version. Older Fire TVs (Fire OS 5 or 6) can't install it, and Fire TVs with **Vega OS** can't install apps from outside the Appstore, so neither can run GlidePad Pair.
- Tested on a Fire TV Stick 4K Plus with Fire OS 8. Other Fire TVs with Fire OS 7 or newer should work, but haven't been tested yet.

## Install

1. On the Fire TV, install **Downloader** from the Appstore.
2. Let Downloader install apps: open Settings › My Fire TV › About and select your TV's name 7 times, until it says you're a developer. Go Back, then open Developer options › Install unknown apps and turn on Downloader.
3. Open Downloader and enter the code **5470148**. If the code doesn't work, enter this address instead:
   `https://github.com/rajeevranjan-dev/glidepad-pair/releases/latest/download/glidepad-pair.apk`
4. Select Install, then Open.

## Pair your phone

1. On your phone, open GlidePad › Pair new computer › Fire TV, and tap Make visible.
2. On the TV, open GlidePad Pair. Type the start of your phone's name, as GlidePad shows it, then select Find my phone.
3. Select OK. Check both screens show the same code, then choose Pair on both within 30 seconds. The TV doesn't need your contacts, so you can untick that on your phone.
4. GlidePad connects by itself.

If your phone doesn't show up, tap Make visible in GlidePad again and select Try again on the TV.

## Unpair

Remove the TV in your phone's Bluetooth settings. Fire TV's own settings don't list phones. To pair again later, run GlidePad Pair again: it replaces the TV's old pairing.

## Privacy

GlidePad Pair has no internet permission. It collects, stores and sends nothing. It uses Bluetooth only to find your phone and start the pairing.

## Versions

| Version | Date | Notes |
|---|---|---|
| 1.0.1 | 2026-10-10 | Sends a blocked Bluetooth permission to Settings, finishes replacing an old pairing more reliably, no longer closes if the system's dialog can't open, and matches names with accents in any case. Installs over 1.0.0 with the same code. |
| 1.0.0 | 2026-10-10 | First release. Fire TV with Fire OS 7 or newer. |

The APK is signed with a certificate whose SHA-256 is `f679880e48a2c08674cca66a969d860f1b779dbad4594177859f1b8d99c7cb14`.

GlidePad Pair was not created or endorsed by Amazon. Fire TV is a trademark of Amazon.com, Inc. or its affiliates.
