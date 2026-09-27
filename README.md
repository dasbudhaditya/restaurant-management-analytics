# Restaurant Management & Analytics System — Portfolio Demo

**Live demo:** https://dasbudhaditya.github.io/restaurant-management-analytics/recruiter-demo.html

A standalone, interactive demonstration of a restaurant operations and management analytics platform. The demo opens with a populated fictional trading day so reviewers can immediately explore the dashboard and then switch between daily, weekly, monthly and custom reporting views.

## What the demo covers
- Management dashboard with sales, covers, average spend, labour cost, labour %, overtime and budget KPIs
- Food and beverage revenue analysis by menu category
- Product-level sales entry, search, menu-price calculation and reconciliation
- Daily Z-report entry and historical lookup
- Staff clock-in / clock-out entry with overtime calculation
- Staff performance, overtime spend and current-month payroll accrual
- Weekly ROTA management with fictional sample shifts
- Menu and staff master management
- Autosave/recovery patterns and editable browser sandbox

## Portfolio safety
All staff names, operational figures and sample transactions are fictional. This GitHub Pages build is completely separate from the restaurant production environment and does **not** connect to the production Google Sheet or Apps Script backend.

Changes made by a visitor are stored only in that visitor's browser (`localStorage`). **Reset Demo** restores the original fictional dataset.

## Technology
HTML5, CSS3, JavaScript and Google Charts. The production application uses Google Apps Script and Google Sheets as its application/backend layer.

## Demo notes
The portfolio build intentionally preloads a complete fictional sample date and sample week so dashboard charts, labour analytics, payroll and ROTA can be reviewed without setup. It is designed for demonstration rather than production data entry.

## Run locally
Open `index.html` in a browser. GitHub Pages publishes the repository root from the `main` branch.
