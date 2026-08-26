# QuirkMacroAnalytics 
# Personal Wealth & Macro Analytics Dashboard
A custom, data-integrated financial intelligence platform built to centralize macroeconomic indicators, localized real estate trends, quantitative portfolio factor modeling, and money market yield optimizer. A sandbox for my market fixations.

**Live Platform Demo:** [Insert your Porkbun custom domain URL here]
**Stack:** React (Vite), Tailwind CSS, Supabase (Database & Data APIs), Cursor AI, Lovable

---

## Key Operational Modules

### 1. Get Your Macros (Macroeconomic Data Hub)
* **The Problem:** Fagmented data sources (FRED, fin news, government reports) that create friction when tracking macro trends.
* **The Solution:** A unified data tab aggregating what I find to be key macroeconomic indicators into a single, high-density visualization layer. Specific to my current role in the real estate finance world.

### 2. Localized Real Estate Explorer (Zip/City Search)
* **The Problem:** Legacy platforms (Zillow/Redfin/Realtor) are optimized for transactional scrolling rather than quick, on-the-go geographical trend snapshots.
* **The Solution:** A mobile-responsive market intelligence tool. Users input a Zip Code, town, or city to instantly fetch micro-market snapshots, multi-year pricing trends, and localized inventory velocity.

### 3. Quantitative Factor Beta Predictor
* **The Problem:** Retail investors lack accessible tools to track historical asset exposure to underlying risk factors. It's difficult to track ETF/Mutual Fund manager skill by using solely a YTD return metric.
* **The Solution:** A proprietary baseline quantitative model that tracks historical factor beta trends, forecasts forward-looking exposure shifts, and programmatically suggests highly correlated ETFs optimized for predicted factor tailwinds. Uses Fama-French and Carhart factors, select macroeconomic data, and Kalman filter regression to predict funds with potential for outsized returns.

### 4. Short Term Cash Yield Optimization Engine
* **The Problem:** Inefficient cash drag due to the friction of manually parsing floating 30-Day SEC yields across short-duration Treasury funds. 
* **The Solution:** A real-time yield standings leaderboard that ranks high-liquidity, low-expense treasury ETFs, automating capital preservation routing for unallocated cash. Manages duration risk to optimize yield.

---

## 🛠️ Data Architecture & Pipeline
* **Frontend:** Componentized React architecture with utility-first Tailwind CSS for high-density financial data layouts.
* **Backend & API Layer:** Supabase relational data models handling user queries, geographic parameters, and financial asset metadata.
* **Development Workflow:** Initial rapid UI/UX scaffolding executed via Lovable AI; deep logic integration, Supabase API wiring, and styling refactored locally utilizing Cursor (Claude 3.5 Sonnet engine).
