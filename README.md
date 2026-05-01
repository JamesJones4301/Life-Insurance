# Freedom Wealth Strategies Life Insurance Form

Static client intake form for Vercel. Submits responses to a Google Apps Script web app, which appends rows to the connected Google Sheet.

Setup summary:
1. Paste the Apps Script code from ChatGPT into Extensions > Apps Script inside the Google Sheet.
2. Deploy the Apps Script as a Web App.
3. Paste the Web App URL into `index.html` as `SCRIPT_URL`.
4. Connect this repo to Vercel and deploy.

Security note: this form includes sensitive financial and health fields. Use least-privilege collection, restrict Sheet access, and confirm compliance requirements before collecting SSN or bank data.