# Privacy Policy – Simple CRM Mail Merge for Gmail

**Last updated:** March 17, 2026

Simple CRM Mail Merge for Gmail (“the extension”) is a Gmail-native CRM tool designed to help users manage contacts, track opportunities, and run mail merge campaigns using Google Sheets and the Google Apps Script Mail service. 

We take privacy seriously and collect only the minimum data required for the extension to function.

---

### 1. Data We Access (Google OAuth)
The extension uses Google OAuth to access specific data to provide its core services. We adhere to the principle of **"Least Privilege,"** accessing only what is necessary:

* **Google Sheets (`.../auth/spreadsheets`):** Used to read and write CRM data and campaign results within spreadsheets you designate.
* **Google Drive (`.../auth/drive.file`):** Used strictly to create and edit specific spreadsheet files created by the extension.
* **User Identity (`.../auth/userinfo.email`):** Used to identify your account for subscription management and trial tracking.
* **Google Apps Script Mail Service (`.../auth/script.send_mail`):** Used solely to execute mail merge campaigns that you manually trigger. This allows the extension to send emails via Apps Script without needing access to your full Gmail inbox.

---

### 2. Gmail (In-Page Context)
The extension runs inside your Gmail browser tab to help associate open email threads with CRM records.
* The extension may read limited Gmail page context, such as the **sender email address** and **email subject**, solely for CRM matching purposes.
* We do **not** read the body content of your emails for CRM matching.
* This data is processed locally in your browser and is never transmitted to any external server.

---

### 3. Google API Limited Use Disclosure
Simple CRM Mail Merge's use and transfer to any other app of information received from Google APIs will adhere to the **[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy)**, including the Limited Use requirements.

**We do NOT:**
* Use Google user data for advertising.
* Sell or share user data with third-party data brokers.
* Use data for any purpose outside the core CRM and mail merge functionality.

---

### 4. Data Storage
* **Locally (on your device):** The extension stores CRM metadata (Opportunity records, pipeline stages) using `chrome.storage.local`. This data remains on your device and is never sent to our servers.
* **On Google Sheets:** Your Mail Merge campaign data (recipient lists and send status) is stored within the specific Google Sheets files that you control. 

---

### 5. Mail Merge Sending Mechanism
Mail merge campaigns are handled via a "Private Bridge" using Google Apps Script. 
* Sending is only initiated when you explicitly click "Send" or "Test Send."
* Because we use the `script.send_mail` scope, the extension **cannot** read your existing emails, search your inbox, or delete messages. 
* Your email content remains private and is never accessed or stored by the developers.

---

### 6. Data Sharing & Third Parties
We do **not** operate a backend server and do **not** use third-party analytics or advertising trackers. Data is only exchanged with Google Services via encrypted HTTPS connections when you explicitly trigger a feature.

---

### 7. Export and Deletion
* **Export:** You can export your CRM data at any time via your associated Google Sheets.
* **Deletion:** Uninstalling the extension removes all locally stored metadata. Any Google Sheets created must be manually deleted from your Google Drive.

---

### 8. Security
The extension uses Google-approved OAuth2 protocols and Chrome’s secure storage APIs. All communication with Google services is encrypted using industry-standard HTTPS.

---

### 9. Contact
If you have any questions about this policy or the technical implementation of our Mail Merge "bridge," please contact:

**Simple CRM Mail Merge for Gmail** 📧 Email: hello@simple-crm.uk  
🌐 Website: [https://simple-crm.uk](https://simple-crm.uk)
