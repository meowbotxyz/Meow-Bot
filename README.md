<div align="center">

# 🐾 Meow Bot

**A feature-rich, high-performance Discord Bot built with Discord.js v14, Express & MongoDB**

[![Discord.js](https://img.shields.io/badge/Discord.js-v14.x-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.js.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18.x%2B-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

[🌐 Web Dashboard](https://meowbot.xyz) • [💬 Support Server](https://discord.gg/PaqFDgWe4J) • [➕ Invite Bot](https://discord.com/oauth2/authorize?client_id=1491052906496131296)

---

<img src="./assets/banner.png" alt="Meow Bot Banner" width="100%" />

</div>

## 📌 Overview

**Meow Bot** is a modern, multipurpose Discord bot designed to empower communities with advanced server automation, security monitoring, and interactive utilities. Featuring a full-fledged ticket support desk, granular AutoMod audit logging, dynamic voice channels, in-chat Roblox script searching, and a centralized web dashboard, Meow Bot provides everything required to manage and engage a Discord server efficiently.

---

## ✨ Key Features

### 🌐 Web Dashboard Integration
* **Visual Management:** Configure server-specific preferences, manage features, and review activity logs directly on [meowbot.xyz](https://meowbot.xyz).
* **Live Synchronization:** Seamless data bridge between Discord servers and MongoDB storage.

### 🛡️ Comprehensive AutoMod & Audit Logging
* **Message Tracking:** Logs edited and deleted messages with automatic partial caching to prevent missing metadata.
* **Voice Activity:** Real-time embeds for members joining, leaving, or switching voice channels.
* **Role & Channel Audits:** Logs newly created, updated, or deleted server roles and text/voice channels.
* **Member & Guild Changes:** Tracks member joins, leaves/kicks, nickname adjustments, and server name/icon modifications.

### 🎫 Advanced Support & AI Ticket Desk
* **Dual Ticket Engines:** Standard categorized buttons or automated keyword-responsive AI ticket workflows.
* **Custom Ticket Panels:** Build customized panels (`/ticket panel custompanel`) with up to 25 interactive buttons.
* **Staff Controls:** Claim, unclaim, priority tags, transfer tickets, close with reasons, and generate transcripts.
* **Partnership Automation:** Auto-detects partnership requests and triggers dedicated advertising sequences.

### 🔊 VoiceMaster (Join to Create)
* Automated voice room creation when members enter a designated hub.
* Auto-deletes empty temporary channels to keep server lists clean.

### 📜 ScriptBlox Search Engine
* Query Roblox scripts straight from the ScriptBlox directory with pagination.
* Displays script metadata including view counts, verified status, key requirements, and patch alerts.
* Interactive **Copy Script** modal for quick execution.

---

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Runtime** | Node.js (v18+) |
| **Framework** | Discord.js v14 |
| **Database** | MongoDB with Mongoose ODM |
| **Web Server** | Express.js (Dashboard & Webhooks) |
| **UI Components** | Discord Components V2 / EmbedBuilder / ActionRows / Modals |

---

## 🚀 Installation & Setup

### 1. Prerequisites
* Node.js v18.0.0 or higher
* MongoDB connection URI (MongoDB Atlas or self-hosted)
* Discord Application Token & Client ID from the [Discord Developer Portal](https://discord.com/developers/applications)

### 2. Clone the Repository
```bash
git clone [https://github.com/phongfg384-maker/Meow-Bot.git](https://github.com/phongfg384-maker/Meow-Bot.git)
cd Meow-Bot
