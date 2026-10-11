# Release notes

## 2.1 (64) — October 11, 2026

Everything since 2.1 (50), the last public build. Items marked (53) went out in the 2.1 (53) hotfix.

**Cast from the YouTube app to the car**
- Link once with a TV code: Settings › Link YouTube with TV code, then enter it in the YouTube app (Cast icon › + Add a device, or Settings › Watch on TV). "rPlayFling" is then in YouTube's Cast menu wherever rPlayFling is open on the car, even on cellular with no Wi-Fi.
- On the same Wi-Fi the YouTube app finds rPlayFling by itself; with a code linked it shows once.
- The YouTube app is the remote: its queue, next and previous, seek, pause and autoplay all drive the car.
- Stop casting in the app and the car stops; cast from our app and the car follows the latest request, while the YouTube app shows what the car plays and keeps controlling it.
- A paid film, which YouTube keeps to its own app, is reported back as ended instead of freezing the app's player.
- Unlink in Settings; the link survives updates and reinstalls.

**Resume**
- Settings › Resume last video when the car connects (off by default): the last video plays on from where it stopped as soon as rPlayFling is open on the car.
- Photos & Videos continue where you left off.

**Receivers**
- DLNA receiver: iQiyi, Youku, Bilibili and other DLNA apps cast to the car.
- FCast receiver (Grayjay), off by default.
- Settings › Receive casts from other apps.

**Car screen and the knob**
- Video bar: the title beside the seek bar, ±15 s, a full-width seek bar with the quality beside the time, the knob lands on the bar and stays on the seek bar while scrubbing. (53)
- Car web tab: the knob moves over the page's links, buttons and videos, in a steady order past the site's fixed bars; the video player's controls are in reach; a Full-screen page button; the page stays reachable after a video. (53)
- Full screen can be left with the knob: up past the top of the page, or a press on nothing.
- A player frozen at rate 0 restarts; a stall restarts the stream. (53)
- A cast that cannot play says so on the car instead of "Loading…" forever. (53)
- Disconnecting the car ends the cast at once unless another device is watching. (53)
- The video bar fades and stays faded while a video plays.

**Settings**
- Simplified Chinese for Settings and the car screens.
- Car video size (Fit, Fill, Stretch) in Settings.
- A trimmed Settings page: the cast queue, recent casts and the logs page are gone from it.

**Fixes**
- A crash at launch in the car's channel list.
- YouTube app casts that stopped working on the second try (the Lounge session died on every reconnect).
- A black car screen after a cast that could not play.
- The car's player staying paused on the old picture when the YouTube app took over.

**Known**
- A video can start at 360p and move to 1080p after a while, when YouTube releases the HD stream; on the road the wait is longer.
- DRM apps (Netflix, Disney+, Crunchyroll) show black in a screen cast, and paid YouTube films play only in the YouTube app; that is iOS and YouTube.
- Cars on iOS 27.2 without CarPlay video playback play the sound only.

The [user guide](user-guide.md) covers every feature.

## 2.1 (21) — October 2026

- **1080p on cars with CarPlay video playback** (iOS 27.2): YouTube videos now reach the car's own
  player in full HD with sound, instead of 360p.
- **MKV, AVI and WebM** imported from Files are converted to MP4 automatically (H.264/HEVC copied as
  is, other formats re-encoded on the iPhone's hardware encoder).
- **Browser downloads**, as in Safari: a file link asks first, long-press offers *Download Linked
  File*, a Downloads list, and the Files app shows *On My iPhone › rPlayFling › Downloads*.
- **Ad blocker** for websites (ad networks, trackers, pop-ups), on by default in Settings. YouTube is
  not changed.
- **Car Web tab**: opens YouTube with full rows of videos, full-screen video, ⤢ to give the page the
  whole screen, an address field with your bookmarks, Chinese pinyin (中/英), 🌐 languages and 🎤 voice
  input.
- **Car toolbars** use CarPlay's own frosted look, light by day and dark by night.
- **Battery**: nothing runs in the background without a cast or a car; the DLNA receiver leaves other
  apps' device lists when rPlayFling goes to the background.
- The address bar keyboard has a space bar.

## 2.0 (20) — October 2026

- **DLNA receiver**: video apps that cast to TVs list “rPlayFling”, and what they send plays on the car.
- **Web page on the car screen**, with a car keyboard.
- Steering-wheel next/previous moves between videos.
- CarPlay Now Playing shows the video on air, with play/pause.
- Settings: *Video under CarPlay sidebar*, *Car toolbar look*.
- Browser: Mobile / Desktop site, remembered per site.
- A paused HD video is a still picture; autoplay no longer brings back old videos.
- Files import says when a video cannot be played.

## 1.6 — October 2026

- Works on its own in CarPlay (no second app needed).
- HD that arrives late starts at 360p and moves to HD; HD for videos tapped in the feed.
- Videos for cars with CarPlay video playback; resume after a phone call.
- Settings reordered: CarPlay target only, Car toolbar, Cast quality.
