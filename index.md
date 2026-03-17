<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - Simple CRM Mail Merge</title>
    <style>
        body { font-family: -apple-system, Segoe UI, Helvetica, Arial, sans-serif; line-height: 1.6; color: #24292e; max-width: 850px; margin: 0 auto; padding: 40px 20px; }
        h1 { font-size: 2em; padding-bottom: 0.3em; border-bottom: 1px solid #eaecef; }
        h2 { font-size: 1.5em; margin-top: 24px; padding-bottom: 0.3em; border-bottom: 1px solid #eaecef; }
        hr { height: 0.25em; padding: 0; margin: 24px 0; background-color: #e1e4e8; border: 0; }
        code { padding: 0.2em 0.4em; margin: 0; font-size: 85%; background-color: rgba(27,31,35,0.05); border-radius: 3px; font-family: SFMono-Regular, Consolas, Liberation Mono, Menlo, monospace; }
        .last-updated { color: #586069; }
        a { color: #0366d6; text-decoration: none; }
        a:hover { text-decoration: underline; }
        .contact-section { background: #f6f8fa; border: 1px solid #d1d5da; padding: 15px; border-radius: 6px; margin-top: 30px; }
    </style>
</head>
<body>

    <h1>Privacy Policy – Simple CRM Mail Merge for Gmail</h1>
    <p class="last-updated"><strong>Last updated:</strong> March 17, 2026</p>

    <p><strong>Simple CRM Mail Merge for Gmail</strong> (“the extension”) is a Gmail-native CRM tool designed to help users manage contacts, track opportunities, and run mail merge campaigns using Google Sheets and Gmail drafts.</p>
    <p>We take privacy seriously and collect only the minimum data required for the extension to function.</p>

    <hr>

    <h2>Data We Access</h2>

    <h3>Google Account (OAuth)</h3>
    <p>The extension uses Google OAuth to access the following specific data to provide its core services:</p>
    <ul>
        <li><strong>Google Sheets (<code>.../auth/spreadsheets</code>):</strong> Used to read and write CRM data and campaign results.</li>
        <li><strong>Google Drive (<code>.../auth/drive.file</code>):</strong> Used strictly to create and edit spreadsheet files created by the extension. We cannot access your entire Drive.</li>
        <li><strong>User Identity (<code>.../auth/userinfo.email</code>):</strong> Used to identify your account for subscription management.</li>
        <li><strong>Gmail (<code>.../auth/gmail.send</code>):</strong> Used solely to execute mail merge campaigns that you manually trigger.</li>
    </ul>

    <h3>Gmail (in-page)</h3>
    <p>The extension runs inside Gmail to detect the currently open email thread and associate it with CRM records.</p>
    <ul>
        <li>The extension may read limited context such as <strong>sender email address</strong> and <strong>subject</strong> for matching.</li>
        <li><strong>We do not transmit Gmail content to any external server.</strong></li>
    </ul>

    <hr>

    <h2>Google API Limited Use Disclosure</h2>
    <p>Simple CRM Mail Merge's use and transfer to any other app of information received from Google APIs will adhere to the <strong><a href="https://developers.google.com/terms/api-services-user-data-policy" target="_blank">Google API Service User Data Policy</a></strong>, including the Limited Use requirements.</p>

    <hr>

    <h2>Data We Store</h2>
    <p><strong>Locally (on your device):</strong> The extension stores Contacts, Opportunity records, and settings using <code>chrome.storage.local</code>. This data remains on your device. We do not operate a backend server.</p>

    <hr>

    <h2>Security</h2>
    <p>The extension uses Google-approved APIs. All data transmitted to Google services is encrypted in transit using HTTPS.</p>

    <div class="contact-section">
        <h2>Contact</h2>
        <p>If you have questions about this policy, please contact:</p>
        <p><strong>Simple CRM Mail Merge for Gmail</strong><br>
        <strong>Email:</strong> <a href="mailto:hello@simple-crm.uk">hello@simple-crm.uk</a><br>
        <strong>Website:</strong> <a href="https://simple-crm.uk">https://simple-crm.uk</a></p>
    </div>

</body>
</html>
