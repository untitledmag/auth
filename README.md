# ⚖️ Auth | Legal & Policies

**Official Policy Hub for the Auth Discord Bot.**

This repository serves as the home for the Terms of Service, Privacy Policy, and operational documentation for **Auth**. By inviting or using Auth, you agree to the standards and practices outlined in the documents located here.

---

## 🤖 About Auth

**Auth** is an automated security tool designed to protect Discord servers from malicious "nuking" or mass-removal events.

### How It Works (Simplified)

To keep your server safe without being intrusive, Auth uses a **"Snapshot & Compare"** system:

1. **Routine Checks:** At periodic intervals, the bot wakes up to check the health of your server.
2. **Data Comparison:** It compares your current member count against the last known "safe" record.
3. **Automatic Recovery:** If the system detects a **drastic drop** in members compared to the previous record—indicating a likely attack or raid—it automatically initiates recovery protocols to restore the server and notify the guild's owner to its safe state.

> **Note:** This system is designed to ignore normal, day-to-day member leaves. It only triggers when a significant portion of the community is lost within a short timeframe.

---

## 📄 Policy Documents

Please review the following documents to understand your rights and responsibilities.

### 📜 [Terms of Service (TOS.md)](./TOS.md)

* **What it covers:** Usage rules, liability limitations, and acceptable use policies.
* **Key point:** You accept that the bot performs administrative actions (like channel creation or role changes) automatically when a threat is detected.

### 🔒 [Privacy Policy (PRIVACY.md)](./PRIVACY.md)

* **What it covers:** Data collection, storage, and retention.
* **Key point:** We store "snapshots" of your server's member counts and role states solely for the purpose of comparison and recovery.

---

## 🔗 Quick Links

* **[Invite Auth](https://discord.com/oauth2/authorize?client_id=1237912969392951348&permissions=8&integration_type=0&scope=bot)**
* **[Support Server](https://discord.gg/pjC5pJhAfv)** – *For queries, appeals, bug reports, or data deletion requests.*

*This repository and its documents are maintained by Olympus Development™ and untitledmag. We reserve rights to change these at any time. Any major changes in terms of service or privacy policy will be announced in support server.*
