# CareFlow v2 — support workers & management

A responsive, offline-capable **demo** care-management progressive web app, independently created and **not affiliated with ShiftCare**.

## Features
- **Management view:** dashboard, team member directory, client records, create/edit/delete scheduled shifts, assign a worker, filter team roster, progress notes, timesheets and CSV export.
- **Support-worker view:** switch between fictional worker profiles, see assigned shifts and relevant clients, clock in/out, complete shift tasks, create progress notes, review hours.
- Device-local data persists in browser storage, with JSON backup/restore and demo reset.
- Demo migration from the earlier CareFlow v1 browser storage on the same origin/device.

## Publish on GitHub Pages
1. Extract the ZIP, open the `careflow` folder and upload the **contents** (not the folder itself) to the root of the GitHub repository. Keep `index.html`, `app.js`, `style.css`, icons, manifest and `sw.js` together.
2. Go to repository **Settings → Pages → Build and deployment**, select **Deploy from a branch**, `main`, `/ (root)`, Save.
3. Open your GitHub Pages address in **Safari** on an iPhone, then **Share → Add to Home Screen**.
4. The top-right role switcher changes between **Manager** and **Worker** demos. In worker mode, select a fictional worker from the dashboard or Settings.

You can test locally by opening `index.html` or by running `python -m http.server 8000` in the folder and opening `http://localhost:8000`.

## IMPORTANT: Demo safety and limitations
**Do not enter actual client names, contact information, addresses, progress notes, disability records, health information or NDIS participant data.** Local browser storage is not a secure multiuser database. The role switcher is a UI demonstration, **not access control or authentication**. Data does **not** sync across staff or devices; each browser has separate data. Time entries are local device timestamps, not verified attendance. No real staff logins, encryption at rest, audit trail, GPS verification, staff notifications, payments, NDIS claims, official compliance verification, or clinical escalation workflows. Real deployment requires a secure backend, authenticated permissions, data protection, backups and professional privacy/security/compliance review.
