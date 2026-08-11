# Vidyut — Power Monitoring & Analytics Platform

A web-based dashboard for monitoring and analyzing electrical parameters — voltage, current, and power — across the IIT Jammu campus grid system, built to surface fluctuations and abnormal patterns that are otherwise hard to spot in raw measurements.

**Live Demo:** [vidyut-power-monitoring.onrender.com](https://vidyut-power-monitoring.onrender.com/)

> Note: The deployed link is a demo/prototype interface showcasing the monitoring and analytics system, not a live production feed of the actual IIT Jammu grid.

---

## Overview

Vidyut brings together voltage, current, and power measurements from across the campus grid into a single, centralized dashboard. Instead of inspecting raw electrical readings independently, the platform converts them into graphs and visual summaries, making it easier to track trends and catch anomalies early.

## Problem It Solves

- **Voltage Fluctuation Monitoring** — visualizes changes in voltage across the grid over time
- **Power Monitoring** — tracks voltage, current, and power through one interface instead of scattered raw readings
- **Data Visualization** — turns raw electrical measurements into readable graphs and dashboards
- **Anomaly Identification** — threshold-based alerts flag unusual or potentially problematic conditions
- **Centralized Monitoring** — consolidates multiple measurement streams into a single platform

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | Node.js / JavaScript, modular architecture (controllers, routes, services, models, middleware) |
| Frontend | HTML, CSS, JavaScript |
| Data Visualization | JavaScript-based charting components |
| Deployment | Render |

## Architecture

```
Frontend/           → Dashboards, graphs, maps, scheduling, device interaction, data exploration
Backend_main/        → Controllers, routes, services, models, middleware, utilities, DB insertion
```

- **Frontend Layer** — user-facing dashboards, graphs, and interactive controls
- **Backend Layer** — server-side logic organized into controllers, routes, services, and models
- **Data Layer** — handles storage and insertion of electrical monitoring data
- **Visualization Layer** — processes and renders voltage/current/power data as interactive graphs
- **Monitoring Layer** — core logic for observing and flagging grid behavior
- **Automation Layer** — Auto-Timer module for scheduling device-related operations

## Key Features

- Real-time-style voltage, current, and power monitoring dashboards
- Interactive, graph-based visualization of electrical trends
- Threshold-based smart alerts for abnormal readings
- Data exploration interface for digging into collected measurements
- Device control and Auto-Timer for automation of device operations

## Getting Started

```bash
# Clone the repository
git clone https://github.com/inviforce/Project-Monitoring.git
cd Project-Monitoring

# Install backend dependencies
cd Backend_main
npm install

# Install frontend dependencies
cd ../Frontend
npm install

# Run locally (see individual package.json scripts for exact commands)
npm start
```

> Update the commands above once final `package.json` scripts are confirmed.

## Screenshots

_Add 2–3 screenshots of the dashboard, graph views, and alerts here to give recruiters a quick visual before they click into the live demo._

## Current Status

Working prototype built as a college project focused on monitoring electrical parameters and voltage fluctuations across the IIT Jammu grid. Deployed publicly on Render as a demonstration of the platform's monitoring and analytics capabilities.

## Future Improvements

- Real-time integration with live electrical sensors and meters
- Automated detection of voltage spikes, drops, and sags
- Predictive analytics using historical measurement data
- Historical trend comparison across time periods
- Configurable, per-parameter alert thresholds
- Energy consumption forecasting
- Scalable data infrastructure for more sensors at higher frequency
- Mobile-optimized dashboard experience

## License

_Add a license if you'd like this repo to specify usage terms (MIT is a common default for student/portfolio projects)._