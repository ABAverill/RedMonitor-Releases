# Reddit Monitor Desktop — Releases

This repository hosts downloadable builds of **Reddit Monitor Desktop**.

## Downloads

Go to the [**Releases**](../../releases) tab to download the latest version for your platform:

| Platform | File |
|----------|------|
| macOS (Apple Silicon) | `RedMonitor-arm64.dmg` |
| macOS (Intel) | `RedMonitor-x64.dmg` |
| Windows | `RedMonitor-Setup.exe` |

## Installation

### macOS
1. Download the `.dmg` for your chip (arm64 = Apple Silicon, x64 = Intel)
2. Open the `.dmg` and drag **Red Monitor** to your Applications folder
3. **Before running the app**, open Terminal and run:
   ```bash
   xattr -cr "/Applications/Red Monitor.app"
   ```
   This removes the quarantine attribute so the app can launch. This step is required.
4. Launch **Red Monitor** from Applications. If macOS still warns about an unverified developer, right-click the app → **Open**, then confirm.

### Windows
1. Download `RedMonitor-Setup.exe`
2. Run the installer and follow the prompts
3. On first run, Windows may show a SmartScreen or “Unknown publisher” warning because we’re indie developers. Click **More info** (if shown), then **Run anyway** to continue

---

> Source code lives in [RedditMonitorDesktop](https://github.com/YOUR_USERNAME/RedditMonitorDesktop).
