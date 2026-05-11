# Retrac Launcher Support: Error Codes Reference

This document provides a comprehensive list of error codes and troubleshooting steps for the Retrac Launcher support team.

## 🚀 1xxx: Launch & Game Errors
Errors related to starting the game or checking game files.

| Code | Error Message | Meaning | Troubleshooting Steps |
| :--- | :--- | :--- | :--- |
| **1001** | `Invalid Fortnite installation path` | The folder selected doesn't contain a valid Fortnite installation. | 1. Ensure the path points to the main Fortnite folder.<br>2. Check if `FortniteGame` folder exists inside. |
| **1002** | `Unsupported Fortnite version` | The version of Fortnite found is not compatible with Retrac. | 1. Ensure you are using the correct build version required by the server. |
| **1003** | `Already launching` | User tried to launch while a launch process was already active. | 1. Wait a few seconds.<br>2. Restart the launcher if it's stuck. |
| **1004** | `Failed to launch Retrac` | General failure during the injection or launch process. | 1. Run Launcher as Administrator.<br>2. Disable Antivirus/Windows Defender. |
| **1005** | `EAC setup path does not exist` | Could not find the Easy Anti-Cheat setup executable. | 1. Verify game files.<br>2. Ensure EAC is installed in the game folder. |
| **1006** | `Failed to create process: [ID]` | Windows refused to start the game process. | 1. Check if the game EXE is missing.<br>2. Check for permission issues (Run as Admin). |

---

## 📥 2xxx: Download & Installation Errors
Errors related to downloading builds or manifests.

| Code | Error Message | Meaning | Troubleshooting Steps |
| :--- | :--- | :--- | :--- |
| **2001** | `Failed to download manifest` | Could not fetch the build list from the CDN. | 1. Check internet connection.<br>2. Server might be down (Check #announcements). |
| **2002** | `Failed to download chunk [Hash]` | A specific part of the download failed to download. | 1. Check disk space.<br>2. Ensure the launcher has write permissions to the folder. |
| **2003** | `Error rebuilding file` | Downloaded chunks couldn't be merged into the final file. | 1. Usually caused by Antivirus blocking the file creation.<br>2. Check if disk is full. |
| **2004** | `Build not found in library` | User tried to launch a build they haven't added/downloaded. | 1. Refresh the library.<br>2. Re-download the build. |
| **2005** | `Another download in progress` | User tried to start a download while one was already running. | 1. Wait for current download to finish or cancel it. |

---

## 🌐 3xxx: Connection & Auth Errors
Errors related to the server connection and Discord login.

| Code | Error Message | Meaning | Troubleshooting Steps |
| :--- | :--- | :--- | :--- |
| **3001** | `Disconnected from server` | The socket connection to Retrac servers was lost. | 1. Check Discord status.<br>2. Restart the launcher.<br>3. Check if your IP is banned or ratelimited. |
| **3002** | `Failed to get exchange code` | Discord authentication failed. | 1. Ensure Discord is open and you are logged in.<br>2. Try logging out and back in within the launcher. |
| **3003** | `Timeout` | The server took too long to respond. | 1. Check your ping.<br>2. Server might be under high load. |

---

## 🛡️ 4xxx: System & Permission Errors
Errors related to Windows settings and permissions.

| Code | Error Message | Meaning | Troubleshooting Steps |
| :--- | :--- | :--- | :--- |
| **4001** | `Failed to add to Windows Defender` | Launcher couldn't add itself/game to exclusions. | 1. **Run as Administrator** (Required for this action).<br>2. Manually add the folder to exclusions. |
| **4002** | `Pattern not found` / `Version not found` | Could not identify the Windows or Game version. | 1. Ensure Windows is up to date.<br>2. Check if the game files are modified. |

---

## 💡 General Support Tips
1. **Admin Mode**: 90% of issues are fixed by running the launcher as **Administrator**.
2. **Exclusions**: Always add the Launcher and Game folders to **Windows Defender Exclusions**.
3. **Discord**: Direct users to [Discord Support](https://discord.gg/6sNFtW4Hva) for complex issues.
4. **Logs**: If issues persist, ask the user for the `launcher.log` (if available) or a screenshot of the error.
