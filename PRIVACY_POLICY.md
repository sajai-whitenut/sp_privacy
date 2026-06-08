# Privacy Policy for Aegis Striker

**Last Updated:** June 8, 2026

Welcome to **Aegis Striker** (referred to below as "the App"), a futuristic 2D neon space shooter game. We respect your privacy and are committed to protecting any information that may be gathered during your use of the App. 

This Privacy Policy explains what information we collect, how we use it, and your choices regarding this information.

---

## 1. Information We Collect and Receive

### A. Personal Information
We do **not** collect any personally identifiable information (PII) such as your name, physical address, phone number, or payment details. The App is designed to function with zero requirement for personal registration or user accounts.

### B. Automatically Collected Data & Network Information
* **Network Status & Connectivity:** Because Aegis Striker is an **Online-Only** game, the App monitors your network state (Wi-Fi, Cellular, or Ethernet) to ensure an active link to the online system.
* **Game Performance & State Data:** The App utilizes a local SQLite database (via Android Room) on your device to keep track of local game statistics, campaign scores, and high-score leaderboards. This data remains on your physical device and is not uploaded to external servers.

### C. Third-Party API Integrations
Aegis Striker integrates with the **Google Gemini API** to provide dynamic, AI-assisted tactical advice, game analysis, and fluid difficulty adjustments during gameplay. 
* When the App requests AI advice, gameplay state markers (such as current score, wave reached, target accuracy, and damage indicators) are transmitted securely to the Gemini API servers.
* No personal, identifying, or device-specific sensitive data is sent to the Gemini API. 
* For more information on how Google manages query data, please refer to the [Google Privacy Policy](https://policies.google.com/privacy).

---

## 2. Permissions Required by the App

To provide a fully synchronized online gameplay experience, the App requests the following Android system permissions:
* `android.permission.INTERNET`: Required to verify battle-net links and transmit high-energy tactical analysis queries to the secure Google Gemini API.
* `android.permission.ACCESS_NETWORK_STATE`: Required to monitor active network connections and gracefully lock/unlock play options based on internet availability.

---

## 3. How We Use the Collected Data

Any information collected or processed by the App is strictly used to:
1. Maintain real-time gaming synchronization and gameplay stability.
2. Deliver responsive tactical dialogue, difficulty tailoring, and gameplay logs using deep-learning models.
3. Save local achievements, score counters, and unlockable status indicators on your device.

---

## 4. Data Sharing and Disclosure

We **do not sell, trade, or rent** any data to third-party advertisers, data brokers, or marketing networks.
We only share technical gameplay telemetry with:
* **Google (Gemini API):** Solely for executing real-time in-game generative dialogue/difficulty updates.

We may also disclose data if required to do so by applicable law, in response to a valid legal subpoena, or to protect the safety and integrity of our systems.

---

## 5. Security of Your Data

We implement industry-standard commercial security measures to protect device telemetry. Since your high scores and progress are preserved within a secure local SQLite sandboxed directory, they are protected by standard Android operating system-level application boundary controls.

---

## 6. Children's Privacy (COPPA & GDPR compliance)

Aegis Striker is a general-audience space shooter. We do not knowingly compile or request data from children under the age of 13 (or under the age of 16 in the European Union). If you are a parent or guardian and believe that your child has provided us with any data, please contact us immediately so we can inspect and safely purge any records.

---

## 7. Changes to This Privacy Policy

We may modify or update this Privacy Policy from time to time. We will post any amendments directly on this page and revise the "Last Updated" date at the top. We encourage you to review this policy periodically to stay informed about how we maintain data security.

---

## 8. Contact Us

If you have any questions, comments, or concerns about this Privacy Policy or our data practices, please contact us at:

* **Developer Email:** sajai.whitenut@gmail.com
* **Project Reference:** Aegis Striker / Space Shooter
