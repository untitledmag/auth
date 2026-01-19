# 🔒 Privacy Policy

**Last Updated:** January 19, 2026

This Privacy Policy explains how **Auth** ("the Service," "we," "us") collects, stores, and processes information when you interact with our bot or authorize it via Discord. We are committed to protecting your data while providing a robust security environment for your community.

---

## 1. Information We Collect

To function as a recovery and restoration system, Auth collects the following types of data:

### A. OAuth2 Access Tokens

When you authorize Auth, we collect and store your **Discord OAuth2 Access Token** and **Refresh Token**.

* **Scope:** We specifically request the `guilds.join` scope.
* **Purpose:** These tokens are used as a "digital key" to restore your membership to a server if you are removed during a security breach.

### B. Server Integrity Snapshots

To detect server anomalies, the Service periodically records "snapshots" of a guild's state. This includes:

* **Current Member Count:** The total number of users present at the time of the check.
* **User Metadata:** A list of User IDs associated with their respective Role IDs and Nicknames.
* **Guild Identity:** Guild ID, Guild Name, and designated notification channel IDs.

### C. System Logs

We may collect temporary logs regarding bot performance, including timestamps of integrity checks and records of triggered recovery events.

---

## 2. How We Use Your Data

### A. Anomaly Detection & Comparison

Auth utilizes a **Snapshot & Compare** methodology. At routine intervals, the system checks the live member count. If the system detects a **significant deviation** that exceeds our internal safety margins (indicating a mass-loss event), the Service automatically initiates recovery protocols.

### B. Automatic Restoration

During a recovery event, we use stored **Access Tokens** to automatically rejoin authorized users to the server and utilize **Snapshot Data** to restore their roles and nicknames instantly.

### C. Security Investigations

As per our Terms of Service, we reserve the right to investigate suspected exploits of the Service. This may involve the programmatic generation of a server invite or the analysis of guild metadata to identify and mitigate malicious activity or bot abuse.

---

## 3. Data Security & Encryption

We prioritize the security of the credentials entrusted to us:

* **Encryption at Rest:** All OAuth2 Access and Refresh tokens are stored using **AES-256 encryption**.
* **Access Control:** Data is processed programmatically. Access by developers is restricted to instances of critical system failure or verified security investigations.
* **No Third-Party Sharing:** We do not sell, trade, or distribute your data or tokens to any third parties or external services.

---

## 4. Data Retention & Deletion

* **Snapshots:** Server snapshots are not permanent history; they are overwritten during subsequent integrity cycles to ensure the baseline remains current.
* **Tokens:** Tokens are stored until they are revoked by the user, expire, or until the Service is removed from the server.
* **Manual Deletion:** * **Users:** You may revoke Auth's access at any time via **Discord Settings > Authorized Apps**.
* **Server Owners:** To request a full purge of all guild-related data from our database, please contact our support team.


---

## 5. Third-Party Services

Auth operates within the **Discord** ecosystem. By using this Service, you are also subject to the [Discord Privacy Policy](https://discord.com/privacy). We are not responsible for how Discord handles your data outside of our specific bot operations.

---

## 6. Contact Us

If you have questions regarding this policy or wish to exercise your data rights, please join our **[Support Server](https://discord.gg/pjC5pJhAfv)** and create a ticket.
