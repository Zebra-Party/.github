# Privacy Policy — macboy

_Last updated: 2026-10-03_

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

On iPhone and iPad your library is also kept as ordinary files in
macboy's own iCloud Drive folder, so you can see and manage your ROMs and
saves in the Files app. That is deliberate — they are your files — but it
does mean anything with access to your iCloud Drive can read them.

## What we request from the internet

macboy looks up **cover art** for the games in your library from the
public [libretro-thumbnails](https://github.com/libretro-thumbnails)
project. That takes requests to **two** different services:

- **`api.github.com`** — to list the artwork filenames available for the
  Game Boy and Game Boy Color. This asks only for the system's list and
  says nothing about you or your games. The list is cached on your device
  for two weeks.
- **`thumbnails.libretro.com`** — to fetch the image itself. **The game's
  name is part of this request.** macboy tries the title stored inside
  the cartridge and the file's own name, so if you have named a file
  something personal, that name is what gets sent. When a game has no
  artwork, several variations of the name may be tried before macboy
  gives up.

Those two services therefore see the ordinary details of a web request —
your IP address — and, for the second, the name of a game in your
library. We do not see those requests and nothing about them reaches us;
GitHub's and the libretro project's handling of them is governed by their
own privacy policies. Images are cached on your device, so a given game
is fetched once.

These cover-art lookups are the only requests macboy makes to anyone's
servers, besides your own iCloud. They happen automatically when a game
appears on screen, and there is currently **no setting to turn them
off** — we would rather say so than imply a control that isn't there. The
app is fully usable without them: if the requests fail, games simply show
a plain card.

## Playing over a wireless link

The link-cable feature connects two devices **directly** to each other
over Wi-Fi or Bluetooth, using Apple's Multipeer Connectivity. Nothing
goes through a server of ours or anyone else's, and nothing is recorded.
iOS will ask for Local Network permission the first time; declining it
disables only that feature.

Two things to be straight about: the connection is **not encrypted**, and
while it is being set up your device advertises its name to other devices
on the same network. It is meant for playing with someone in the room, on
a network you trust — not over public Wi-Fi.

## What we do NOT do

- No advertising, no ad SDKs, no behavioural tracking.
- No analytics SDK. We do not record what you tap, which games you play,
  or how often you open the app.
- No account system of our own. No email address, no password.
- No personal data is sold or shared with third parties, ever.
- **No games are included.** macboy ships only its own sample programs
  and a public test ROM. Anything else is a file you provide.
- **No notifications.** The Apple TV build carries a push-notification
  entitlement because the App Store requires one alongside iCloud sync,
  but macboy has no way to send a notification and never does.

## Children

macboy is suitable for all ages and does not knowingly collect any
personal information from children.

## Contact

For questions, open an issue on our GitHub:
https://github.com/Zebra-Party/.github/issues
