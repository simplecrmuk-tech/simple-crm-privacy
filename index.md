Privacy Policy – Simple CRM Mail Merge for Gmail
Last updated: March 17, 2026

Simple CRM Mail Merge for Gmail (“the extension”) is a Gmail-native CRM tool designed to help users manage contacts, track opportunities, and run mail merge campaigns using Google Sheets and Gmail drafts.

We take privacy seriously and collect only the minimum data required for the extension to function.

1. Data We Access and Purpose
Google Account (OAuth)

The extension uses Google OAuth to access the following specific data to provide its core services:

Google Sheets (.../auth/spreadsheets): Used to read and write CRM data, contact lists, and campaign results within spreadsheets you designate.

Google Drive (.../auth/drive.file): Used strictly to create, edit, and save specific spreadsheet files created by the extension. We cannot access your entire Google Drive.

User Identity (.../auth/userinfo.email): Used to identify your account for subscription management and to personalize the CRM experience.

Gmail (.../auth/gmail.send): Used solely to execute mail merge campaigns that you manually trigger. This allows the extension (via Google Apps Script) to send emails on your behalf based on your selected Gmail drafts.

Gmail (in-page)

The extension runs inside Gmail to detect the currently open email thread and help associate it with CRM records.

The extension may read limited Gmail page context such as sender email address and email subject for matching purposes.

We do not transmit Gmail content to any external server.

2. Google API Limited Use Disclosure
Simple CRM Mail Merge's use and transfer to any other app of information received from Google APIs will adhere to the Google API Service User Data Policy, including the Limited Use requirements.

We do not use Google user data to serve advertisements or for any purpose other than providing the CRM and Mail Merge services described.

3. Data We Store
Locally (on your device)

The extension stores the following data using Chrome extension local storage (chrome.storage.local):

Contacts

Opportunity (pipeline) records

Lists, stages, and settings

Trial and entitlement state

This data remains on your device unless you explicitly export it. We do not operate a backend server and do not store your CRM data remotely.

4. Mail Merge Sending
Mail merge campaigns are created as Google Sheets documents.

Sending is initiated from the extension or the Google Sheets menu using a Google Apps Script bridge that runs under your own Google account permissions.

The content of your emails remains private to your Google account and is never accessed by the developers.

5. Data Sharing
Data is not shared with third parties, except where required to interact with Google services (Sheets, Drive, and Gmail) when you explicitly use those features. We do not sell, rent, or use third-party analytics/advertising trackers.

6. Export and Deletion
You may export your data at any time using the extension’s export features.

Uninstalling the extension removes all locally stored data. Data stored in Google Sheets must be deleted manually within your Google Drive.

7. Security
The extension uses Google-approved APIs and Chrome extension APIs. All data transmitted to Google services is encrypted in transit using HTTPS.

8. Changes
If this privacy policy changes, an updated version will be published before any new data practices take effect.

9. Contact
If you have questions about this policy, please contact:

Simple CRM Mail Merge for Gmail  
Email: hello@simple-crm.uk

Website: https://simple-crm.uk
