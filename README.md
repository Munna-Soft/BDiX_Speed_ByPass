# FlClash + BDiX Bypass Config — Convert BDiX to Raw Speed

This repository provides an **open-source configuration file** that, when used with the open‑source FlClash / Clash client, helps broadband or Wi‑Fi users route BDiX (Bangladesh Intranet Exchange) traffic directly — converting BDiX speed into true **raw speed**. 

- Even if your regular internet is slow, using this bypass config can allow files on the internet to download at very high speed — up to **500 Mbps capacity** (depending on your BDiX line).
- If your BDiX speed is higher, this bypass converts it to raw local throughput for maximum performance.

> **Note:** This repo contains only the configuration file. You must install FlClash (or Clash client) from the official open-source. For iOS devices, you can use Clash Meta (Clash Mi) from the App Store.

---

## Supported Platforms

- **Android** — via FlClash (GitHub release).
- **Windows** — via FlClash (GitHub release).
- **macOS** — via FlClash (GitHub release / Homebrew).
- **Linux** — via FlClash (GitHub release).
- **iOS (iPhone/iPad)** — via Clash Meta (Clash Mi) app from the Apple App Store.

---

## Installation & Usage

### Android
1. Download **FlClash** APK from the [GitHub releases](https://github.com/chen08209/FlClash/releases).
2. Install the APK on your Android device.
3. Open FlClash → Import config → Select `SpeedX.yaml`.
4. Start the client and test speed.

### Windows
1. Download FlClash for Windows from [GitHub releases](https://github.com/chen08209/FlClash/releases).
2. Install the APK on your Android device.
3. Open FlClash → Import config → Select `SpeedX.yaml`.
4. Test with any download manager or browser.

### macOS
1. Install Clash via Homebrew:
   ```bash
   brew install clash
   ```
   or download FlClash from [GitHub releases](https://github.com/chen08209/FlClash/releases).
2. Place `SpeedX.yaml` into `~/.config/clash/`.
3. Run:
   ```bash
   clash -f ~/.config/clash/SpeedX.yaml
   ```
4. Verify BDiX traffic is DIRECT.

### Linux
1. Download FlClash for Linux from [GitHub releases](https://github.com/chen08209/FlClash/releases).
2. Place config files in `~/.config/clash/`.
3. Run:
   ```bash
   clash -f ~/.config/clash/SpeedX.yaml
   ```
4. Confirm speed improvement with `wget` or `curl`.

### iOS (iPhone/iPad)
1. Install **Clash Meta (Clash Mi)** from the [Apple App Store](https://apps.apple.com/us/app/clash-mi/id6744321968).
2. Open Clash Mi → Import configuration file → Load `SpeedX.yaml`.
3. Start the service. All BDiX traffic will now bypass and convert to raw speed.

---

## Download Sources
- **FlClash (open-source):** [GitHub Releases](https://github.com/chen08209/FlClash/releases)
- **Clash Meta (Clash Mi for iOS):** [App Store](https://apps.apple.com/us/app/clash-mi/id6744321968)

---

## License

This project is released under the **MIT License**.

```
MIT License
Copyright (c) 2025 Munna MasterMind
```

---

## Config Credit

- Config created and maintained by **Munna MasterMind**
- FlClash software is developed and maintained by its open-source community.

---

## Contribution

Pull requests and issues are welcome if you want to add BDiX IP ranges or improve documentation.

---

🚀 With FlClash + BDiX bypass config, you can unlock **raw high-speed internet performance** across Android, Windows, macOS, Linux, and iOS (via Clash Mi).
