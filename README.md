# rPlayFling

rPlayFling puts the videos you watch on your iPhone onto your **car's CarPlay screen** — and onto
TVs (AirPlay, Chromecast, DLNA). Browse a video site on the phone, tap **Cast**, and it plays on the
car while you are parked.

### ⬇ Get it

**[Join the TestFlight beta](https://testflight.apple.com/join/rncgthyN)** — iPhone, iOS 18 or later, with a CarPlay car or head unit.

**[User guide](docs/user-guide.md)** · [Report a problem](https://github.com/rPlayAI/rPlayFling-public/issues) ·
[Release notes](docs/releases.md)

**Tutorials:** [Cast a YouTube video to the car](docs/cast-from-youtube.md) · [Cast from the YouTube app](docs/cast-from-youtube-app.md) · [Fill the whole car screen](docs/full-screen.md)

This repository is for **releases, documentation and issues**. The source code is not public.

New here? The **[user guide](docs/user-guide.md)** walks through every feature: casting, the car screen, the Web tab and full screen, knob cars, casting from the YouTube app with a TV code, your own videos, and troubleshooting.

## What it does

- **Cast to the car** — videos from the browser play on the CarPlay screen; next and previous on the
  steering wheel; 1080p where the site offers it.
- **Web tab on the car** — a browser on the car screen itself, with a car keyboard (English, Chinese
  pinyin) and voice input.
- **DLNA receiver** — apps that cast to TVs (iQiyi, Youku, Bilibili and others) list “rPlayFling”, and
  what they send plays on the car.
- **Your own videos and photos** — from Photos or Files (MKV, AVI and WebM are converted to MP4), as a
  slideshow or a playlist on the car.
- **Cast Screen** — show any other app's screen on the car.
- **TVs too** — AirPlay, Chromecast and DLNA TVs.

Video on the car screen is for when the car is **parked**: by default the picture is hidden while
the car moves (sound keeps playing).

## Two kinds of cars

| Car | How video shows |
|---|---|
| CarPlay without video support (most cars, iOS up to 27.0) | rPlayFling draws on the car screen itself |
| Cars with CarPlay video playback (iOS 27.2 and later) | the car's own video player plays the file rPlayFling hands it |

## Reporting a problem

Please [open an issue](https://github.com/rPlayAI/rPlayFling-public/issues/new/choose) with your iPhone model,
iOS version, rPlayFling version, and the car or head unit. A screenshot or a photo of the car screen
helps a lot.

## Feedback

Ideas and feature requests are welcome too — use the *Feature request* form under
[Issues](https://github.com/rPlayAI/rPlayFling-public/issues/new/choose).
