# Privacy Policy for Meow Bot

*Last Updated: September 16, 2026*

This policy outlines how **Meow Bot** collects, uses, and safeguards data provided by Discord servers and users.

---

### 1. Data We Collect
To function properly, Meow Bot collects and processes minimal server configuration data:
* **Guild Metadata:** Guild IDs, channel IDs, and role IDs configured for features (e.g., ticket panels, log destinations).
* **Temporary Message Snippets:** Recent deleted/edited message content is held ephemerally in RAM caches exclusively to power snipe/audit log commands and is overwritten continuously.
* **Audit Identifiers:** User IDs and action timestamps for support ticket interactions and event audit tracking.

### 2. Data We Do NOT Collect
* We do not read, record, or store general private message conversations.
* We do not store personal billing details, payment card information, or physical addresses.
* We do not sell or lease any user data to third-party advertisers.

### 3. Third-Party Integrations
* **ScriptBlox:** Script searches interact directly with public query interfaces to return game script listings. No private user telemetry is shared with ScriptBlox.
* **Discord API:** Operational data complies directly with the Discord Developer Policy.

### 4. Data Retention & Deletion
* Server configurations persist in MongoDB until the Bot is removed from the server or a server administrator requests an explicit purge.
* You may request data deletion by contacting staff in our official [Support Server](https://discord.gg/PaqFDgWe4J).
