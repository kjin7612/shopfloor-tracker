# Shop Floor Tracker

A lightweight production tracking app for small manufacturing plants: tablet-friendly shift reports, live OEE dashboards and defect tracking.

**Live demo:** https://shopfloor-tracker.vercel.app

## What it does

- **Overview dashboard:** OEE gauge with Availability × Performance × Quality breakdown, attainment, first-pass yield, downtime, per-line status and trends
- **Shift report:** large touch targets for operators on a tablet, with KPIs calculated as they type
- **Quality:** defect logging, Pareto analysis and open/closed tracking for corrective actions

The demo runs entirely in the browser with generated sample data (4 lines, 2 shifts, last 4 weeks). Nothing is stored or sent anywhere.

## KPI definitions

| KPI | Formula |
|---|---|
| Attainment | Actual qty ÷ Planned qty |
| First-pass yield | Good qty ÷ Actual qty |
| Availability | (Planned run time − Downtime) ÷ Planned run time |
| OEE (simplified) | Availability × min(Attainment, 100%) × Yield |

## Custom versions

I build versions of this around your own lines, products and reports, including database storage, user logins, ERP integration and machine data collection.

Contact me on [Upwork](https://www.upwork.com/freelancers/~01d54fad8b27892498).
