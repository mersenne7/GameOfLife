# ADULTING: Modern Life Simulator

> A contemporary, systems-driven life simulation game exploring the socio-economic realities, financial trade-offs, and holistic well-being challenges of 21st-century adulthood.

---

## 🎯 Project Objective

Traditional life-simulation games (such as the classic 1960s *The Game of Life*) were designed around a mid-20th-century economic playbook: go to college, secure a lifelong corporate job, purchase a suburban home, and retire wealthy.

**ADULTING: Modern Life Simulator** redesigns this formula from the ground up for the modern era. The core objective of this project is to simulate the complex, interconnected trade-offs required to navigate adult life from **Age 18 to 70**. Players must balance economic survival with mental, physical, and relational well-being, demonstrating that financial wealth without health or social connection is a recipe for burnout.

Success is measured not merely by net worth, but by the **Holistic Fulfillment Index (0–100)**—a composite metric reflecting four pillars:
1. **Financial Independence** (Liquid cash, portfolio assets, equity/RSUs, and debt service)
2. **Mental Sanity** (Mitigating burnout, workplace friction, and chronic stress)
3. **Physical Vitality** (Longevity habits, health crises, and ergonomic strain)
4. **Social Capital** (Community networks, family, friendships, and mutual aid)

---

## 🏗️ Technical Architecture & Core Systems

The entire application is constructed with a **zero-dependency, single-file architecture** contained in [`index.html`](index.html), running natively in any modern web browser using standard web technologies:

### 1. Node-Graph State Machine & SVG Board
- **Procedural SVG Rendering (`#lifeBoardSvg`)**: Renders a 27-node winding path from Age 18 to 70 with responsive vector geometry, status rings, and interactive tooltips.
- **Non-Linear Branching Dilemmas**: Incorporates critical career crossroads (e.g., *Age 26 Hustle Culture vs. 4-Day Work Week*, *Age 37 Executive Golden Handcuffs vs. Sabbatical*, *Age 55 Corporate Advisory vs. Community Mentorship*) that branch the physical graph topology.

### 2. Comprehensive Financial & Cashflow Simulation Engine
- **Dynamic Cashflow Ledger**: Computes annual after-tax income, baseline living costs indexed to inflation, housing costs (roommate splits, solo rent, or mortgage amortization), dependent/childcare expenses, subscription creep, and debt obligations.
- **Multi-Asset Portfolio Modeling**:
  - **HYSA (High-Yield Savings)**: Stable compound interest yielding ~4.5% APY.
  - **Broad-Market Index Funds**: Stochastic market returns (-3% to +15% annual drift).
  - **Startup Equity (RSUs)**: Illiquid equity units tied to company valuation cycles.
  - **Cryptocurrency**: High-volatility speculative asset (-42% to +68% drift).
  - **Real Estate**: Property value appreciation paired with compounding mortgage interest.
- **Macroeconomic Volatility Engine**: Simulates fluctuating macro regimes (*Bull Rally*, *Steady*, *Inflation Spike*, *Tech Cooling*) affecting base inflation and borrowing interest rates.

### 3. Holistic Well-Being & Resilience Mechanics
- **Burnout & Insolvency Safety Nets**: Replaces arbitrary "Game Over" states with realistic **Emergency Lifestyle Restructures** (medical leaves, downsizing, debt consolidation) to model resilience and recovery.
- **Micro-Intervention Deck**: Players can actively allocate capital toward preventive interventions: therapy/coaching (+Sanity), preventive health/ergonomics (+Health), neighborhood supper clubs (+Social), or auditing phantom subscription costs.

### 4. Legacy Evaluation & Archetype Scoring Engine
- Evaluates the player's life path upon reaching Age 70 across all four domains with letter grades (S/A/B/C/D) and dynamically determines their life archetype (e.g., *The Renaissance Adult*, *The Burned-Out Titan*, *The Zen Longevity Architect*, *The Beloved Community Pillar*).

---

## 🚀 Getting Started

No build tools, bundlers, or package managers are required.

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/mersenne7/GameOfLife.git
   ```
2. Open [`index.html`](index.html) in any modern desktop or mobile browser:
   - On Windows: Double-click `index.html` or run:
     ```powershell
     Start-Process index.html
     ```
   - On macOS/Linux:
     ```bash
     open index.html   # macOS
     xdg-open index.html # Linux
     ```

---

## 🕹️ Game Loop Summary

1. **Select Launchpad**: Choose an initial launch profile at Age 18 (*4-Year University Degree*, *Intensive Tech Bootcamp*, *Trade/Gig Hustle*, or *Indie Creator/Solopreneur*).
2. **Spin the Wheel**: Advance through the life cycle, navigating modern hiccups, market shocks, and career milestones.
3. **Make Conscious Crossroads Decisions**: Choose between short-term financial acceleration and long-term sustainability.
4. **Manage Capital Allocation**: Balance cash reserves, debt paydown, investment accounts, and preventive self-care.
5. **Review Your Legacy**: Reach Age 70 and review your holistic life grade and archetype report.
