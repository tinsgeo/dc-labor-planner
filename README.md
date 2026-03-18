# dc-labor-planner
DC Labor Planning Tool

A full-stack, browser-based distribution center labor planning application built to model headcount requirements, capacity utilization, shift scheduling, and labor budget — in real time.

Live Demo: [tinsgeo.github.io/dc-labor-planner](https://tinsgeo.github.io/dc-labor-planner)

____________________________________________________________________________________________________________________________________________

The Problem

Distribution center managers make staffing and capacity decisions daily — often using disconnected spreadsheets, manual calculations, and gut instinct. Errors in these decisions directly drive labor cost overruns, understaffing during peak volume, and missed throughput targets.

This tool consolidates those decisions into a single, dynamic planning interface that recalculates in real time as inputs change.

____________________________________________________________________________________________________________________________________________

Features

Shift Planning
- Configure number of shifts, shift length, and break time
- Define process paths (Receiving, Picking, Packing, Shipping, etc.) with individual productivity rates
- Calculates required headcount per path and per shift automatically

Weekly Volume Forecast
- Input daily volume targets and planned headcount for each day of the week
- Instantly flags understaffed and overstaffed days with recommended adjustments
- Displays required vs. planned headcount delta across the full week

Capacity Modeling
- Define DC floor parameters: square footage, workstation count, max associates
- Model standard vs. peak volume scenarios and see utilization rates side by side
- Supports multi-brand and multi-channel volume splits

Budget & Cost Tracking
- Calculate weekly and annual labor cost with overtime multipliers and benefits load
- Projects annual spend against budget with variance analysis
- Computes cost-per-unit at current volume levels

Live Dashboard
- KPI tiles with color-coded status indicators (on plan / understaffed / overstaffed)
- Automated alerts for staffing gaps, capacity overloads, and budget overruns
- Visual bar charts for volume distribution and process path utilization

____________________________________________________________________________________________________________________________________________

Tech Stack

| Frontend | React, JavaScript, Tailwind CSS |
| Charts | Recharts |
| State Management | React Hooks (useState) |
| Deployment | GitHub Pages |

____________________________________________________________________________________________________________________________________________

Why I Built This

I spent 8 years managing distribution center operations at Amazon — across robotics fulfillment, last-mile delivery, and manufacturing. I built internal tools at Amazon (in VBA and SQL) that the project management team validated at 1.2M in annual savings. This project is a public, modern reimagining of that same problem: giving operations managers a real-time planning tool that replaces manual spreadsheet work.

It also gave me hands-on experience building a production-grade React application with dynamic state management, real-time computation, and a component-based UI — applying software engineering principles to a domain I know deeply.

____________________________________________________________________________________________________________________________________________

Getting Started

_bash_

git clone https://github.com/tinsgeo/dc-labor-planner.git

cd dc-labor-planner

npm install

npm start

Open [http://localhost:3000](http://localhost:3000) to run locally.

____________________________________________________________________________________________________________________________________________

Future Improvements

- CSV/Excel import for historical volume data
- Saved scenarios with local storage persistence
- Azure integration for cloud-hosted data and multi-user access
- Predictive headcount recommendations using time-series forecasting

____________________________________________________________________________________________________________________________________________

Author

Tinsley George
[linkedin.com/in/tinsleybgeorge](https://linkedin.com/in/tinsleybgeorge) [burrishenry.george@gmail.com](mailto:burrishenry.george@gmail.com)

