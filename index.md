---
layout: default
title: Portfolio
---

<style>
  /* Sidebar for Desktop - Fills the white space on the left */
  @media screen and (min-width: 1200px) {
    #project-sidebar {
      position: fixed;
      left: 30px; 
      top: 450px; 
      width: 180px;
      z-index: 1000;
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
  <p style="font-weight: bold; color: #333; font-size: 15px; margin-bottom: 10px;">Index</p>

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

&nbsp;

# Project Portfolio

Hi, I'm Rishabh Jain. I'm a Business Professional with 4+ years of professional experience working with data, strategy, and execution.

Welcome to my Portfolio! I work for solutions to real-life challenges. My passion is rooted in optimization. I always aim to work on challenges that address our everyday friction and affect how we live and work. This portfolio is a showcase of my skills that spans understanding about data in different industries, business strategy in real world and my curiosity for always learning and solving problems.

## PROJECTS

---

## Sport Analytics <a name="sport-analytics"></a>
## US Open - ATP Prediction Model

### Inspiration Behind:
As a recreational tennis player and a fan, I’ve always been fascinated by the invisible factors that decide a Grand Slam, like how a veteran’s mental toughness holds up against a younger player’s physical stamina. I noticed that standard sports stats often miss these 'human' elements. I took on this project to see if I could build a more holistic model that doesn't just look at who won, but why they won, accounting for the friction of age, recovery, and high-pressure moments.

### Strategy Behind:
I designed a three-layered approach to simulate reality, moving beyond raw statistics:
1. Scouting the Data:** Scraped 6 years of ATP match data (2019-2024) from Jeff Sackman/ Tennis abstract datasets.
2. Engineering Human Features:** Created Stamina Curves (based on age/match duration) and Pressure-Point Conversion rates to account for mental fatigue.
3. The Simulation:** Executed a 10,000-round Monte Carlo loop to forecast the 2025 US Open, finding the most probable "path to victory".

I prioritized **Elo Ratings** over standard ATP Rankings. Momentum in the last 30 days is a much stronger predictor of success than a 12-month average.

### How it all came out:
The model achieved an 87% accuracy rate when validated against 2024 outcomes. The most significant finding was the 3rd-hour tipping point, identifying exactly when physical stamina begins to override veteran experience. Based on an elite Elo-to-Age ratio, the model highlighted Jannik Sinner as the dominant force for the 2025 season.

### What this Changes:
This model moves the needle for Sports Broadcasting by enabling real-time "Live Win-Probability" graphics that factor in player fatigue. Additionally, it offers Coaching Staffs a data-backed blueprint to adjust conditioning or tactics as players approach their identified fatigue thresholds.

[**View Project**](https://github.com/Ri-jain/Sport-Analytics)

---

## Mobility Optimization & Analysis <a name="mobility-analytics"></a>
## 1. MBTA Commuter Rail Optimization 

### Inspiration Behind:
This project idea came about as a part of a Business Modeling class at Northeastern University. Having traveled to Tokyo last year, I was fascinated by their rail infrastructure and how they managed to run different categories of trains on the same infrastructure. This motivated me to prototype a new express line on Boston's MBTA Commuter rail infrastructure.

### Strategy Behind:
I engineered a data-driven model to identify service gaps and architect a new Express tier:
1. Demographic Layering: Integrated MBTA usage data with District Population data to ensure our model prioritized high-density neighborhoods and maintained social equity.
2. Integer Programming (PuLP): Developed a mathematical optimization model in Python to identify "low-impact" stops to bypass, maximizing speed while preserving essential service connections.
3. Financial Stress-Testing: Executed a 1,000-iteration Monte Carlo simulation to forecast revenue growth and ridership elasticity.

### How it all came out: 
The prototype demonstrated a 9.25-minute saving per trip, scaling to thousands of commuter hours saved annually. The financial impact is significant, with an $18.6M projected annual revenue growth. 

### What this Changes:
This project reshapes Urban Policy by proving that city planners can achieve modernized results through low-cost scheduling overhauls rather than massive construction budgets.

[**View Project**](https://github.com/Ri-jain/MBTA-Optimization-Project)

---

## Healthcare Analytics <a name="healthcare-analytics"></a>
### Patient Care Pathway Optimization

### Inspiration Behind:
Healthcare is an environment defined by high stakes where delays in data can lead to delays in critical care. I wanted to apply my optimization mindset to a field where better data directly impacts human lives. This project was driven by a desire to move from reactive hospital management to a proactive, data-driven system.

### Strategy Behind:
I treated the patient journey as a complex system requiring precise technical interventions:
1. Bottleneck Identification: Analyzed over 26,000 inpatient records to identify care delivery bottlenecks and optimize resource allocation.
2. Risk Stratification Modeling: Developed predictive risk models using Logistic Regression and Decision Trees to forecast patient readmission risks.
3. Clinical KPI Engineering: Engineered critical metrics such as Length-of-Stay and Cost-to-Serve to visualize provider performance.

### How it all came out:
The project demonstrated that large-scale clinical datasets can be transformed into clear roadmaps for improving health outcomes. The model provides a blueprint for hospital administrators to optimize surgical throughput and reduce readmissions.

### What this Changes:
This work changes the Healthcare Management landscape by shifting the focus to Value-Based Care. By implementing these risk models, hospitals can pivot toward models where resource allocation is tied directly to recovery outcomes rather than volume.

[**View Project**](https://github.com/Ri-jain/Healthcare_Analytics)

---

## Strategy & Consulting 

## Chipotle: Market Entry Strategy in India <a name="chipotle-strategy"></a>

### Inspiration Behind:
This project was born from an interest in "Reverse Globalization", the complex challenge of adapting a global brand to a high-friction market. As a Business Analytics student with an MBA, I along with my team architected a market entry strategy for Chipotle Mexican Grill’s entry into India.

### Strategy Behind:
We developed a comprehensive investment and operational framework:
1. Market & Competitive Benchmarking: Performed deep-dive analysis using Porter’s Five Forces and Value Chain Analysis. I benchmarked Chipotle against incumbents like Taco Bell and McDonald’s.
2. Cultural Localization: Designed a transnational strategy that mandates a high vegetarian menu mix and strict cross-contamination protocols.
3. Risk-Mitigated Entry Mode: Recommended a Joint Venture with a local player to leverage an established supply chain and reduce initial entry risk.

### How it all came out:
The report established a clear roadmap for long-term brand building. By focusing on urban hubs like Delhi, Mumbai, and Bengaluru, the model identifies that a single outlet in India costs approximately ₹3.51 Cr, a 77% saving compared to US costs—enabling a 18-24 month break-even timeline.

### What this Changes:
This project proves that successful market entry requires a pivot from standard menus to Local Supply Chain Innovation,such as sourcing native biodegradable materials for packaging. It provides a blueprint for Asset-Light Expansion in emerging economies.

[**View Report**](https://github.com/Ri-jain/Chipotle-India-Entry-/blob/main/Full-Report.pdf)
