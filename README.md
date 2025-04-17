# 📊 Retail Spending Index Dashboard

**An interactive, PCA-weighted visualization of U.S. retail economic indicators**  
_Built with React, Recharts, TailwindCSS, PapaParse, and chrono-node_

---

## 📌 Table of Contents

- [Overview](#overview)
- [Why This Matters](#why-this-matters)
- [Live Demo](#live-demo)
- [Tech Stack](#tech-stack)
- [How It Works](#how-it-works)
- [Project Structure](#project-structure)
- [Run It Yourself](#run-it-yourself)
- [Data Sources & Methodology](#data-sources--methodology)
- [License](#license)

---

## 🧠 Overview

This dashboard simulates a **Principal Component Analysis (PCA)-weighted Retail Spending Index**, allowing users to visually interpret economic trends in the U.S. consumer market. Built for economists, policy advisors, and academic researchers, this dashboard integrates multiple macroeconomic indicators to surface a unified economic signal.

Key features:
- 📈 Time-series analysis of consumer retail activity
- 🧮 Dynamic visualization of PCA weight contributions
- 🗃 Embedded CSVs for instant use, with architecture ready for file uploads
- 🎨 Clean, professional UI with responsive charts

---

## 🧭 Why This Matters

From **inflation trends** to **economic recovery tracking**, consumer spending data serves as a pulse-check on the economy.

> “Retail sales are the canary in the coal mine of economic slowdowns.”  
> — *Harvard Business Review, 2023*

Traditional time-series graphs often fall short when policymakers and analysts need to:
- Compare multi-indicator datasets simultaneously
- Understand the relative importance (weight) of each component
- Simulate economic signals under varying conditions

This dashboard bridges that gap using PCA-weighted modeling and modern data storytelling. It empowers:
- **Economists** to explore structural economic shifts
- **Policy advisors** to test sensitivity of spending indicators
- **Census Bureau teams** to improve composite index communication
- **Educators and researchers** to teach PCA and macroeconomic forecasting

---

## 🚀 Live Demo

> [🟢 Try the Dashboard in CodeSandbox →](https://codesandbox.io/)

*(Or copy the HTML from below and run locally)*

---

## ⚙️ Tech Stack

| Layer        | Technology                                       |
|--------------|--------------------------------------------------|
| 📦 Framework | **React** (18.x via CDN)                         |
| 📊 Charts    | **Recharts**                                     |
| 🎨 Styling   | **TailwindCSS** (CDN-based)                      |
| 📄 CSV Parse | **PapaParse**                                    |
| 🕰 Dates     | **chrono-node** for natural language date parsing|
| 📁 Data      | Embedded CSV (no backend/API required)           |

---

## 🧪 How It Works

### Retail Spending Index

- Loads embedded CSV containing retail index values over time
- Parses with `PapaParse`, transforms with `chrono-node`
- Renders in a responsive `LineChart`

### PCA Component Weights

- Loads weights from a second embedded CSV
- Reformats into a series showing each component’s PCA weight
- Renders contributions with distinct color-coded lines

Both plots support:
- Tooltips
- Axis labeling
- Responsive containers
- Natural date handling

---

## 📁 Project Structure

```text
.
├── index.html          # All code, CSVs, and logic embedded
├── README.md           # Project documentation
└── (Optional) styles.css  # For custom transitions, themes
```

---

## 💻 Run It Yourself

### ✅ Option 1: CodeSandbox

Paste the code into a new [CodeSandbox](https://codesandbox.io/) under `index.html`.

### ✅ Option 2: Local HTML file

1. Save the code below as `index.html`
2. Open it in any modern browser

```html
<!-- Paste final version of the HTML file here -->
<!-- See the latest version in the repo or CodeSandbox link -->
```

---

## 📊 Data Sources & Methodology

### Embedded CSVs

- **Retail Index CSV**: Simulated monthly index data (normalized to 100 base)
- **Weights CSV**: PCA components for major economic indicators such as:
  - Retail Sales
  - Inventory Metrics
  - Business Applications (proxy for entrepreneurial activity)

### PCA Explained

Principal Component Analysis (PCA) is a dimensionality reduction technique used here to combine multiple economic signals into a single index. This allows us to:
- Reduce noise
- Capture dominant trends
- Reveal co-movement among indicators

---

## 📜 License

MIT License. Free for academic, nonprofit, and commercial use with attribution.

---

## ✍️ Author

Built by a data analyst passionate about economic storytelling and macro strategy modeling.

> Want to contribute? Fork the repo or open an issue!

---

```

Let me know if you’d like a version of the README with screenshots, a downloadable ZIP, or one customized for deployment (e.g., GitHub Pages).
