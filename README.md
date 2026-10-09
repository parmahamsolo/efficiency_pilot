# Efficiency Pilot

**A live efficiency dashboard for the BYD Sealion 7 (DiLink 5).**
See exactly how much power you're using, how much regen is putting back, and get ranked for
driving efficiently - full-screen on your head unit, or side by side with your map.

<p align="center">
  <img src="media/preview.gif" alt="Efficiency Pilot live while driving: power and regen gauge moving" width="100%">
</p>

<p align="center">
  <b><a href="../../releases/latest">⬇ Download the latest APK</a></b>
  &nbsp;·&nbsp; Free for personal use &nbsp;·&nbsp; No account, no ads
</p>

---

## What you get

| | |
|---|---|
| ⚡ **Power / regen gauge** | Live kW. Turns red for **POWER**, green for **REGENERATING**, so you see energy coming back the moment you lift off. |
| 📊 **Trip efficiency** | Your kWh/100km for this trip, plus distance driven. |
| 🔋 **Range recovered** | How many km regen has given back this trip, and what share of the distance that is. |
| 📈 **Recent efficiency chart** | A rolling line of your efficiency, so you see the effect of how you drive right away. |
| 🌀 **Motor speed** | Live motor RPM, plus the highest this trip. |
| 🏅 **Efficiency rank & XP** | Earn XP by driving efficiently. 100 ranks across 10 tiers, from *Energy Cadet* to *Efficiency Grandmaster*. Your rank is saved between drives. |
| 📱 **Split-screen mode** | A portrait layout that sits beside your navigation in split screen. |

## Screenshots

**Full screen**

<img src="media/main_screen.jpg" alt="Full-screen landscape HUD" width="100%">

**Split screen, beside navigation**

<img src="media/split_screen.jpg" alt="Split-screen HUD next to the map" width="100%">

**On the car**

<img src="media/real_life.jpg" alt="Efficiency Pilot running on a BYD Sealion 7 head unit" width="100%">

[▶ Watch the clip as a video](media/preview.mp4)

## Is it for my car?

- ✅ **BYD Sealion 7 with DiLink 5** - built and tested on this car.
- ❓ **Other BYD models on DiLink 5** - may work, not tested. Tell me if you try it.
- ❌ Phones and other cars - no. The app reads data from BYD's own system.

## What it does NOT do

- No account, no sign-up, no ads.
- No trip history, no location tracking, no vehicle data sent anywhere.
- It does **not** change any car setting. It only reads battery voltage/current, speed and motor RPM.
- About once a month it checks online that it's still a supported version. That check sends
  **only** an anonymous install ID and the app version number, used to count active installs.
  Details in [PERSONAL_USE_NOTICE.txt](PERSONAL_USE_NOTICE.txt).

## Install

1. Download `efficiency-pilot-<version>.apk` from **[Releases](../../releases/latest)**.
2. On the head unit, switch to **rotated (vertical) screen mode**.
3. Open **Developer options** and turn on **Wireless ADB debugging**.
4. Install the APK over wireless ADB.
5. **Updating?** Install the new APK over the old one. Your rank and settings stay.

## First-time setup (about 2 minutes, once)

The app needs a one-off permission to read the car's data:

1. Make sure **Wireless ADB debugging** is still on (from the install step).
2. Open Efficiency Pilot, tap **`...`** (bottom right) for Setup, then tap **Allow vehicle access**.
3. When the car asks **"Allow USB debugging?"**, tick **Always allow** and tap **Allow**.
4. The app restarts once. Live values appear.

Setup tells you plainly if a step is still missing.

## Good to know

- **After the head unit restarts**, the Sealion 7 turns Wireless ADB off. Turn it back on, open
  the app, and tap **Connect again** in Setup (it often reconnects by itself).
- **When the car goes to standby**, BYD closes all third-party apps. Just open it again after
  you start the car.

## FAQ

**Is it safe for my car?**
It only *reads* values. It doesn't change any car setting.

**Why does it need Developer options / ADB?**
BYD doesn't give third-party apps access to vehicle data. The app uses the head unit's own ADB
connection to switch that access on. The access resets every time the head unit restarts.

**Does it cost anything?**
No. It's free for personal use on your own car.

**Where's the source code?**
Not published. This repo hosts the release downloads and update notes.

## Updates

Watch this repo (**Watch → Custom → Releases**) to get notified when a new version is out.

## Feedback & contact

Found a bug or have an idea? Email **parmahamsolo@gmail.com**.

---

Free for personal use on your own vehicle. Do not redistribute, resell, rebrand, or reverse
engineer this app. See [PERSONAL_USE_NOTICE.txt](PERSONAL_USE_NOTICE.txt).
Not affiliated with or endorsed by BYD.

Copyright (c) 2026 parmahamsolo@gmail.com. All rights reserved.
