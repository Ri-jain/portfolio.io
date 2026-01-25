<style>
  /* Fills the white space on the left */
  @media screen and (min-width: 1200px) {
    #project-sidebar {
      position: fixed;
      left: 30px; 
      top: 450px; 
      width: 180px;
      z-index: 100;
      border-right: 1px solid #eee;
      padding-right: 10px;
      font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    }
    #project-sidebar ul { list-style: none; padding: 0; margin: 0; }
    #project-sidebar li { margin-bottom: 12px; font-size: 14px; }
    #project-sidebar a { color: #39c; text-decoration: none; display: block; }
    #project-sidebar a:hover { color: #222; font-weight: bold; }
    .nav-header { font-size: 11px; font-weight: bold; margin: 15px 0 5px 0; color: #666; letter-spacing: 1px; text-transform: uppercase; }
  }
  @media screen and (max-width: 1199px) { #project-sidebar { display: none; } }
</style>

<div id="project-sidebar">
  <p style="font-weight: bold; color: #333; font-size: 15px; margin-bottom: 10px;">Project Index</p>

  <p class="nav-header">Data Analytics</p>
  <ul>
    <li><a href="#sport-analytics">Sport Analytics</a></li>
    <li><a href="#mobility-analytics">Mobility Optimization</a></li>
    <li><a href="#healthcare-analytics">Healthcare Analytics</a></li>
  </ul>

  <p class="nav-header">Strategy & Consulting</p>
  <ul>
    <li><a href="#chipotle-strategy">Chipotle India Strategy</a></li>
  </ul>
</div>

# Project Portfolio

Hi, I'm Rishabh Jain. I'm a Business Professional with 4+ years of professional experience working with data, strategy, and execution.

Welcome to my Portfolio! I work on solutions to real-life challenges, rooted in optimization. This portfolio is a showcase of my skills that spans understanding about data in different industries, business strategy in real world and my curiosity for solving various problems.

## PROJECTS

## Sport Analytics <a name="sport-analytics"></a>
### US Open - ATP Prediction Model

**Inspiration Behind:**
As a recreational tennis player, I noticed standard sports stats often miss 'human' elements. I took on this project to build a more holistic model accounting for the friction of age, recovery, and high-pressure moments.

**Strategy Behind:**
1. **Scouting:** Scraped 6 years of ATP match data (2019-2024).
2. **Engineering:** Created **Stamina Curves** and **Pressure-Point Conversion** rates.
3. **Simulation:** Executed a **10,000-round Monte Carlo loop**.

**How it all came out:**
Achieved **87% accuracy** and identified the "3rd-hour tipping point" where youth overrides experience.

**What this Changes:**
Enables real-time **Win-Probability** graphics for broadcasting and provides coaches with data-backed thresholds to adjust tactics as players approach fatigue.

---

## Mobility Optimization & Analysis <a name="mobility-analytics"></a>
### 1. MBTA Commuter Rail Optimization

**Inspiration Behind:**
Inspired by Tokyo's rail infrastructure, I prototyped a new express line for Boston's MBTA to optimize service without adding new concrete infrastructure.

**Strategy Behind:**
1. **Demographic Layering:** Integrated MBTA usage with district population data for social equity.
2. **Optimization:** Used **Integer Programming (PuLP)** to identify "low-impact" stops to bypass.
3. **Stress-Testing:** Executed a **1,000-iteration Monte Carlo simulation** for revenue forecasting.

**How it all came out:**
Demonstrated **9.25 minutes saved** per trip and **$18.6M projected annual revenue growth**.

**What this Changes:**
Proves city planners can modernize transit through **low-cost scheduling overhauls** rather than billion-dollar construction budgets.

---

## Healthcare Analytics <a name="healthcare-analytics"></a>
### Patient Care Pathway Optimization

**Inspiration Behind:**
Healthcare is a high-stakes environment where data delays equal care delays. I applied optimization to move from reactive to proactive care.

**Strategy Behind:**
1. **Bottleneck Identification:** Analyzed **26,000+ inpatient records** to optimize surgical throughput.
2. **Risk Modeling:** Developed **Logistic Regression and Decision Tree** models for readmission risk.
3. **KPI Engineering:** Engineered metrics like **Length-of-Stay** and **Cost-to-Serve**.

**How it all came out:**
Simulated a Patient Support Program (PSP) to enable proactive interventions for high-risk cohorts.

**What this Changes:**
Pivots healthcare toward **Value-Based Care**, scaling digital support beyond hospital walls to reduce ER infrastructure burden.

---

## Strategy & Consulting

## Chipotle: Market Entry Strategy in India <a name="chipotle-strategy"></a>

**Inspiration Behind:**
Architected a "Reverse Globalization" framework to solve the localization puzzle of bringing a global brand into India's complex, high-friction market.

**Strategy Behind:**
1. **Competitive Benchmarking:** Used **Porter’s Five Forces** and **Value Chain Analysis**.
2. **Financial Logic:** Identified a 77% cost reduction via local sourcing ($420k vs $1.8M US cost).
3. **De-risking:** Recommended a **Joint Venture model** to leverage local supply chain expertise.

**How it all came out:**
Developed a strategic blueprint with an **18-24 month break-even** timeline and a roadmap to navigate the FDI landscape.

**What this Changes:**
Shifts global expansion toward **Strategic Resilience**, using **Local Supply Chain Innovation** to maintain brand values while meeting local economic realities.

[**View Full Report**](https://github.com/Ri-jain/Chipotle-India-Entry-/blob/main/Full-Report.pdf)
