---
layout: default
title: Portfolio
---

<style>
  /* Sidebar for Desktop - Filling the white space */
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

Welcome to my Portfolio! I work for solutions to real-life challenges. My passion is rooted in optimization. I always aim to work on challenges that address our everyday friction and affect how we live and work. This portfolio is a showcase of my skills that spans understanding about data in different industries, business strategy in the real world, and my curiosity for solving various problems.

## PROJECTS

---

## Sport Analytics <a name="sport-analytics"></a>
## US Open - ATP Prediction Model

### Inspiration Behind:
As a recreational tennis player and a fan, I’ve always been fascinated by the invisible factors that decide a Grand Slam, like how a veteran’s mental toughness holds up against a younger player’s physical stamina. I noticed that standard sports stats often miss these 'human' elements. I took on this project to see if I could build a more holistic model that doesn't just look at who won, but why they won, accounting for the friction of age, recovery, and high-pressure moments.

### Strategy Behind:
I designed a three-layered approach to simulate reality, moving beyond raw statistics:
1. **Scouting the Data:** Scraped 6 years of ATP match data (2019-2024) to establish a baseline of player "DNA".
2. **Engineering Human Features:** Created **Stamina Curves** (based on age/match duration) and **Pressure-Point Conversion** rates to account for mental fatigue.
3. **The Simulation:** Executed a **10,000-round Monte Carlo loop** to forecast the 2025 US Open, finding the most probable "path to victory".

I prioritized **Elo Ratings** over standard ATP Rankings. In a high-friction sport like tennis, momentum in the last 30 days is a much stronger predictor of success than a 12-month average.

### How it all came out:
The model achieved an **87% accuracy rate** when validated against 2024 outcomes. The most significant finding was the **"3rd-hour tipping point,"** identifying exactly when physical stamina begins to override veteran experience. Based on an elite Elo-to-Age ratio, the model highlighted **Jannik Sinner** as the dominant force for the 2025 season.

### 🚀 What this Changes:
This model moves the needle for **Sports Broadcasting** by enabling real-time "Live Win-Probability" graphics that factor in player fatigue, making the viewer experience more immersive. Additionally, it offers **Coaching Staffs** a data-backed blueprint to adjust conditioning or on-court tactics—such as playing more aggressively to shorten points—as players approach their identified fatigue thresholds.

[**View Project**](https://github.com/Ri-jain/Sport-Analytics)

---

## Mobility Optimization & Analysis <a name="mobility-analytics"></a>
## 1. MBTA Commuter Rail Optimization 

### Inspiration Behind:
As someone who loves to travel and explore cities, this project idea came about as a part of a Business Modeling class at Northeastern University. Having traveled to Tokyo last year, I was fascinated by their rail infrastructure and how they managed to run different categories of trains on the same infrastructure. This motivated me to prototype a new express line on Boston's MBTA Commuter rail infrastructure.

### Strategy Behind:
I engineered a data-driven model to identify service gaps and architect a new Express tier:
1. **Demographic Layering:** Integrated MBTA usage data with District Population data to ensure our model prioritized high-density neighborhoods and maintained social equity.
2. **Integer Programming (PuLP):** Developed a mathematical optimization model in Python to identify "low-impact" stops to bypass, maximizing speed while preserving essential service connections.
3. **Financial Stress-Testing:** Executed a **1,000-iteration Monte Carlo simulation** to forecast revenue growth and ridership elasticity, ensuring the model was profitable.

I focused on a **Zero-CapEx framework**. The goal was to prove that the most powerful tool for urban transit isn't more concrete, but better data optimization.

### How it all came out: 
The prototype demonstrated a **9.25-minute saving per trip**, scaling to thousands of commuter hours saved annually. The financial impact is significant, with an **$18.6M projected annual revenue growth** driven by increased service frequency. Environmentally, the model predicts the removal of **6,300+ cars** from Boston roads daily, significantly reducing urban carbon emissions.

### 🚀 What this Changes:
This project reshapes **Urban Policy** by proving that city planners can achieve modernized results through low-cost software and scheduling overhauls rather than massive construction budgets. It also lays the groundwork for **Dynamic Scheduling**, suggesting a future where the MBTA implements "Smart Scheduling" that adjusts express routes in real-time based on live population movement or demand.

[**View Project**](https://github.com/Ri-jain/MBTA-Optimization-Project)

---

## 2. European Air Traffic Trends (2016–2024)

### Inspiration Behind:
Growing up, I always had a fascination with aviation. While my career path led me to data, I’ve never lost that fascination with how the world moves through the sky. This project, developed for a Data Mining class at Northeastern, studied the aviation industry as a "system in reset" following the pandemic. I took on this project to quantify resilience, tracking how 300,000+ flights navigated the friction of COVID-19 and Brexit.

### Strategy Behind:
1. **Data Harmonization:** Standardized and merged over **300,000 records** from Kaggle, Eurostat, and ACI Europe to create a unified time-series spanning 2016 to 2024.
2. **Predictive Modeling:** Developed **ARIMA and Moving Average models** to forecast traffic trends, accounting for "black swan" events like lockdowns.
3. **Segmentation Analysis:** Analyzed the divergence between Low-Cost Carriers (LCCs) and traditional hubs to identify who was truly driving the recovery.

### How it all came out:
The models achieved a **95%+ R² score**, accurately capturing the recovery curve. The analysis revealed a massive concentration of traffic, with just **10 airports driving over 40% of the passenger recovery**. It also identified a permanent structural shift: a lag in business travel at major hubs like London and Frankfurt, contrasted by the aggressive dominance of LCCs in Southern and Eastern Europe.

### 🚀 What this Changes:
These insights allow for a massive shift in **Airline Strategy**, suggesting a move away from wide-body "Hub-to-Hub" investment toward smaller, fuel-efficient planes for high-growth LCC routes. From an **Economic Forecasting** perspective, government tourism boards can use this recovery data to predict future hospitality demand, ensuring regional infrastructure keeps pace with passenger surges.

[**View Project**](https://github.com/Ri-jain/European-Air-Traffic-Analysis)

---

## Healthcare Analytics <a name="healthcare-analytics"></a>
### Patient Care Pathway Optimization

### Inspiration Behind:
Healthcare is an environment defined by high stakes and high friction, where delays in data can lead to delays in critical care. I wanted to apply my optimization mindset to a field where better data directly impacts human lives. This project was driven by a desire to move from reactive hospital management to a proactive, data-driven system that anticipates patient needs before they become emergencies.

### Strategy Behind:
I treated the patient journey as a complex system requiring precise technical interventions:
1. **Bottleneck Identification:** Analyzed over **26,000 inpatient records** to identify care delivery bottlenecks and optimize resource allocation for specialty surgical procedures.
2. **Risk Stratification Modeling:** Developed predictive risk models using **Logistic Regression and Decision Trees** to forecast patient readmission risks.
3. **Clinical KPI Engineering:** Engineered critical metrics such as **Length-of-Stay and Cost-to-Serve** to visualize provider performance and translate complex clinical data into actionable strategies.

### How it all came out:
The project demonstrated that large-scale clinical datasets can be transformed into clear roadmaps for improving health outcomes. By moving away from anecdotal observations, the model provides a **"Single Source of Truth"** for hospital administrators to optimize surgical throughput and reduce the likelihood of patient readmission.

### 🚀 What this Changes:
This work changes the **Healthcare Management** landscape by shifting the focus from simply "managing volume" to **Value-Based Care**. By implementing these risk models, hospitals can pivot toward models where resource allocation is tied directly to recovery outcomes. Furthermore, it proves that **Digital Health Interventions** can be used to scale patient support beyond hospital walls, reducing the burden on physical ER infrastructure.

[**View Project**](https://github.com/Ri-jain/Healthcare_Analytics)

---

## Strategy & Consulting 

## Chipotle: Market Entry Strategy in India <a name="chipotle-strategy"></a>

### Inspiration Behind:
This project was born from an interest in **"Reverse Globalization"**—the complex challenge of adapting a global brand to a high-friction market. As a Business Analytics student with an MBA, I architected a market entry strategy for **Chipotle Mexican Grill’s** entry into India. We wanted to solve the ultimate localization puzzle: maintaining a core brand identity ("Food with Integrity") in a market where 30% of consumers follow strict vegetarian diets and income inequality requires a calibrated pricing strategy.

### Strategy Behind:
We developed a comprehensive investment and operational framework to de-risk Chipotle's expansion:
1. **Market & Competitive Benchmarking:** Performed deep-dive analysis using **Porter’s Five Forces and Value Chain Analysis**. I benchmarked Chipotle against incumbents like Taco Bell and McDonald’s, identifying a "Premium Fresh" gap with a proposed AOV of **₹300-400**.
2. **Cultural & Operational Localization:** Designed a transnational strategy that mandates a high vegetarian menu mix and strict cross-contamination protocols, such as dedicated grills for meat and vegetarian options.
3. **Risk-Mitigated Entry Mode:** Recommended a **Joint Venture** with a local player to leverage an established supply chain and reduce initial entry risk.

### How it all came out:
The report established a clear roadmap for long-term brand building. By focusing on urban hubs like **Delhi, Mumbai, and Bengaluru**, and utilizing flagship physical stores alongside efficient cloud kitchens, the model forecasts scalable growth. The model identifies that a single outlet in India costs approximately **$420,000 (₹3.51 Cr)**—a 77% saving compared to US costs—enabling a **18-24 month break-even timeline**.

### 🚀 What this Changes:
This project shifts the focus for global brands from expansion to **Strategic Resilience**. It proves that successful market entry requires a pivot from standard menus to **Local Supply Chain Innovation**—such as sourcing native biodegradable materials for packaging. For stakeholders, this provides a blueprint for **Asset-Light Expansion**, where core brand values are preserved while operational systems are re-engineered for local economic realities.

[**View Report**](https://github.com/Ri-jain/Chipotle-India-Entry-/blob/main/Full-Report.pdf)
