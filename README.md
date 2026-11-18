# ClientFlow — Functional CRM Dashboard (Demo)

A responsive, **client-side prototype** of a sales/lead management dashboard. It demonstrates a working CRUD application, pipeline analytics, follow-up scheduling and CSV export. All preloaded contacts are fictional.

## Working features
- Add, edit and delete leads
- Update pipeline stage inline (New → Contacted → Proposal → Won / Lost)
- Search names, companies and requested services
- Filter by stage and track follow-up dates
- KPI cards, stage chart and overdue follow-up queue calculated from real app state
- CSV export with spreadsheet formula-injection mitigation
- Local browser persistence with `localStorage` and demo reset
- Responsive desktop/mobile interface

## Run
Open `index.html` in Chrome, Edge or Firefox. No libraries or build tools required.

## Publish
Create public GitHub repository `portfolio-crm-dashboard`, upload `index.html` and `README.md`, then turn on **Settings → Pages → Deploy from a branch → main / (root)**.

The deployed URL follows `https://YOUR_USERNAME.github.io/portfolio-crm-dashboard/`.

## Limitations
This is a **front-end portfolio concept**, not a secure production CRM. Leads are local to one browser. No authentication, multi-user backend, team permissions, emails, external integrations or production database are included. Do not use it for real customer data without an audited backend and privacy safeguards.
