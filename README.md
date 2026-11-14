# CareFlow — care management demo

A mobile-first, installable prototype inspired by common care-management workflows, independently built and **not affiliated with ShiftCare**.

## Features
- Dashboard and weekly roster
- Add/edit client profiles
- Create/edit/delete shifts
- Clock in/out and task checklist
- Progress notes
- Timesheets, CSV download
- JSON backup/restore
- Local-first data storage, iPhone home-screen installation

## Run and publish
Upload all files (including icons and `sw.js`) to the root of a GitHub repository. In Settings → Pages, choose **Deploy from a branch** → `main` → `/ (root)` → Save. Open your GitHub Pages URL in Safari. Tap Share → Add to Home Screen.

For local testing, run `python -m http.server 8000` inside the folder then open `http://localhost:8000/`.

## Important limits
**Prototype only. Not suitable for storing real client health, NDIS, or personal information.** Local browser storage is not an appropriate secure record system. The app has no user authentication, permissions, encrypted server storage, audit logging, live staff sync, GPS verification, real messaging, clinical safety checks, NDIS billing, or compliance certifications. Clock-in times are device timestamps, not verified attendances. Use dummy data only. Before real-world use, build a secure backend and complete privacy, security, and relevant legal/compliance reviews.
