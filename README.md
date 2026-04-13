# 💎 SimpleClaim - The Ultimate Land Protection Suite

![Version](https://img.shields.io/badge/Version-1.0-blue.svg) ![Minecraft](https://img.shields.io/badge/Minecraft-1.21--1.21.1-green.svg) ![Platform](https://img.shields.io/badge/Platform-Paper%20%7C%20Spigot%20%7C%20Bukkit-orange.svg)

**SimpleClaim** is a high-performance, cross-platform land claiming solution built for modern Minecraft servers. Experience zero-lag protection with a premium, polished feel, now optimized with **Spatial Indexing** for enterprise-scale performance.

---

## 🚀 Technical Excellence

### ⚡ **Infinite Scaling (Spatial Indexing)**
Unlike traditional plugins that slow down as more claims are created, SimpleClaim uses a **Chunk-based Spatial Index**. Lookups occur in **O(1) time**, ensuring your server remains at 20 TPS even with thousands of active claims.

### 🌉 **Adventure API Universal Bridge**
Built on the **Adventure API**, SimpleClaim runs natively on **Paper** and **Purpur**, while providing a high-performance bridge for **Spigot** and **Bukkit**. One Jar, zero compromises.

---

## ✨ Premium Features

### ☠️ **Advanced Death Chests**
*   **Holographic Display**: A 3-line floating hologram displays the Owner, the Death Reason, and a Live Countdown.
*   **Click-to-Teleport**: Upon death, receive a private message with a clickable **[Teleport]** action to find your items instantly.
*   **Auto-Cleanup**: Fully configurable expiration timers. Once you empty the chest, it vanishes automatically!
*   **Secure Storage**: Grief-proof, piston-proof, and explosion-proof until the timer runs out.

### 🛡️ **Absolute Environmental Protection**
Simply claiming an area provides immediate, absolute safety for your home and investments:
*   **Total Immunity**: No damage from PVP, Mobs (PVE), Falling, or Fire while inside a claim.
*   **Explosion & TNT Proof**: TNT, Creepers, and Fireballs do zero damage to blocks or entities.
*   **Fire Suppression**: Fire ignition, burning, and spreading are completely disabled in claims.
*   **Piston-Push Protection**: Pistons are disabled in the wilderness. They ONLY work if placed inside a claim and cannot push blocks across claim boundaries.
*   **Technical Block Lock**: Hoppers and Minecarts are restricted to claimed territory to prevent automated theft.
*   **Animal Sanctuary**: Your cows, sheep, and other animals are 100% safe from both players and mobs.

---

## 🛠️ Commands & Permissions

| Command | Description | Permission |
|:---|:---|:---|
| `/trust <player>` | Grant access to your claim | `simpleclaim.trust` |
| `/untrust <player>` | Revoke access | `simpleclaim.untrust` |
| `/unclaim` | Delete the current claim | `simpleclaim.unclaim` |
| `/claimlist` | View your active claims | `simpleclaim.claimlist` |
| `/claimblocks` | Check block balance | `simpleclaim.claimblocks` |
| `/buyclaimblocks <qty>` | Purchase blocks via Economy | `simpleclaim.buyblocks` |
| `/sellclaimblocks <qty>` | Sell blocks for money | `simpleclaim.sellblocks` |
| `/deathchest tp <id>` | Teleport to a death chest | `simpleclaim.deathchest.tp` |

**Admin Override**: Use `simpleclaim.admin` for absolute power to bypass all protections and manage any claim.

---

## 🔧 Installation & Configuration

1.  Place `SimpleClaim.jar` into your `plugins` folder.
2.  Ensure **Vault** is installed for economy features.
3.  Restart your server.
4.  Customize `config.yml` for claim sizes, prices, and settings.
5.  Customize `messages.yml` for full branding and localization.

---
*Developed for Visual Excellence and Server Stability For By Benjamin Krishan*
