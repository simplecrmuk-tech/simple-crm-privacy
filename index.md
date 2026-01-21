# Privacy Policy – Simple CRM Mail Merge for Gmail

**Last updated:** 20 January 2026

**Simple CRM Mail Merge for Gmail** (“the extension”) is a Gmail-native CRM tool designed to help users manage contacts, track opportunities, and run mail merge campaigns using Google Sheets and Gmail drafts.

We take privacy seriously and collect only the minimum data required for the extension to function.

---

## Data We Access

### Gmail (in-page)
The extension runs inside Gmail to detect the currently open email thread and help associate it with CRM records.

- The extension may read limited Gmail page context such as **sender email address** and **email subject** for matching purposes.
- **We do not use the Gmail API.**
- **We do not send emails from the extension.**
- **We do not transmit Gmail content to any external server.**

### Google Account (OAuth)
The extension uses Google OAuth to access:
- **Google Sheets** – to create and manage mail merge campaign spreadsheets.
- **Google Drive (file-level access only: `drive.file`)** – to create, copy, and access files the user explicitly creates or uses through the extension.

The extension cannot access your entire Google Drive.

---

## Data We Store

### Locally (on your device)
The extension stores the following data using Chrome extension local storage (`chrome.storage.local`):

- Contacts  
- Opportunity (pipeline) records  
- Lists, stages, and settings  
- Trial and entitlement state  

This data remains on your device unless you explicitly export it or choose to use Google Sheets features.

---

## Mail Merge Sending

- Mail merge campaigns are created as Google Sheets documents.
- Sending is initiated from the **Google Sheets menu** using a bound Google Apps Script included with the campaign template.
- The extension itself does **not** send emails and does **not** perform automated background sending.

---

## Data We Do Not Collect

We do **not**:
- Operate a backend server
- Store your CRM data remotely
- Sell, rent, or share personal data
- Use third-party analytics or advertising trackers

---

## Data Sharing

Data is not shared with third parties, except where required to interact with Google services (Sheets and Drive) when you explicitly use those features.

---

## Export and Deletion

- You may export your data at any time using the extension’s export features.
- Uninstalling the extension removes all locally stored data.

---

## Security

The extension uses Google-approved APIs and Chrome extension APIs. All data transmitted to Google services is encrypted in transit using HTTPS.

---

## Changes

If this privacy policy changes, an updated version will be published before any new data practices take effect.

---

## Contact

If you have questions about this policy, please contact:

**Simple CRM Mail Merge for Gmail**  
**Email:** support@simple-crm.uk
