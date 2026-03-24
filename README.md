# forge.

![Build Time](https://img.shields.io/badge/BUILD_TIME-%3C2_HOURS-brightgreen?style=for-the-badge&logo=fastapi&logoColor=white)
![Aura Points](https://img.shields.io/badge/AURA-DETERMINISTIC-blueviolet?style=for-the-badge)

[![Download on the App Store](https://img.shields.io/badge/Download_on_the-App_Store-000000?style=for-the-badge&logo=apple&logoColor=white)](YOUR_APP_STORE_URL)
[![Get it on Google Play](https://img.shields.io/badge/Get_it_on-Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](YOUR_GOOGLE_PLAY_URL)

> **forge.** does not ask how you feel. It tells you who you are.

---

### THE MANIFESTO
A deterministic identity lab. forge. synthesizes live biometric data and digital consumption to generate a **vibe receipt**—a timestamped proof of your current state.

* **NO STORAGE:** Your data is forged, printed, and purged. The app remembers nothing.
* **NO OPTIONS:** You cannot mute the pulse. You cannot change the color. The truth is not customizable.
* **SHARE TO SAVE:** If you do not witness the moment, it is lost to the void.

---

### THE ANATOMY OF A RECEIPT
Each scan lasts **7 seconds** and reads:
1. **BIO:** Live BPM + HRV (Heart Rate Variability)
2. **MOTION:** Step count + Gait symmetry (Last 120m)
3. **DIGITAL:** Screen time category distribution + Pickup frequency
4. **ENV:** Ambient light (Lux) + Noise floor (dB)

---

## THE VIBE DICTIONARY

### 🟣 THE ROT — Low Kinetic / High Digital
*Trigger: Steps < 100 in last 2h AND Screen Time > 60% of last 2h.*

| VERB | TRIGGER | COLOR | HAPTIC |
| :--- | :--- | :--- | :--- |
| **stagnating** | Default ROT state | Light Plum | Soft Throb |
| **bed rotting** | Light < 10 Lux + Charging | Deep Purple | Heavy Sink |
| **calcified** | No movement > 4h | Ash Grey | None (Dead) |
| **glued** | Social Media > 80% screen | Toxic Pink | Sticky Pulse |

### 🟢 THE GRIND — High Kinetic / Focus
*Trigger: Steps > 1500 in last 2h OR Productivity Apps > 50%.*

| VERB | TRIGGER | COLOR | HAPTIC |
| :--- | :--- | :--- | :--- |
| **locking in** | High Focus App usage | Neon Wasabi | Sharp Tap |
| **grinding** | Constant movement + High BPM | Safety Orange | Rapid Buzz |
| **machining** | Steps > 3000 in 1h | Industrial Steel | Metronome |
| **overclocked** | BPM > 120 + Stationary | Electric Red | Double-Beat |

### ⚫ THE VOID — Environmental Isolation
*Trigger: Ambient Light < 5 Lux AND Noise Floor < 30dB.*

| VERB | TRIGGER | COLOR | HAPTIC |
| :--- | :--- | :--- | :--- |
| **ghosting** | Zero pickups > 1h | Translucent White | Ghost Tap |
| **abyssal** | Midnight – 4AM Window | Absolute Black | Ultra-Low Freq |
| **liminal** | Low Light + Low Battery | Eerie Yellow | Flutter |

### 🔵 THE FLOW — Optimal Balance
*Trigger: HRV High AND Steps 500–1000.*

| VERB | TRIGGER | COLOR | HAPTIC |
| :--- | :--- | :--- | :--- |
| **ascending** | Consistent gait symmetry | Sky Chrome | Wave Flow |
| **zenith** | BPM in resting zone | Pure Gold | Heartbeat |
| **rhythmic** | Music playing + Walking | Deep Teal | Sync-Bounce |

### ⚡ THE LEGENDARIES — 1% Rarity / Edge Cases
*These override all other families when conditions are met.*

| VERB | TRIGGER | COLOR | HAPTIC |
| :--- | :--- | :--- | :--- |
| **absolute** | 0 Steps + 0 Lux + 0 dB (True Silence) | #FFFFFF Pure White | Single Heartbeat |
| **forged** | First scan after 24h app absence | #FFD700 Gold | Intense 1s Vibration |
| **thrashing** | BPM > 130 + Noise > 90dB (Concert/Club) | Neon Magenta | Erratic Jitter |
| **zenith** | HRV at all-time high + 0 Screen Time | Chrome Green | Deep Harmonic |
| **archived** | Forge at exactly 00:00 (Midnight) | #50C878 Emerald | TIME_SLIP_DETECTED |

---

### SENSOR MAPPING
* **Color Saturation** → Driven by **BPM**. Higher BPM = Higher Saturation.
* **Pulse Speed** → Fixed to **Live BPM**.
* **Receipt Grain** → Driven by **Screen Time**. More screen = grainier texture.

---

## .signal MODE

Forge **3 times** to unlock **.signal**—a persistent ambient layer that bleeds your last vibe state into your device.

* **AuraPulse Shader:** Radial gradient + 1Hz sine pulse + simplex noise turbulence.
* **Two Modes:** LOW_POWER (24hr+ battery, 60s refresh) and PERFORMANCE (6hr est., 5s refresh, full turbulence).
* **Zero Network. Zero Storage.** The signal bridge writes locally. Nothing leaves your device.

---

### iOS — Lock Screen Widget Setup

1. Open **forge.** and forge at least **3 times** to unlock Signal Mode.
2. Lock your device, then **long press** the Lock Screen.
3. Tap **Customize** → select your Lock Screen.
4. Tap the widget area (above or below the clock).
5. Scroll or search for **forge.** in the widget list.
6. Select a size: Circular, Rectangular, Small, or Medium.
7. Tap **Done** → **Set as Wallpaper Pair**.

Your Lock Screen now pulses with your last forged vibe state.

---

### Android — Live Wallpaper Setup

1. Open **forge.** and forge at least **3 times** to unlock Signal Mode.
2. **Long press** your home screen → tap **Wallpapers**.
3. Look for **Live Wallpapers** or **forge. signal** in the list.
4. Select it → tap **Set wallpaper** → choose Home screen, Lock screen, or both.

> **Note for some devices (Moto, Samsung, etc.):** Some Android manufacturers hide live wallpapers from the default picker. If you don't see it:
> - Open **Settings** → search for **"Live wallpaper"**
> - Or install **"Live Wallpaper Picker"** from the Play Store
> - Or use ADB: `adb shell am start -a android.service.wallpaper.CHANGE_LIVE_WALLPAPER -e android.service.extra.LIVE_WALLPAPER_COMPONENT "app.loyal9.forge/.signal.ForgeWallpaperService"`

---

### CREDITS
* **CONCEPT & VISION:** [Shannon Goddard](https://github.com/Shannon-Goddard)
* **SYNTHETIC ARCHITECT:** Gemini 1.5
* **DEVELOPMENT & DEPLOYMENT:** Amazon Q Developer

---

[![Privacy Policy](https://img.shields.io/badge/PRIVACY-PROTOCOL_v1.0-333333?style=flat-square)](YOUR_PRIVACY_URL)

`[ END OF DATA ]`
