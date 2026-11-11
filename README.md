# ITSM Incident Dashboard: SLA Tracker

A ServiceNow-style incident management dashboard built with plain HTML, CSS and JavaScript. It shows how IT service desks prioritise incidents and track resolution SLAs.

**Live demo:** https://melwin139.github.io/itsm-incident-dashboard/

## Features

- **Impact × Urgency priority matrix**, using the same lookup as ServiceNow's default priority data lookup (P1–P5)
- **Live SLA timers** for each incident: time left, an "at risk" warning above 75% used, and breach detection
- **KPI cards**: open incidents, P1 critical, SLA breached, at risk, % of resolved incidents within SLA
- **Create incidents** in a form that calculates priority and SLA as you choose impact and urgency
- **Workflow buttons**: New → In Progress → Resolved
- Search, filter by state, priority or assignment group, sortable columns
- **Export to CSV**, light/dark theme, data saved in the browser (localStorage)

## Why I built this

I work with ServiceNow ITSM (Incident, Problem, Change, SLAs) and hold the CSA and CIS-ITSM certifications. This project recreates the core incident and SLA logic in vanilla JavaScript, to show both my ITSM process knowledge and my front-end skills.

| Priority | Name | Resolution SLA |
|---|---|---|
| P1 | Critical | 4 hours |
| P2 | High | 8 hours |
| P3 | Moderate | 24 hours |
| P4 | Low | 72 hours |
| P5 | Planning | 120 hours |

## Tech

HTML5, CSS3 (Grid, custom properties, dark mode), vanilla JavaScript (ES2020). No frameworks, no build step.

## Run locally

Open `index.html` in any browser. Click **Reset demo data** to reload the sample incidents.

## Author

**Melwin Naigam**, ServiceNow & Web Developer · [Portfolio](https://melwin139.github.io) · [LinkedIn](https://www.linkedin.com/in/melwinaigam)
