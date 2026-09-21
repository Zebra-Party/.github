# Privacy Policy — macboy

_Last updated: 2026-09-21_

macboy is a Game Boy emulator and development toolkit. It runs games you
supply yourself. We respect your privacy and collect nothing.

## What we store on your device

- **Your library**: the `.gb` / `.gbc` files you import, and the box art
  fetched for them (see below).
- **Your progress**: save states, the cartridge's own battery saves, and
  any cheat codes you enter. These are kept per player profile.
- **Your settings**: the active profile, recently played games, on-screen
  control preferences, display options, and whether you have seen the
  welcome screen.

All of it lives on your device, and in your own iCloud if you have it
switched on.

## What we send to iCloud

If you are signed in to iCloud, macboy syncs your library, profiles and
saves through **your own private iCloud container** so they appear on
your other devices — an Apple TV has no Files app, so this is how it gets
a library at all.

This is your private database. It is governed by Apple's privacy policy.
We have no server, no account system, and no way to see, store or process
any of it.

## What we request from the internet

macboy looks up **cover art** for the games in your library from the
public [libretro-thumbnails](https://github.com/libretro-thumbnails)
project on GitHub. To do that it requests a list of available filenames
and then an image, matched on the game's name.

That means GitHub receives the ordinary details of a web request — your
IP address, and the name of the game whose art is being fetched. We do
not see those requests and nothing about them reaches us. GitHub's use of
them is governed by GitHub's privacy policy. Art is cached on your device,
so it is fetched once.

This is the only outbound request macboy makes. If you would rather it
made none, the app works fully without it; games simply show a plain
card instead of cover art.

## Playing over a wireless link

The link-cable feature connects two devices **directly** to each other
over Wi-Fi or Bluetooth, using Apple's Multipeer Connectivity. Nothing
goes through a server of ours or anyone else's, and nothing is recorded.
iOS will ask for Local Network permission the first time; declining it
disables only that feature.

## What we do NOT do

- No advertising, no ad SDKs, no behavioural tracking.
- No analytics SDK. We do not record what you tap, which games you play,
  or how often you open the app.
- No account system of our own. No email address, no password.
- No personal data is sold or shared with third parties, ever.
- **No games are included.** macboy ships only its own sample programs
  and a public test ROM. Anything else is a file you provide.

## Children

macboy is suitable for all ages and does not knowingly collect any
personal information from children.

## Contact

For questions, open an issue on our GitHub:
https://github.com/Zebra-Party/.github/issues
