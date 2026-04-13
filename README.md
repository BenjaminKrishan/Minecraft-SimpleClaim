# 💎 SimpleClaim - The Ultimate Land Protection Suite

![Version](https://img.shields.io/badge/Version-1.0-blue.svg) ![Minecraft](https://img.shields.io/badge/Minecraft-1.21--1.21.11-green.svg) ![Platform](https://img.shields.io/badge/Platform-Paper%20%7C%20Spigot%20%7C%20Bukkit-orange.svg)

**SimpleClaim** is a high-performance, cross-platform land claiming solution built for modern Minecraft servers. Experience zero-lag protection with a premium, polished feel.

---

## ✨ Premium Features

### 🚀 **Ultra-Compatible Bridge**
Built on the **Adventure API**, SimpleClaim runs natively on **Paper** and **Purpur**, while providing a high-performance bridge for **Spigot** and **Bukkit**. One Jar for every server.

### ☠️ **Advanced Death Chests**
*   **Holographic Display**: A 3-line floating hologram displays the Owner, the Death Reason, and a Live Countdown.
*   **Click-to-Teleport**: Upon death, receive a private message with a clickable **[Teleport]** action to find your items instantly.
*   **Auto-Cleanup**: Fully configurable expiration timers. Once you empty the chest, it vanishes automatically!
*   **Secure Storage**: Grief-proof, piston-proof, and explosion-proof until the timer runs out.

### 🛡️ **Elite Universal Protection**
Simply claiming an area provides immediate, absolute safety for your home and investments:
*   **Total Immunity**: No damage from PVP, Mobs (PVE), Falling, or Fire while inside a claim.
*   **Explosion & TNT Proof**: TNT, Creepers, and Fireballs do zero damage to blocks or entities.
*   **Fire Suppression**: Fire ignition, burning, and spreading are completely disabled in claims.
*   **Technical Block Lock (Elite)**: 
    *   **Pistons**: Disabled in the wilderness. They ONLY work if placed inside a claim, stopping "piston-push" griefing.
    *   **Hoppers & Minecarts**: Automation is locked to claimed territory. Hoppers in the wilderness (including Minecarts) will not move items.
    *   **Anti-Theft**: Hoppers cannot pull items out of containers (like Chests or Death Chests) across claim boundaries.
*   **Animal Sanctuary**: Your cows, sheep, and other animals are 100% safe from both players and mobs.
*   **No Stolen Items**: Untrusted players cannot open containers or interact with items.

### 🔑 **Streamlined Permissions (Default: False)**
We've simplified our system to be elite and easy to manage:
*   `simpleclaim.claim`: Allows creating and resizing claims.
*   `simpleclaim.deathchest.tp`: Allows using the clickable teleport button.
*   `simpleclaim.admin`: **The Master Bypass**. Grants absolute power to override protections, access any chest, and bypass all build restrictions. (Default: OP)

---

## 🛠️ Commands

| Command | Description | Permission |
|:---|:---|:---|
| `/trust <player>` | Grant access to your claim | `simpleclaim.trust` |
| `/untrust <player>` | Revoke access | `simpleclaim.untrust` |
| `/unclaim` | Delete the current claim | `simpleclaim.unclaim` |
| `/claimlist` | View your active claims | `simpleclaim.claimlist` |
| `/claimblocks` | Check block balance | `simpleclaim.claimblocks` |
| `/buyclaimblocks <qty>` | Purchase blocks | `simpleclaim.buyblocks` |
| `/sellclaimblocks <qty>` | Sell blocks | `simpleclaim.sellblocks` |

---

## 🔧 Configuration
The plugin generates detailed `config.yml` and `messages.yml` files. You can customize every single message, sound, and visual effect to match your server's brand.

---
*Simple Claim Plugin By - Benjamin Krishan*
