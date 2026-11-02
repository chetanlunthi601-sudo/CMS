# Manas College Pithoragarh — Computer Lab Management System

A static, GitHub Pages-ready prototype for tracking computers, repairs, CCTV cameras, and student lab usage across:
- Multipurpose Room
- Computer Lab

## Run locally
Open `index.html` in a modern browser. The logo is loaded from `assets/manas-college-logo.png`.

## Demo login
- Username: `admin`
- Password: `College@123`

Change the demo credentials in Settings before testing with others. This is a front-end prototype only; records are stored in the current browser's localStorage.

## Publish on GitHub Pages
1. Create a new repository on GitHub.
2. Upload all files in this ZIP (keep the `assets` folder and `index.html` together) to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Wait for the deployment URL to appear in the Pages section.

## Important security and data note
This static prototype is not suitable for confidential student data or real staff-only access on a public website. The login is checked in browser JavaScript and can be bypassed by a technically skilled visitor; localStorage data is not shared across devices and can be cleared. Before real college deployment, replace this with server-side authentication, role-based staff accounts, a shared database, audit logs, and a proper backup policy. Do not enter sensitive personal information in this demo.
