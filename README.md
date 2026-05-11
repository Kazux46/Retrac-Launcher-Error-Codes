# 📕 Retrac Support: Staff Error Guide

Welcome to the official error reference for the Retrac support team. This guide is designed to help you quickly identify issues and provide clear, actionable steps to get players back in the game.

> [!TIP]
> **The Golden Rule:** 90% of launcher issues are solved by running as **Administrator** and adding the game folder to **Windows Defender Exclusions**. Always ask the user to try these first!

---

## ⚡ Quick Fix Dashboard
If a user is in a hurry, check these common fixes first:
*   **Game won't open?** Check for a missing `FortniteGame` folder (Error 1001).
*   **Download stuck?** Usually a permissions issue or full disk (Error 2003).
*   **Discord login failing?** Make sure their Discord app is actually open and logged in (Error 3002).

---

## 🎮 Game & Launching
*Errors that happen when the user clicks "Play".*

### **1001 - Path Invalid**
*   **What's happening:** The launcher is looking for Fortnite but can't find it where the user said it was.
*   **The Fix:** Ask them to re-select the folder. It should be the main folder that contains `FortniteGame`.

### **1002 - Version Mismatch**
*   **What's happening:** They are trying to use a Fortnite version that our servers don't support.
*   **The Fix:** Verify which version they have. Direct them to the `#downloads` channel for the correct build.

### **1005 - EAC Missing**
*   **What's happening:** The Easy Anti-Cheat setup is missing or moved.
*   **The Fix:** They might need to verify their files or manually run the EAC setup from the game's `EasyAntiCheat` folder.

### **1006 - Process Blocked**
*   **What's happening:** Windows (or an Antivirus) is refusing to let Retrac start the game.
*   **The Fix:** Ensure they have disabled all "Real-time protection" and are running the launcher as Admin.

---

## 📥 Downloads & Installation
*Errors that happen during the update or install process.*

### **2001 - Manifest Failure**
*   **What's happening:** The launcher can't "see" our download server.
*   **The Fix:** Usually a temporary server blip. Have them wait 5 minutes. If it persists, check if our CDN is down.

### **2002/2003 - Disk & Write Errors**
*   **What's happening:** The launcher can't save the game files to their computer.
*   **The Fix:** Check if their drive is full. If not, their Antivirus is likely "eating" the files as they download. Add an exclusion!

---

## 🔑 Accounts & Connectivity
*Errors related to Discord or the Retrac API.*

### **3001 - Socket Disconnect**
*   **What's happening:** The constant "handshake" with our server was broken.
*   **The Fix:** Have them restart the launcher. If it keeps happening, their internet might be unstable or they might be using a VPN that we block.

### **3002 - Discord Auth Error**
*   **What's happening:** The launcher couldn't talk to their Discord app to log them in.
*   **The Fix:** Tell them to open Discord first, *then* open the launcher. If that fails, have them log out and back in on Discord.

---

## 🛡️ System & Permissions
*Windows-specific headaches.*

### **4001 - Defender Exclusion Failed**
*   **What's happening:** The "Add Exclusion" button failed to work.
*   **The Fix:** This *requires* Admin rights. If they are already Admin, they'll have to add the folder to Windows Defender manually.

### **4002 - Version Detection Error**
*   **What's happening:** The launcher is confused about what version of Windows or Fortnite they are running.
*   **The Fix:** Usually happens on "stripped" or custom Windows versions. Ask them to ensure they aren't using a modified `FortniteClient-Win64-Shipping.exe`.

---

## 📝 Staff Reminder
Stay patient! Most players are frustrated because they just want to play. If an error isn't on this list, grab a screenshot and post it in your ticket.

**Official Support Link:** [discord.gg/6sNFtW4Hva](https://discord.gg/6sNFtW4Hva)
