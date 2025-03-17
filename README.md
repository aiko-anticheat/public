# 📌 AikoAC (AntiCheat) - Complete Guide

## 🚀 Introduction

**AikoAC** is an advanced anti-cheat system developed for **FiveM**, ensuring server security and integrity. It provides powerful tools for **monitoring**, **detection**, and **mitigation** of cheats, as well as administrative functionalities for efficient server management.

The `/aiko` command is the main interface of AikoAC, allowing administrators and moderators to execute actions directly in the game.

---

## 🎮 Command Usage

The command follows the following syntax:

```bash
/aiko [subcommand] [parameters]
```

Each subcommand has a specific function and may require additional parameters.

---

## 🔹 Available Subcommands

### 🎯 1. **info**
Displays detailed information about the player who executed the command.

```bash
/aiko info
```

### 📋 2. **menu**
Opens the AikoAC system menu for the player (requires proper permission).

```bash
/aiko menu
```

### 🛡️ 3. **wall**
Enables or disables the "wallhack" feature in AikoAC for the player (requires proper permission).

```bash
/aiko wall
```

### 👑 4. **setowner [playerId]**
Sets a player as the server owner (requires permission).

```bash
/aiko setowner 123
```

### ⚙️ 5. **setperm [permission] [playerId]**
Modifies a player's permission. Available permissions: `owner`, `administrator`, `moderator`, `support`, `user`.

```bash
/aiko setperm administrator 123
```

### 🔨 6. **ban [playerId]**
Bans a player from the server (requires permission).

```bash
/aiko ban 123
```

### 🎫 7. **unban [playerId]**
Unbans a player from the server (requires permission).

```bash
/aiko unban 123
```

### ✨ 8. **tp [playerId]**
Teleports the player who executed the command to another player.

```bash
/aiko tp 123
```

### 🔄 9. **pull [playerId]**
Pulls a player to the position of the player who executed the command.

```bash
/aiko pull 123
```

### 🏙️ 10. **deleteAllPeds**
Removes all NPCs from the server (requires permission).

```bash
/aiko deleteAllPeds
```

### 🚗 11. **deleteAllVehicles**
Removes all vehicles from the server (requires permission).

```bash
/aiko deleteAllVehicles
```

### 📦 12. **deleteAllObjects**
Removes all objects from the server (requires permission).

```bash
/aiko deleteAllObjects
```

### 🔄 13. **update**
Updates the server configuration (requires `owner` permission).

```bash
/aiko update
```

### ❌ 14. **uninstall**
Uninstalls AikoAC dependencies (server console only).

```bash
/aiko uninstall
```

---

## 🔑 Permissions

Each subcommand requires a specific permission level:

- **👑 owner** - Server owner
- **🔧 administrator** - Administrator
- **🛡️ moderator** - Moderator
- **📞 support** - Support
- **🎮 user** - Regular player

---

## 📌 Notes

✔️ AikoAC **detects suspicious activities in real-time** and can take automatic actions to prevent cheating.
✔️ Some commands **cannot be executed from the server console**.
✔️ If a player **does not have permission** to execute a command, they will receive an error message.
✔️ The `/aiko` command without parameters will display the available commands.

---

## 🎯 Conclusion

**AikoAC** is a **complete and efficient** solution to ensure a **safe and cheat-free** gaming environment. With its various features, it provides **full control** over the server, protecting game integrity and facilitating administration.

🔹 **Advanced protection** against cheaters.
🔹 **Administrative tools** for efficient management.
🔹 **Robust permission system** for enhanced security.

➡️ **Keep your server safe with AikoAC!** 🚀
