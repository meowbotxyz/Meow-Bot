# 📖 Meow Bot Official Documentation

Welcome to the comprehensive command and setup documentation for **Meow Bot**.

---

## 🛠️ Configuration & Core Management

### 1. Web Dashboard / Docs
* URL Dashboard: [https://meowbot.xyz](https://meowbot.xyz)
* URL Docs: [https://meowbot.xyz/docs](https://meowbot.xyz/docs)
* Connect your Discord account to visually review logs, configure channels, and adjust bot preferences without typing commands.

### 2. AutoMod & Audit Logging
Monitor server events in designated channels:

| Command | Usage | Description |
| :--- | :--- | :--- |
| `?automod status` | `?automod status` | Displays all configured log categories and current channels. |
| `?setlog` | `?setlog <category> #channel` | Binds an event category to a specific text channel. |
| `?unsetlog` | `?unsetlog <category>` | Disables logging for that category. |
| `?automod` | `?automod <category> <log/off> [#ch]` | Combined command to view, set, or disable logging. |

**Available Categories:**
* `message` — Deleted and edited messages.
* `voice` — Joins, leaves, and channel switches.
* `channel` — Created and removed channels.
* `role` — Created and deleted roles.
* `join` / `leave` — Member joins and leaves/kicks.
* `nickname` — Nickname modifications.
* `server` — Guild name and icon updates.

---

## 🎫 Ticket System Setup

### Quick Setup Wizard
Use `/ticket setup quicksetup` to let the bot automatically create ticket categories, channels, and staff roles.

### AI Ticket Engine
Use `/ticket setup aiticket` to activate automated responses and interactive issue routing before notifying staff members.

### Staff Ticket Controls
* `/ticket action close` — Closes the active ticket channel and generates a transcript.
* `/ticket panel custompanel` — Opens the panel editor to design custom embeds with up to 25 buttons.

---

## 🔊 VoiceMaster (Join-to-Create)

1. Designate a voice channel as the VoiceMaster hub.
2. When a member connects to the hub, the bot dynamically creates a private temporary voice channel for them.
3. The temporary room is automatically purged when empty.

---

## 📜 ScriptBlox Search

Find Roblox scripts directly within Discord:

```text
?script-search <game/keyword>
