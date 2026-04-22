# MARUTEE Recruitment Portal

A lightweight, single-file recruitment management portal built for the Thermal & Automotive Pillar. Role-based workflow for Managers and Recruiters — no backend, no installation, runs entirely in the browser.

**Live demo:** https://YOUR-USERNAME.github.io/marutee-recruitment-portal/

---

## Features

**Manager Portal**
- Full dashboard with 12 KPIs, 5 charts (status, priority, decisions, department, location)
- Recruitment pipeline funnel visualisation
- Create new hiring requirements with full JD, skills, CTC, priority, deadline
- Assign requirements to specific recruiters with briefing notes
- Review and approve/reject candidates with feedback comments
- Recruiter performance leaderboard
- Department-wise reporting
- Export full snapshot as JSON

**Recruiter Portal**
- Personal dashboard with assignment KPIs and urgent deadline tracker
- Accept assignments from the available queue
- Submit candidate details against active assignments
- Full candidate form (experience, CTC, notice, skills match, screening score)
- Track candidate status and read manager feedback

## How to Use

1. Open the live URL (or `index.html` locally)
2. Enter your name and email on the login screen
3. Choose **Manager** or **Recruiter**
4. Navigate through the tabs at the top of the dashboard

## Sample Accounts

This is a demo. Any name and email will work. Try logging in as Manager first to create and assign requirements, then log out and log in as Recruiter (same browser) to accept assignments and submit candidates.

## Technology

- Pure HTML, CSS, JavaScript — single file, no build step
- Chart.js (via CDN) for interactive charts
- `localStorage` for data persistence (browser-local)

## Limitations

This is a prototype / demonstration. Data is stored in the browser's `localStorage`, so:
- Every visitor has their own isolated demo data
- Data does not sync between devices or users
- For a real multi-user system, a backend (Firebase, Supabase, Node/Express) is required

## Local Development

No build step required. Just open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari).

## License

MIT — see LICENSE file.

## Author

Built by the MARUTEE Thermal & Automotive Pillar team.
