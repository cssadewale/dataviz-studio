<div align="center">

# 📊 Tableau Stimulator
### Free Tableau-Style Browser-Based Analytics Simulator

*A Tableau-inspired analytics platform that runs entirely in a single HTML file —*
*no installation, no server, no subscription, no internet required.*

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Open_App-00d4aa?style=for-the-badge)](https://cssadewale.github.io/tableau-stimulator/)
[![License: MIT](https://img.shields.io/badge/License-MIT-4f8ef7?style=for-the-badge)](./LICENSE)
[![No Backend](https://img.shields.io/badge/Backend-None_Required-2dbd8c?style=for-the-badge)]()
[![No AI API](https://img.shields.io/badge/AI_API-Not_Used-f7a84f?style=for-the-badge)]()
[![Built in Nigeria](https://img.shields.io/badge/Built_in-Nigeria_🇳🇬-008751?style=for-the-badge)]()
[![Single File](https://img.shields.io/badge/App_Size-240KB_Single_File-8c6fd4?style=for-the-badge)]()

**[🚀 Open Live App](https://cssadewale.github.io/tableau-stimulator/) · [📖 Feature Guide](#-complete-feature-guide) · [🐛 Report Bug](../../issues/new?template=bug_report.md) · [💡 Suggest Feature](../../issues/new?template=feature_request.md)**

</div>


---


## Important Naming and Intellectual Property Note

This project is named **Tableau Stimulator** because it is designed as a learning and productivity simulator for Tableau-like analytics workflows. It does **not** use Tableau logos, Tableau source code, proprietary assets, paid Tableau services, or trademarked visual assets. The system recreates familiar BI operations — worksheets, shelves, marks, dashboards, stories/reports, Show Me-style chart suggestions, filters and analytics overlays — using original open-source browser code and free tools.

## 🆕 Enhanced Tableau-Style Features Added in This Build

Tableau Stimulator has been enhanced without removing any previous feature. The new build strengthens the Tableau-like workflow using only free browser technologies:

| Enhancement | What it Does | Tableau-style Purpose |
|---|---|---|
| **Show Me / Template Picker** | The 📋 button suggests visual forms such as Ranking, Trend, Funnel, Waterfall, Gauge, Distribution and Correlation. | Mirrors Tableau's visual recommendation workflow without copying proprietary assets. |
| **Direct Waterfall / Funnel / Gauge Menu Items** | These executive chart types are now available directly from the chart dropdown. | Supports KPI, pipeline, bridge and executive dashboard scenarios. |
| **Forecast Overlay (🔮)** | Adds a deterministic 5-step linear projection based on current aggregated data. | Similar analytical intent to trend/forecast overlays; no AI API and no paid service. |
| **Moving Average Overlay (Ⓜ MA)** | Adds a 3-point rolling average line to smooth noisy trends. | Helps users interpret time-series movement. |
| **Dashboard Presentation Mode (⛶ Present)** | Opens the dashboard full-screen for classroom, client or boardroom display. | Resembles BI presentation workflows. |
| **Reset Dashboard Filters (↺)** | Clears all dashboard drill-down and global filter states in one click. | Restores dashboard context after exploration. |
| **Ask Data (🔎)** | Lets users type simple questions like “top revenue by state” using a local rule parser. | Recreates the intent of natural-language BI queries without AI API cost. |
| **Sample Data Loader** | Loads a built-in sales dataset for instant practice and demos. | Lets new users explore Tableau-style workflows without preparing a CSV first. |
| **Data Dictionary / Metadata** | Profiles each field: type, role, missing count, distinct count and examples. | Recreates a professional data-source metadata workflow. |
| **Fixed Inline Editing** | Data Preview cells can be double-clicked, edited and re-rendered correctly. | Supports quick data correction directly inside the workbook. |
| **Stability Fixes** | Corrected chart menu coverage, workspace version name and dashboard tab switching. | Makes the system more production-ready. |

> Branding note: the app intentionally follows Tableau-like analytical patterns (shelves, marks, worksheets, dashboards, Show Me-style templates) but uses original open-source code, original styling, and no proprietary Tableau logos or assets.


## 👤 Creator / Owner Details Embedded in the Platform

**Adewale Samson Adeagbo** is embedded across the application interface and documentation as the creator and owner of Tableau Stimulator.

| Item | Details |
|---|---|
| Name | Adewale Samson Adeagbo |
| Location | Lagos, Nigeria |
| Identity | Data Scientist · STEM Educator · EdTech Builder · AI-Augmented Solutions Developer |
| Experience | 15+ years teaching Nursery, Primary and Secondary learners across Mathematics, Further Mathematics, Physics, Chemistry and Computer Science |
| Education | B.Sc.(Ed) Computer Science Education, Lagos State University, 2023 |
| Brand | Founder / Visioner of HMG Concepts — HMG Academy, HMG Technologies and HMG Media |
| Portfolio | https://cssadewale.pages.dev |
| HMG Concepts | https://hmgconcepts.pages.dev |
| GitHub | https://github.com/cssadewale |
| LinkedIn | https://linkedin.com/in/adewalesamsonadeagbo |
| YouTube | https://youtube.com/@hmgconcepts |
| WhatsApp | +234 810 086 6322 |
| Email | hmgconcepts@gmail.com · hismarvellousgrace@gmail.com |

Inside the app, users can click **“by Adewale Samson Adeagbo”** in the topbar to open the full About modal.

---

## 📌 Table of Contents

1. [The Origin Story](#-the-origin-story)
2. [Overview](#-overview)
3. [Why Tableau Stimulator?](#-why-tableau-stimulator)
4. [Feature Overview](#-feature-overview)
5. [Chart Types](#-chart-types-15)
6. [Complete Feature Guide](#-complete-feature-guide)
7. [Keyboard Shortcuts](#-keyboard-shortcuts)
8. [Technology Stack](#-technology-stack)
9. [Getting Started](#-getting-started)
10. [Deployment](#-deployment)
11. [File Structure](#-file-structure)
12. [Version History](#-version-history)
13. [Use Cases](#-use-cases)
14. [Contributing](#-contributing)
15. [Author](#-author)
16. [License](#-license)

---

## 🌱 The Origin Story

> *"The barrier to building real software is not hardware — it is clarity of thought."*

Tableau Stimulator was conceived and built on an **Android tablet (ITEL Vista Tab 30s)** using the Acode code editor — no laptop, no IDE, no local server. Every feature was designed, written, and tested from a mobile browser environment, proving that professional-grade analytical tools can be built with nothing but a clear mind and free resources.

This project is part of a broader body of work by **Adewale Samson Adeagbo** — a Data Scientist, EdTech Builder, and AI-Augmented Solutions Developer based in Lagos, Nigeria, who has built **12 deployed data science and analytics applications** and spent **15+ years** in education, bridging the gap between technical knowledge and real-world application.

Tableau Stimulator is the flagship demonstration of a core principle: **you do not need expensive tools to do professional analytical work.**

---

## 🌟 Overview

Tableau Stimulator is a feature-rich, Tableau-inspired data visualisation and analytics platform packed into a **single self-contained HTML file**. It requires:

- ❌ No installation
- ❌ No server or backend
- ❌ No database
- ❌ No paid subscription
- ❌ No AI API
- ❌ No internet connection after first load
- ✅ Just a modern browser

Upload a CSV file, drag fields onto shelves, and build publication-quality charts, pivot tables, statistical reports, and dashboards — entirely in your browser, entirely offline.

**Live URL:** [https://cssadewale.github.io/tableau-stimulator/](https://cssadewale.github.io/tableau-stimulator/)

---

## ❓ Why Tableau Stimulator?

### The Problem

Data professionals and educators in Nigeria and across Africa face a critical access gap: the best analytics tools (Tableau, Power BI) cost $10–$75/month, require installation on a full laptop or desktop, and often need a stable internet connection. For students, independent tutors, and practitioners working on mobile devices or low-spec hardware, these tools are simply out of reach.

### The Solution

A single HTML file that delivers **80% of Tableau's core functionality** at **₦0 / $0**, runs on any device with a browser, and works completely offline.

### Direct Comparison

| Feature | Tableau Public | Power BI | Excel | **Tableau Stimulator** |
|---|---|---|---|---|
| Monthly Cost | Free (limited) | $10 | $10+ | **Free** |
| Installation | Required | Required | Required | **None** |
| Works on Android tablet | No | No | Limited | **Yes** |
| Works fully offline | No | No | Yes | **Yes** |
| Data stays on your device | No | No | Yes | **Yes** |
| Single file | No | No | No | **Yes** |
| Open Source | No | No | No | **Yes (MIT)** |
| Pivot Tables | Yes | Yes | Yes | **Yes** |
| Statistical Analysis | Partial | Partial | Partial | **Yes** |
| Data Cleaning Tools | No | Partial | No | **Yes** |
| Report Builder | Yes | Yes | Yes | **Yes** |
| Smart Narrative | Yes (AI) | Yes (AI) | No | **Yes (algorithmic)** |

---

## ✨ Feature Overview

Tableau Stimulator ships with **75+ features** across 10 functional modules.

| Module | Tab | Description |
|---|---|---|
| 📊 **Worksheet** | Worksheet | Main chart-building workspace with Tableau-style drag-and-drop shelves |
| ⊞ **Pivot Table** | Pivot | Cross-tabulation with heatmap colouring and CSV export |
| 📐 **Statistics** | Statistics | Descriptive stats, outlier detection (IQR), Pearson correlation matrix |
| 🧹 **Data Cleaner** | Data Cleaner | Missing values, duplicates, whitespace, casing, binning, search & replace |
| ⚡ **Compare Mode** | Compare | Side-by-side dual chart comparison with export |
| 📄 **Report Builder** | Report | Assemble and export professional HTML/PDF analytics reports |
| 🗂 **Dashboard** | Dashboard | Multi-panel dashboard with KPI cards and drill-down filtering |
| 📚 **Help System** | (panel) | Built-in searchable documentation — works offline |
| 🗒 **Workbook** | (sheet bar) | Unlimited named sheets with fully independent configurations |
| 🆕 **Show Me + Forecasting** | Topbar / Worksheet | Tableau-style visual suggestions, direct Waterfall/Funnel/Gauge, moving average and rule-based forecast overlays |

---

## 📊 Chart Types (15+)

| # | Chart | Icon | Best For |
|---|---|---|---|
| 1 | Bar Chart | ▬ | Comparing discrete categories |
| 2 | Horizontal Bar | ⊟ | Long category names, rankings |
| 3 | Stacked Bar | ⊞ | Sub-category contribution to a total |
| 4 | Line Chart | 📈 | Trends over time or ordered sequences |
| 5 | Area Chart | 🏔 | Volume trends with fill beneath the line |
| 6 | Stacked Area | ◼ | Cumulative flows over time |
| 7 | Scatter Plot | ⬡ | Correlation between two numeric fields |
| 8 | Pie Chart | 🥧 | Part-of-whole (best with ≤6 categories) |
| 9 | Donut Chart | ⊙ | Part-of-whole with better arc readability |
| 10 | Radar/Spider | 🕸 | Multi-attribute profiling across categories |
| 11 | Heatmap | 🟫 | Intensity at two-dimensional intersections |
| 12 | Box Plot | 📦 | Full distribution: min, Q1, median, Q3, max + outliers |
| 13 | Waterfall | 💧 | Incremental positive/negative changes to a total |
| 14 | Funnel | 🔻 | Sequential conversion or reduction through stages |
| 15 | Gauge | ⏱ | Single aggregated metric vs a target range |

---

## 📖 Complete Feature Guide

### 🏗 Shelf System (Tableau-Style)

The COLS and ROWS shelves replicate Tableau's drag-and-drop workflow:

| Shelf | Purpose | Drag Here |
|---|---|---|
| **COLS** | X-axis / category axis | Categorical (Abc) or Date (D) fields |
| **ROWS** | Y-axis / measure axis | Numeric (#) fields — multiple creates multi-series |
| **Color By** | Split chart by colour | Categorical fields |
| **Size By** | Scale element size | Numeric fields |
| **Label** | Display values on chart | Any field |
| **Filter** | Restrict data | Any field |

**Field Type Icons:**

| Icon | Colour | Meaning |
|---|---|---|
| `#` | Blue | Numeric / Measure |
| `Abc` | Teal | Categorical / Dimension |
| `D` | Amber | Date field |
| `ƒ` | Blue | Calculated field |

---

### ƒ Calculated Fields & Formula Bar

The formula bar below the topbar enables instant calculated field creation:

```
Field Name:  Profit Margin
Formula:     [Revenue] - [Cost]
→ Press Enter or click Apply
```

**Syntax:** Wrap any existing field name in `[square brackets]`. Supports `+`, `-`, `*`, `/`, and parentheses.

| Formula Example | Creates |
|---|---|
| `[Revenue] - [Cost]` | Profit |
| `[Sales] / [Revenue] * 100` | Conversion Rate % |
| `[Units] * [Price]` | Total Value |
| `([Score] / [MaxScore]) * 100` | Normalised Score % |
| `[Q4] - [Q3]` | Quarter-on-Quarter Growth |

---

### 📐 Statistics Tab

Three analytical tools for quantitative analysis:

**1. Descriptive Statistics** — click ▶ Run Statistics

| Statistic | Description |
|---|---|
| Count | Number of non-null values |
| Mean | Arithmetic average |
| Median | Middle value (50th percentile) |
| Std Dev | Standard deviation |
| Variance | Square of standard deviation |
| Min / Max | Smallest and largest values |
| Q1 (25th %ile) | Lower quartile |
| Q3 (75th %ile) | Upper quartile |
| Skewness | Distribution asymmetry (Pearson second coefficient) |

**2. Outlier Detection (IQR Method)** — click ⚠ Detect Outliers

Flags every value below `Q1 − 1.5×IQR` or above `Q3 + 1.5×IQR` with: field name, row number, outlier value, and direction (HIGH/LOW).

**3. Correlation Matrix (Pearson)** — click ⊞ Correlation

Computes the linear relationship coefficient between every pair of numeric fields:
- **+1** = perfect positive correlation
- **−1** = perfect negative correlation
- **0** = no linear relationship
- Colour-coded: 🟢 strong positive · 🔴 strong negative · 🟡 moderate

---

### 🧹 Data Cleaner Tab

| Tool | What It Does |
|---|---|
| **🔍 Scan Data** | Flags every field with missing value counts, type inconsistencies, and duplicate row count |
| **🔧 Fill Missing** | Numeric → replaced with field mean. Text → replaced with mode (most frequent value) |
| **🗑 Remove Dupes** | Deletes exact-match rows. First occurrence is kept. |
| **✂ Trim Spaces** | Strips leading and trailing whitespace from all text values |
| **Aa Case** | Converts all text to Title Case to prevent "lagos" and "Lagos" being separate categories |
| **Search & Replace** | Find any value in a field and replace all occurrences. Case-insensitive. Instant. |
| **Data Binning** | Groups a numeric field into equal-width ranges as a new dimension field |

---

### 🧾 Data Dictionary / Metadata

Click **Dictionary** in the Tableau-style menu strip to inspect every field in the active dataset. The dictionary shows field name, inferred type, analytical role, missing values, distinct values and example values. It can be exported as CSV for data governance, teaching notes or project documentation.

---

### 📦 Sample Data Loader

Click **Sample Data** in the menu strip to load a built-in sales dataset. This is useful for first-time users, classroom demonstrations, GitHub Pages testing and portfolio walkthroughs. No internet or backend is needed after the app loads.

---

### 💡 Smart Narrative Engine

Click **💡** in the topbar after building a chart. Generates a structured plain-English analysis of your chart data with **no AI API** — 100% mathematical and rule-based. Produces a paragraph covering:

- Total aggregated value
- Average per category
- Highest-performing category and its percentage share of the total
- Lowest-performing category and the spread between extremes
- Coefficient of variation (variability measure)
- Overall trend direction (via linear regression slope)
- Top 3 performing categories

Works offline. Costs nothing. Consistent and accurate every time.

---

### ↩↪ Undo / Redo

Every shelf action (drag a field on or remove one) creates a snapshot. Up to **50 actions** stored per session.

- **↩** button = undo · **↪** button = redo
- Keyboard: **Alt+Z** (undo) · **Alt+Y** (redo)
- Buttons are greyed out when nothing is available

---

### ⚡ Compare Mode

Side-by-side dual chart view with independent configuration per chart:
- Chart A and Chart B have separate field, chart type, and aggregation settings
- Both render from the same filtered dataset
- Custom inline-editable titles per panel
- **Export Both** — downloads both charts as PNG simultaneously

---

### 📄 Report Builder

Assembles a professional analytics report from selectable components:

| Component | Contents |
|---|---|
| 📊 Chart | Current worksheet chart embedded as an image |
| 💡 Insights | Algorithmically generated key findings paragraph |
| 📐 Stats | Full descriptive statistics table |
| ⊞ Pivot | Current pivot table |

**Workflow:**
1. Toggle desired components on (they highlight blue when active)
2. Enter report title and author name
3. Click **▶ Build Report** — live preview appears
4. Click any section title to rename it inline
5. **💾 Export HTML** — standalone HTML file for any browser
6. **🖨 Print** — browser print dialog; choose "Save as PDF"

---

### 🎯 Goal / Target Line

Enter a numeric target in the right panel → click **Set Goal** → a bold amber dashed line labelled `Target: [value]` appears across the chart. Click **✕** to remove.

Useful for: sales quotas, budget thresholds, pass marks, KPI targets.

---

### 🔢 Top N Filter

Show only the top or bottom N categories by aggregated value. Example: N=10, Top → only the 10 best-performing categories appear. Works on bar, line, area, and colour-encoded charts.

---

### 🎨 Custom Series Colors

Each measure on the ROWS shelf gets a color picker swatch in the right panel. Click any swatch to assign an exact color, overriding the palette for that series only. Click **Reset to Palette** to restore.

---

### ✏ Inline Cell Editing

Open the Data Preview table (click **▤**). Double-click any cell to edit its value. Press **Enter** to save, **Escape** to cancel. Chart re-renders immediately with the corrected value.

---

### 🗂 Dashboard

| Feature | Description |
|---|---|
| Chart Panels | Independent charts — own field, chart type, aggregation |
| KPI Cards | Big-number metric with sparkline and delta badge |
| Drill-Down | Click any chart element to filter all other panels |
| Global Filter | One field=value filter applied to all panels at once |
| Layouts | 1, 2, or 3 column grid |
| Export | Each panel as individual high-resolution PNG |

---

### 💾 Save & Load Workspace

**Save (💾)** downloads the complete session as JSON including: dataset, all sheets, calculated fields, annotations, reference lines, dashboard panels, KPI cards, palette, and theme.

**Load (📂)** restores any saved session completely in one click.

---

### 🌗 Themes & Palettes

**Themes:** Dark mode (default) · Light/Print mode (white, for PDF and client decks)

**10 Colour Palettes:**

| Name | Best For |
|---|---|
| Teal (default) | Professional reports |
| Blue | Corporate/business |
| Warm | Alerts, marketing |
| Purple | Executive presentations |
| Green | Growth, health, sustainability |
| Mono | Print, accessibility, greyscale |
| Fire | High-energy marketing |
| Fresh | Health, environment |
| Candy | Creative, vibrant |
| Earth | Geographic, demographic |

---

## ⌨ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Alt + R` | Render chart |
| `Alt + C` | Clear all shelves |
| `Alt + Z` | Undo last action |
| `Alt + Y` | Redo last action |
| `Alt + S` | Save workspace |
| `Alt + E` | Export chart as PNG |
| `Alt + P` | Toggle data preview |
| `Alt + N` | Generate smart narrative |
| `Alt + H` | Toggle help panel |
| `Alt + A` | Auto Chart |
| `Alt + F` | Focus formula bar |
| `Alt + W` | Worksheet tab |
| `Alt + D` | Dashboard tab |
| `Alt + T` | Statistics tab |
| `Alt + 1–4` | Switch to sheet 1–4 |
| `Escape` | Close all overlays |

Click **⌨** in the topbar or press Escape anywhere to see the full shortcuts overlay.

---

## 🛠 Technology Stack

Every dependency is free and open-source. No paid APIs. No commercial licences.

| Component | Technology | Version | Purpose |
|---|---|---|---|
| Charting | Apache ECharts | 5.4.3 | All 15 chart types |
| CSV Parsing | PapaParse | 5.4.1 | CSV/TSV file parsing |
| UI | Vanilla HTML5 + CSS3 + ES6 JS | — | All interface and logic |
| Fonts | Google Fonts | — | Sora + DM Mono (degrades gracefully offline) |
| Hosting | GitHub Pages / Netlify | — | Free static hosting |
| Build Tools | **None** | — | No build step required |
| Backend | **None** | — | 100% client-side |
| Database | **None** | — | Browser memory only |
| AI/ML API | **None** | — | All intelligence is algorithmic |

**Monthly infrastructure cost: ₦0 / $0**

---

## 🚀 Getting Started

### Option A — Use the Live App (Instant)

Visit **[https://cssadewale.github.io/tableau-stimulator/](https://cssadewale.github.io/tableau-stimulator/)** in any browser. No login. No sign-up. No credit card.

### Option B — Download and Run Locally

1. Download `index.html` from this repository
2. Double-click to open in your browser (Windows/macOS/Linux)
3. On Android: transfer to your tablet → tap to open in Chrome

### Option C — Clone

```bash
git clone https://github.com/cssadewale/tableau-stimulator.git
cd tableau-stimulator
open index.html   # macOS/Linux
# start index.html  on Windows
# No npm install. No build step. No configuration.
```

### System Requirements

| Item | Requirement |
|---|---|
| Browser | Chrome 90+ · Firefox 88+ · Edge 90+ · Safari 14+ |
| Device | Desktop · Laptop · Android Tablet · iOS · Mobile |
| RAM | 1GB minimum (2GB recommended for 10,000+ row datasets) |
| Storage | 1MB for the application file |
| Internet | Not required after initial page load |
| Server | Never required |

---

## 🌍 Deployment

See [**DEPLOYMENT.md**](./DEPLOYMENT.md) for the complete guide covering 7 methods with step-by-step instructions.

### Quickstart — GitHub Pages

```
1. Fork this repository
2. Go to Settings → Pages
3. Source: Deploy from a branch → main → / (root)
4. Save → wait 2–3 minutes
5. Live at: https://[your-username].github.io/tableau-stimulator/
```

### Quickstart — Netlify (30 seconds)

```
1. Go to netlify.com → sign up free
2. Drag index.html onto the deploy zone
3. Your site is live immediately
4. Customise URL: Site configuration → Change site name
```

---

## 📁 File Structure

```
tableau-stimulator/
│
├── index.html                        ← The entire application (240KB, self-contained)
│
├── README.md                         ← This documentation
├── LICENSE                           ← MIT License
├── CHANGELOG.md                      ← Full version history
├── CONTRIBUTING.md                   ← Architecture guide + contribution standards
├── DEPLOYMENT.md                     ← 7 deployment methods, step by step
├── SAMPLE_DATA.md                    ← 5 ready-to-use CSV datasets for testing
├── SECURITY.md                       ← Data privacy policy + vulnerability reporting
├── CODE_OF_CONDUCT.md                ← Community standards
├── .gitignore                        ← Excludes OS/editor temp files
│
└── .github/
    ├── workflows/
    │   └── deploy.yml                ← Auto-deploys to GitHub Pages on push to main
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.md             ← Structured bug report form
    │   └── feature_request.md        ← Structured feature request form
    └── PULL_REQUEST_TEMPLATE.md      ← PR checklist and description template
```

> **Note:** Everything that matters is in `index.html`. All other files are repository documentation and GitHub configuration only.

---

## 📋 Version History

| Version | Headline Features |
|---|---|
| **Tableau Stimulator** (current) | Smart Narrative, Undo/Redo, Compare Mode, Report Builder, Goal Line, Top N, Binning, Search & Replace, Custom Colors, Inline Editing, Keyboard Shortcuts |
| **v6** | Statistics Tab, Data Cleaner, What-If Simulator, Formula Bar, Auto Chart, Templates, Waterfall/Funnel/Gauge, STDEV, Outlier Highlights, 10 Palettes, Built-in Help |
| **v5** | Multi-Sheet Workbook, Pivot Table, KPI Cards, Dashboard Drill-Down, Conditional Formatting |
| **v4** | DS1+DS2 Multi-Dataset, Join, Annotations, Light Theme, Global Filter, CSV Export, Zoom/Pan, Field Profiling |
| **v3** | Chart Title/Axis Labels, Range Sliders, Trend Lines, Reference Lines, Sort, Box Plot, Workspace Save/Load |
| **v2** | Multi-Series, Dual Axis, Color Encoding, Labels, Heatmap, Radar, Dashboard, Calculated Fields |
| **v1** | CSV upload, 7 chart types, shelves, aggregation, filters, preview |

Full history: [**CHANGELOG.md**](./CHANGELOG.md)

---

## 💼 Use Cases

### 🎓 Education & EdTech (HMG Academy)

HMG Academy is a full-service virtual tutoring brand covering WAEC, NECO, UTME, IGCSE, and IELTS for secondary school students across Nigeria. Tableau Stimulator supports its educational mission directly:

- **Student performance tracking** — upload result spreadsheets and visualise score distributions by subject, class, or term
- **At-risk student identification** — scatter plots of attendance vs performance reveal students needing intervention
- **Comparative class analysis** — pivot tables showing average scores by subject across JSS1–SSS3
- **Parent reporting** — export professional HTML reports with charts and statistics

### 📊 Data Science Portfolio

The author has 12 deployed ML projects. Tableau Stimulator enables rapid EDA of their CSV outputs:

| Project | Tableau Stimulator Use |
|---|---|
| Employee Burnout Predictor | Burn rate distribution by department (Box Plot) |
| Bank Customer Churn | Churn rate waterfall by customer segment |
| SwiftChain Delivery | Delay funnel by shipment stage |
| Income Level Prediction | Income distribution by education level (Box Plot) |
| Student At-Risk Predictor | At-risk rates by class and gender (Heatmap) |
| Fake News Detector | Accuracy metrics visualised as Gauge |

### 🏢 Business Analytics

- Sales analysis — regional revenue bar charts, monthly trend lines, top N products
- HR analytics — attrition funnel, salary distribution, burnout heatmaps
- Financial reporting — waterfall P&L, revenue vs target gauge
- Inventory — stock level gauges, reorder point reference lines

### 🔬 Research & Academia

- Survey data from Google Forms CSV exports
- Correlation analysis before building ML models
- Descriptive statistics before hypothesis testing
- Printable HTML/PDF reports for academic submission

---

## 🤝 Contributing

Contributions are welcome. Please read [**CONTRIBUTING.md**](./CONTRIBUTING.md) for the full guide.

### Quick Rules

1. All code goes in `index.html` — no build step, no npm packages
2. Every interactive element needs a `title` tooltip attribute
3. Every new feature needs a help entry in `HELP_CONTENT`
4. No AI API calls — all logic must be algorithmic
5. Test on Chrome desktop + Chrome Android before submitting

---

## 👤 Author

### Adewale Samson Adeagbo

**Data Scientist · EdTech Builder · Virtual Tutor · AI-Augmented Solutions Developer**

Lagos, Nigeria 🇳🇬

With over **15 years of teaching experience** and a B.Sc.(Ed) in Computer Science Education from Lagos State University (2023), Adewale bridges the gap between data science practice and education. He operates as Visioner/Director/Data Lead at **HMG Concepts** and **HMG Academy**, tutors across platforms including Tuteria and Prepclass, and builds deployed ML/analytics solutions for real-world problems across any domain.

His identity as an **AI-Augmented Solutions Developer** reflects his ability to enter unfamiliar technical domains, learn fast, and deliver professional-quality software — demonstrated concretely by building CBT.ng (a full-featured Computer-Based Testing platform) entirely on an Android tablet with no laptop.

> *"Every project reflects both analytical rigour and a teacher's instinct for clarity, accessibility, and impact."*

| Platform | Link |
|---|---|
| 🔗 LinkedIn | [linkedin.com/in/adewalesamsonadeagbo](https://linkedin.com/in/adewalesamsonadeagbo) |
| 🐙 GitHub | [github.com/cssadewale](https://github.com/cssadewale) |
| 🌐 Portfolio | [cssadewale.pages.dev](https://cssadewale.pages.dev) |
| 🏢 HMG Concepts | [hmgconcepts.business.site](https://hmgconcepts.pages.dev) |
| 📧 Email | hmgconcepts@gmail.com |
| 📧 Alt Email | hismarvellousgrace@gmail.com |
| 📞 Phone | +234 810 086 6322 |

### Other Projects by This Author

| Project | Description | Live Demo |
|---|---|---|
| **CBT.ng** | Free Computer-Based Testing platform (built on Android tablet) | [cssadewale.github.io/cbt-system](https://cssadewale.github.io/cbt-system/student.html) |
| **Employee Burnout Predictor** | NeuroWell Analytics — predicts burnout risk scores | [adewale-burnout-prediction.streamlit.app](https://adewale-burnout-prediction.streamlit.app) |
| **Fake News Detector** | TruthLens Institute — NLP binary classifier | [adewale-fake-news-detector.streamlit.app](https://adewale-fake-news-detector.streamlit.app) |
| **Bank Churn Prediction** | Predicts customer churn probability | [adewale-bank-customer-churn-prediction.streamlit.app](https://adewale-bank-customer-churn-prediction.streamlit.app) |
| **SwiftChain Delivery** | Logistics delay prediction system | [adewale-swiftchain-delivery-prediction.streamlit.app](https://adewale-swiftchain-delivery-prediction.streamlit.app) |
| **Student At-Risk Predictor** | Nigerian JSS/SSS context, SHAP explainability | [student-at-risk-predictor.streamlit.app](https://student-at-risk-predictor.streamlit.app) |
| **Staff Promotion Predictor** | Yakub Trading Group HR analytics | [yakub-promotion-prediction.streamlit.app](https://yakub-promotion-prediction.streamlit.app) |
| **Income Level Predictor** | Binary income classification | [adewale-income-level-prediction.streamlit.app](https://adewale-income-level-prediction.streamlit.app) |

*Full portfolio at [cssadewale.pages.dev](https://cssadewale.pages.dev)*

---

## 📄 License

```
MIT License — Copyright (c) 2025 Adewale Samson Adeagbo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.
```

Full license text: [**LICENSE**](./LICENSE)

---

## ⭐ Support This Project

If Tableau Stimulator has been useful to you:

- ⭐ **Star this repository** — helps others discover it
- 🍴 **Fork it** — build your own version or contribute
- 📣 **Share it** — send the link to anyone who works with data
- 🐛 **Report bugs** — [open an issue](../../issues/new?template=bug_report.md)
- 💡 **Suggest features** — [request a feature](../../issues/new?template=feature_request.md)

---

<div align="center">

**Built with clarity of thought · Powered by free tools · Made in Nigeria 🇳🇬**

*Proving that the barrier to professional software is not hardware — it is clarity of thought.*

---

[🌐 Live App](https://cssadewale.github.io/tableau-stimulator/) &nbsp;·&nbsp;
[👤 LinkedIn](https://linkedin.com/in/adewalesamsonadeagbo) &nbsp;·&nbsp;
[🐙 GitHub](https://github.com/cssadewale) &nbsp;·&nbsp;
[📁 Portfolio](https://cssadewale.pages.dev) &nbsp;·&nbsp;
[🏢 HMG Concepts](https://hmgconcepts.pages.dev)

*© 2025 Adewale Samson Adeagbo · MIT License*

</div>
