# 📜 Terms of Service

**Last Updated:** January 19, 2026

## 1. Acceptance of Terms

By inviting **Auth** ("the Service") to your Discord server, or by using its features, you agree to be bound by these Terms of Service. If you do not agree to these terms, you are required to remove the Service from your server immediately.

## 2. Operation & Methodology

Auth functions as an automated security watchdog for Discord communities. Its operation is defined as follows:

* **State Reference:** The Service maintains a secure "snapshot" of your server's member population metrics.
* **Periodic Validation:** The Service performs routine integrity checks by comparing your server's current live member count against the last stored "safe" snapshot.
* **Deviation Recovery:** If the Service detects a statistically significant negative deviation (a massive drop in members) between the current state and the snapshot, it identifies the event as a security anomaly.
* **Automated Action:** Upon detection, the Service automatically initiates recovery protocols to restore the server to its nearest safe state.

## 3. Availability of Service

We strive to provide continuous uptime for the Service. However, we cannot guarantee 100% availability.

* **Service Interruptions:** The Service may experience downtime due to maintenance, updates, or issues with the Discord API. During these periods, the "Periodic Validation" checks may be delayed.
* **Data Integrity:** While we take every precaution to ensure our snapshots are accurate, we are not responsible for data loss resulting from database failures or corruption. You acknowledge that the Service is a tool to *assist* in recovery, not a guaranteed insurance policy.

## 4. Termination & Security Investigations

We reserve the right to terminate your access to the Service at any time, with or without notice, and to take necessary steps to protect the Service from abuse.

* **Violation of Terms:** If you use the Service to abuse the Discord API, harass users, or violate Discord's Community Guidelines, your access will be revoked.
* **Security Investigations & Access:** To protect the integrity of the Service, we reserve the right to investigate instances of suspected abuse or exploitation of the bot. You acknowledge and agree that in cases of suspected exploits or malicious activity, we reserve the right to **programmatically generate an invite** to access your server (including private or restricted guilds) solely for the purpose of investigation.
* **Moderation Action:** In the event of such an investigation, we reserve the right to take direct moderation action (such as blacklisting the server or banning specific users from the Service) only when strictly required to mitigate the threat or stop the abuse.
* **Right to Refuse:** We reserve the right to block the Service from any specific guild or user at our sole discretion if we deem the usage to be a risk to the Service's infrastructure.

## 5. Limitation of Liability

The Service is provided "AS IS" and "AS AVAILABLE". The developer of Auth expressly disclaim all warranties, whether express or implied. We shall not be liable for any direct, indirect, incidental, or consequential damages resulting from:

* False positives (e.g., the bot banning a user incorrectly due to a misinterpreted member drop).
* Failure to recover members (e.g., if users cannot be restored due to API limits).
* Unauthorized access to your server settings.

---

**Contact:** [Olympus Development™](https://discord.gg/pjC5pJhAfv)
