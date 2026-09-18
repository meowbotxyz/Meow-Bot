
<div align="center">

# 🎨 Meow Bot — Emoji & Asset Repository

**Centralized Discord Emoji & Vector Asset Library powering Meow Bot UI/UX**

[![Discord.js](https://img.shields.io/badge/Discord.js-Assets-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.js.org/)
[![Assets](https://img.shields.io/badge/Assets-Static%20%26%20Animated-FEE75C?style=for-the-badge&logo=appveyor&logoColor=black)](https://meowbot.xyz)
[![Design](https://img.shields.io/badge/Format-PNG%20%7C%20GIF%20%7C%20SVG-00C7B7?style=for-the-badge&logo=figma&logoColor=white)](https://meowbot.xyz)
[![Status](https://img.shields.io/badge/Access-Private%20%2F%20Internal-red?style=for-the-badge&logo=git&logoColor=white)](LICENSE)

[🌐 Web Dashboard](https://meowbot.xyz) • [💬 Support Server](https://discord.gg/PaqFDgWe4J) • [➕ Invite Bot](https://discord.com/oauth2/authorize?client_id=1491052906496131296)

---

</div>

> **Notice:** This repository contains the official graphic assets, custom application emoji manifests, and icon identifiers utilized across the Meow Bot Discord Client and Web Dashboard.

---

## 📌 Asset Overview

This repository serves as the single source of truth for all visual identifiers across the ecosystem:
* **System Emojis:** Interactive UI icons used in embed headers, button labels, and system status monitors.
* **AutoMod & Audit Logs:** Indicator badges for message mutations, voice channel events, and role updates.
* **Music & Multimedia:** Player control icons (play, pause, skip, loop, volume, filters).
* **Game Utilities:** ScriptBlox badges, verified script marks, and execution indicators.

---

## 🗂️ Directory Structure

```text
Meow-Bot/
├── Emoji
│  ├── Meow Bot Emoji.zip
│  └── README.md
├── assets
│  └── banner.png
├── DOCS.md
├── LICENSE
├── PRIVACY_POLICY.md
├── README.md
└── 

```
## 📋 Core Emoji Manifest & Identifiers
| Category | Identifier | Type | Preview | Raw Discord Format |
|---|---|---|---|---|
| **System** | meow_success | Static | ✅ | <:meow_success:123456789012345678> |
| **System** | meow_error | Static | ❌ | <:meow_error:123456789012345679> |
| **System** | meow_loading | Animated | 🔄 | <a:meow_loading:123456789012345680> |
| **Audit** | log_message_delete | Static | 🗑️ | <:log_delete:123456789012345681> |
| **Audit** | log_voice_join | Static | 🔊 | <:log_voice_join:123456789012345682> |
| **Music** | music_play | Static | ▶️ | <:music_play:123456789012345683> |
| **Music** | music_eq | Animated | 📊 | <a:music_eq:123456789012345684> |
| **ScriptBlox** | blox_verified | Static | 🛡️ | <:blox_verified:123456789012345685> |
## 🔌 Integration & Code Manifests
<div align="center">
<a href="#-javascript--nodejs-mappingsemojisjs"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JS" /></a>
<a href="#-typescript-mappingsemojists"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TS" /></a>
<a href="#-python-mappingsemojispy"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Py" /></a>
<a href="#-json-mappingsemojisjson"><img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON" /></a>
</div>
### 🟡 JavaScript / Node.js (mappings/emojis.js)
> *Direct import for Discord.js handlers and EmbedBuilder*
> 
```javascript
module.exports = {
  system: {
    success: '<:meow_success:123456789012345678>',
    error: '<:meow_error:123456789012345679>',
    loading: '<a:meow_loading:123456789012345680>'
  },
  automod: {
    delete: '<:log_delete:123456789012345681>',
    voiceJoin: '<:log_voice_join:123456789012345682>'
  },
  music: {
    play: '<:music_play:123456789012345683>',
    equalizer: '<a:music_eq:123456789012345684>'
  },
  scriptblox: {
    verified: '<:blox_verified:123456789012345685>'
  }
};

```
### 🔵 TypeScript (mappings/emojis.ts)
> *Type-safe mappings for Nuxt 3 Dashboard & TypeScript bot core*
> 
```typescript
export interface EmojiCategory {
  [key: string]: string;
}

export const Emojis = {
  system: {
    success: '<:meow_success:123456789012345678>',
    error: '<:meow_error:123456789012345679>',
    loading: '<a:meow_loading:123456789012345680>'
  },
  automod: {
    delete: '<:log_delete:123456789012345681>',
    voiceJoin: '<:log_voice_join:123456789012345682>'
  },
  music: {
    play: '<:music_play:123456789012345683>',
    equalizer: '<a:music_eq:123456789012345684>'
  },
  scriptblox: {
    verified: '<:blox_verified:123456789012345685>'
  }
} as const;

export type EmojiMap = typeof Emojis;

```
### 🐍 Python (mappings/emojis.py)
> *Discord.py and Disnake dictionary mappings*
> 
```python
EMOJIS = {
    "system": {
        "success": "<:meow_success:123456789012345678>",
        "error": "<:meow_error:123456789012345679>",
        "loading": "<a:meow_loading:123456789012345680>"
    },
    "automod": {
        "delete": "<:log_delete:123456789012345681>",
        "voice_join": "<:log_voice_join:123456789012345682>"
    },
    "music": {
        "play": "<:music_play:123456789012345683>",
        "equalizer": "<a:music_eq:123456789012345684>"
    },
    "scriptblox": {
        "verified": "<:blox_verified:123456789012345685>"
    }
}

```
### 📄 JSON (mappings/emojis.json)
> *Universal cross-platform configuration file*
> 
```json
{
  "system": {
    "success": "<:meow_success:123456789012345678>",
    "error": "<:meow_error:123456789012345679>",
    "loading": "<a:meow_loading:123456789012345680>"
  },
  "automod": {
    "delete": "<:log_delete:123456789012345681>",
    "voiceJoin": "<:log_voice_join:123456789012345682>"
  },
  "music": {
    "play": "<:music_play:123456789012345683>",
    "equalizer": "<a:music_eq:123456789012345684>"
  },
  "scriptblox": {
    "verified": "<:blox_verified:123456789012345685>"
  }
}

```
## ⚡ Automated Emoji Deployment (scripts/uploader.js)
To upload all static and animated icons to a designated Discord Application Guild:
```bash
# Configure bot token and destination emoji guild
export DISCORD_TOKEN="your_bot_token"
export EMOJI_GUILD_ID="your_storage_guild_id"

# Run automated deployment
node scripts/uploader.js

```
## 👥 Asset Designers & Infrastructure

<div align="center">

| Maintainer | Role | Responsibilities |
|---|---|---|
| **Ws ZieeLord** (@4qg1) | **Lead Architect & UI Designer** | Icon Vectorization, Branding Assets & Dashboard Theme Sync |
| **NNK** (@nnk_cool1) | **System Integrator** | Asset Deployment Automation & Bot Engine Mapping Integration |
</div>

<div align="center">

Copyright © 2026 **Ws ZieeLord & NNK**. All rights reserved.
*Internal design assets for Meow Bot. Do not redistribute without authorization.*
</div>
