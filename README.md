# DayQuest — iPhone Web App

A minimal morning (cream/orange) and night (navy/blue) routine tracker.

## Publish on GitHub Pages

1. Create a **public** repository named `dayquest` on GitHub.
2. Select **Add file → Upload files** and upload `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, and `icon-512.png` to the repository root. Commit changes.
3. Open repository **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**. Choose **main** and **/(root)** and click **Save**.
4. Wait for deployment. Your URL should be `https://YOUR-USERNAME.github.io/dayquest/` (replace username). If your repo has a different name, the URL path changes.
5. On iPhone, open the URL in **Safari**, tap **Share → Add to Home Screen → Add**. Open DayQuest from the new icon.

## Notes
- Data is saved locally on the device using `localStorage`. No account or cross-device syncing.
- Daily checkboxes reset when the app is opened on a new local calendar day.
- The start times are labels/settings, not alarms. No scheduled notifications or Lock Screen widget.
- The PWA can work offline after its first successful load.
- If you clear browser/app site data or remove the app, you may lose saved tasks.
