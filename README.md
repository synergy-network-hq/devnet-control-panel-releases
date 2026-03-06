# Synergy Devnet Control Center — Downloads

This is where you download and update the **Synergy Devnet Control Center** app for your machine.

---

## How to Download

1. Go to the **[Releases page](https://github.com/synergy-network-hq/devnet-control-panel-releases/releases)**
2. Find the **latest release** at the top
3. Under **Assets**, click the file that matches your operating system:

| Your Computer | What to Download |
|---|---|
| **Mac (Apple Silicon)** — M1, M2, M3, M4 chips | The `.dmg` file labeled **arm64** |
| **Mac (Intel)** | The `.app.tar.gz` file labeled **x64** |
| **Linux** | The `.deb` file (Ubuntu/Debian) or `.AppImage` file |
| **Windows** | The `.msi` or `.exe` installer |

> **Not sure which Mac you have?** Click the Apple menu () → "About This Mac". If it says "Apple M1" (or M2, M3, etc.) you have Apple Silicon. If it says "Intel" you have an Intel Mac.

---

## How to Install

### Mac (Apple Silicon — `.dmg`)
1. Open the downloaded `.dmg` file
2. Drag the **Synergy Devnet Control Center** app into your **Applications** folder
3. Open it from Applications — if macOS asks you to confirm, click **Open**

### Mac (Intel — `.app.tar.gz`)
1. Double-click the downloaded `.app.tar.gz` to extract it
2. Move the **Synergy Devnet Control Center** app into your **Applications** folder
3. Open it from Applications — if macOS asks you to confirm, click **Open**

### Linux (`.deb`)
```
sudo dpkg -i synergy-devnet-control-center_*.deb
```

### Linux (`.AppImage`)
```
chmod +x Synergy*.AppImage
./Synergy*.AppImage
```

### Windows (`.msi` or `.exe`)
1. Run the downloaded installer
2. Follow the prompts
3. Launch from the Start menu

---

## Updating an Existing Installation

If you already have the Control Center installed, **you don't need to come back here to update it**. The app checks for updates automatically.

1. Open the Control Center
2. Look for the **Check for Updates** button in the bottom-left corner
3. If an update is available, the button will turn green and say **"Update Available"**
4. Click it to download and install the update
5. Restart the app when prompted

---

## Troubleshooting

**"The app is damaged and can't be opened" (Mac)**
Open Terminal and run:
```
xattr -cr /Applications/Synergy\ Devnet\ Control\ Panel.app
```
Then try opening the app again.

**The app won't connect to my nodes**
Make sure your WireGuard VPN connection is active before opening the Control Center.

**Update check says "error"**
Make sure your machine has internet access. The app needs to reach GitHub to check for updates.

---

## Questions?

Reach out in the **[Synergy Network Community Discord Server](https://discord.gg/synergy-network-hq)**.
