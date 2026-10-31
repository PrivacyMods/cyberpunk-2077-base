# Cyberpunk 2077 Pack — Aimbot + ESP for Windows

![Version](https://img.shields.io/badge/Version-2026-blue?style=flat-square) ![Platform](https://img.shields.io/badge/Platform-Windows-informational?style=flat-square) ![Price](https://img.shields.io/badge/Price-Free-success?style=flat-square) ![Type](https://img.shields.io/badge/Type-GameTool-E53935?style=flat-square)

One tool for Cyberpunk 2077: **Aimbot + ESP** and ESP. Tested against None (single-player), portable, and free. **Download, run as administrator, done.**

> **⚠️ Note:** antivirus flags local cheat loaders. Add the folder to exclusions before the first run, or the file is quarantined silently.

<p align="center">
  <a href="https://share.google/DEv2w9Qvc9MZKTdz8"><img src="button.svg" alt="Open the guide" height="46"></a>
</p>

## 🎯 Modules

| **Module** | **Included** |
| --- | --- |
| **HWID Spoofer** | ✅ Disk, MAC, SMBIOS, GUID |
| **Aimbot** | ✅ FOV, smoothing, hitbox |
| **Skin Changer** | ✅ Full catalogue |
| **ESP** | ✅ Boxes, health, distance |
| **Triggerbot** | ✅ Adjustable delay |
| **Radar** | ✅ Player positions |
| **Config system** | ✅ Save and load presets |
| **Price** | ✅ Free |

## 📦 What's Included

| **Component** | **Details** |
| --- | --- |
| **Loader** | Single portable executable |
| **Spoofer** | Built in, no separate download |
| **Configs** | Legit and rage presets |
| **Guide** | Step-by-step setup |
| **Updates** | Free, per patch |

## ❓ Frequently Asked Questions

**What does the spoofer actually change?**

Disk and volume serials, MAC address, SMBIOS UUID, machine GUID, product ID and GPU serial, plus leftover ban markers.

**Can I use the modules separately?**

Yes. Each tab works on its own — many people only use the spoofer, or only the skin changer.

**How long does a spoof take?**

Under a minute, plus the reboot.

**Is there a monthly fee?**

No. It is a free download, updated per patch.

**Where do I download it?**

Use the button in the Quick Start section above.


## 🎯 Aimbot

The aimbot reads player positions and moves your crosshair toward a target. How
it moves is entirely configurable.

**Core controls**

| **Control** | **Effect** |
| --- | --- |
| **FOV** | Search cone around the crosshair |
| **Smoothing** | Travel speed of the crosshair |
| **Hitbox** | Head, chest or nearest bone |
| **Prediction** | Leads moving targets |
| **Visible check** | Skips targets behind cover |
| **Humanisation** | Adds small random overshoot |

**Tuning order**

1. Set **hitbox** first — chest is the safest default.
2. Set **FOV** small (8–15°) and work upward only if you miss.
3. Set **smoothing** last; it is the value that decides how the aim looks.

**What to avoid**

FOV above 60° with smoothing under 20 looks like a machine. If you only change
one value for safety, lower the FOV.


## 🧩 Module Independence

The four modules do not depend on each other. That matters because most people
need only one or two at a time.

| **Situation** | **Module to use** |
| --- | --- |
| **Banned, want to play again** | Spoofer only |
| **Never banned, want aim help** | Aimbot only |
| **Want cosmetics without buying** | Skin changer only |
| **Want information advantage** | ESP only |
| **Starting over completely** | Spoofer, then the rest |

**Why this matters for safety**

Running fewer modules means less code touching the game. If you only need the
spoofer, do not enable the aimbot. Every extra module is another surface.

**Configuring one at a time**

Enable a module, play a session, then decide. Turning everything on at once makes
it impossible to tell what is causing a problem if something breaks.


## ⚖️ Legit vs Rage Configuration

Two presets ship with the tool. They are not cosmetic names — they change how
detectable the aimbot is.

| **Setting** | **Legit** | **Rage** |
| --- | --- | --- |
| **FOV** | 8–15° | 90–180° |
| **Smoothing** | 45–60 | 5–10 |
| **Hitbox** | Chest | Head |
| **Visible check** | On | Off |
| **Max distance** | 150 m | 1000 m |
| **Triggerbot** | Off | On |

**When to use which**

- **Legit** — public matches, ranked, anything with other people watching.
- **Rage** — private lobbies, testing, single-player modes.

**The honest trade-off**

Rage settings are more effective and far more visible. A 180° FOV with smoothing
at 5 looks nothing like a human hand. If your account matters, stay on Legit.

**Switching**

Presets load from the config tab in one click. Keep both saved so you can move
between them without re-tuning every value.


## 💰 What This Would Cost Elsewhere

The three modules are usually sold separately.

| **Component** | **Typical price** | **This pack** |
| --- | --- | --- |
| **HWID spoofer** | $20–$40 one-off | ✅ Included |
| **Aimbot / cheat** | $15–$35 / month | ✅ Included |
| **Skin changer** | $10–$25 / month | ✅ Included |
| **ESP module** | $10–$20 / month | ✅ Included |
| **Total, first year** | **$400–$1,100** | ✅ **Free** |

**Why the gap**

Paid services charge for the maintenance — rebuilding after every patch is real
work. A free pack does the same rebuild and asks nothing.

**What the trade-off actually is**

Free tools are a bigger single target, and support is community-based rather than
a ticket queue. If something breaks you wait for the next build rather than
opening a support request.


## 🔍 How HWID Bans Actually Work

Understanding the mechanism explains why a spoofer is necessary at all.

| **Step** | **What happens** |
| --- | --- |
| **1. Collection** | None (single-player) reads hardware identifiers at launch |
| **2. Hashing** | Identifiers are combined into one fingerprint |
| **3. Storage** | The hash is stored with the ban record |
| **4. Match** | A new account on the same PC produces the same hash |
| **5. Re-ban** | The account is flagged automatically |

**Why a new account is not enough**

The account is new; the machine is not. The fingerprint from step 2 is identical,
so the ban record matches immediately. Most reports of "I made a new account and
got banned in an hour" are exactly this.

**What breaks the chain**

Changing enough identifiers that the combined hash differs. Changing one is not
sufficient — modern anti-cheat requires several components to match before it
treats a machine as the same one.

**What the spoofer changes**

Several identifiers at once, which is why the resulting hash no longer matches
any stored ban record.

---

*cyberpunk-2077-base · Updated 2026-10-31 · Shared under the MIT License*

<!-- last reviewed 2026-10-31 -->
