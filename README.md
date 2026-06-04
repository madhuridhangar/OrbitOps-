# OrbitOps — Angular 22 Admin Dashboard

![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-Material_3-CC6699?style=flat-square&logo=sass&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)

A production-ready enterprise admin dashboard built with the latest Angular 22 features — Standalone Components, Signals, `@if`/`@for` control flow, lazy loading, and SSR support.

> 🟢 **[Open Live Preview](./angular22-dashboard-preview.html)** — no build step required, works directly in the browser.

---

## 🚀 Tech Stack

- **Angular 22** — Standalone Components, Signals, Control Flow syntax
- **Angular Material** — MD3-inspired UI with async animations
- **TypeScript** — strict mode throughout
- **SCSS** — CSS custom property token system
- **Angular CDK** — breakpoint-driven responsive layout

## ✨ What's Inside

- Fixed navbar, collapsible dark sidebar (260px ↔ 80px), mobile overlay drawer
- **Dashboard** — KPI cards, revenue chart, activity bars, orders table with search & pagination, calendar, timeline
- **Analytics** — 6 KPI comparison cards, line/donut/sparkline charts, conversion funnel, sortable top pages table
- 7 additional lazy-loaded route stubs (Users, Products, Orders, Reports, Settings, Profile, Help)
- Fully responsive — Desktop · Tablet · Mobile
- WCAG AA accessible — skip link, ARIA labels, keyboard nav, reduced-motion support

## 📁 Structure

```text
src/app/
├─ core/layout/      # Shell, Navbar, Sidebar, Footer
├─ core/services/    # UiShellService (Signals + CDK), DashboardStore, AnalyticsStore
├─ shared/components # StatCard, LineChart, BarChart, Donut, Sparkline, KpiCard, MetricTable
└─ features/         # dashboard/, analytics/, placeholder/
```

## 🏃 Quick Start

```bash
npm install
ng serve
```

## 📸 Preview

| Dashboard | Analytics |
|-----------|-----------|
| KPI cards · Revenue chart · Orders table | KPI comparison · Funnel · Sortable table |

---

Made with ❤️ by [Madhuri Dhangar](https://github.com/madhuridhangar
