# Salesforce Recruitment CRM (Admin Project)

A practical, business-focused Salesforce project that demonstrates how to manage Job Openings, Candidates, and Applications with automation and reporting.

## Why this project?
Recruiting teams often track candidates in spreadsheets. This project shows a clean, scalable way to run recruiting in Salesforce: custom objects, auto-assignment, and dashboards.

## Features (Admin-focused)
- Custom Objects: **Job Opening**, **Candidate**, **Application** (junction object)
- Automation: Record-Triggered **Flow** to assign Applications to the right recruiter or a team queue
- Reporting: Reports + **Recruitment KPIs Dashboard**
- Security: Owner/Queue-based visibility; basic permission set for Recruiters

## Folder Structure
```
/docs   -> screenshots (objects, flow, dashboards)
/data   -> sample CSVs for quick import
/flows  -> exported flows (optional)
README.md -> this file
```

## How to use this repo
1. Create a Salesforce Dev Org (or Trailhead Playground).
2. Build the objects/fields/flow using the steps in your guide.
3. Import sample data from `/data` (order: Job Openings → Candidates → Applications).
4. Take screenshots and drop them into `/docs`.
5. (Optional) Export your Flow and place it in `/flows`.

## Project Summary (copy for LinkedIn/Portfolio)
**Problem:** Hiring activity lived in spreadsheets, creating delays and no visibility.  
**Solution:** Built a Recruitment CRM in Salesforce with custom objects (Job Opening, Candidate, Application), an auto-assignment Flow, and KPI dashboards.  
**Outcome:** Reduced manual work, clear ownership, and real-time insights for managers.

## Screenshots
Place your images in `/docs` and reference them here, e.g.:
- `docs/app-launcher.png`
- `docs/flow-auto-assign.png`
- `docs/dashboard-recruitment-kpis.png`

## Credits
Created by **Sukhvinder Singh Sandhu** — Salesforce Certified Administrator (Berlin).
