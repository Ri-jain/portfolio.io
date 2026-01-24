# Project Portfolio

Hi, I'm Rishabh Jain. I'm a Business Professional with 4+ years of professional experience working with data,strategy and execution.

 Welcome to my Portfolio!

I work for solutions to real life challenges. My passion is rooted in optimization. I always aim to work on challenges that addresses our everyday friction and affect how we live and work. This portfolio is a showcase of my skills that spans understanding about data in different industries , business strategy in real world and my curiosity for solving various problems.

## PROJECTS


## Sport Analytics
## US Open - ATP Prediction Model

### Inspiration Behind :
As a recreational tennis player and a fan, I’ve always been fascinated by the invisible factors that decide a Grand Slam, like how a veteran’s mental toughness holds up against a younger player’s physical stamina. I noticed that standard sports stats often miss these 'human' elements. I took on this project to see if I could build a more holistic model that doesn't just look at who won, but why they won, accounting for the friction of age, recovery, and high-pressure moments. This project was a passion project.

### Strategy Behind:
I designed a three-layered approach to simulate reality, moving beyond raw statistics:

01. Scouting the Data           : Scraped 6 years of ATP match data (2019-2024) to establish a baseline of player "DNA."
02. Engineering Human Features  :  Created **Stamina Curves** (based on age/match duration) and **Pressure-Point Conversion** rates to account for mental fatigue.
03. The Simulation              :  Executed a **10,000-round Monte Carlo loop** to forecast the 2025 US Open, finding the most probable "path to victory."

I prioritized **Elo Ratings** over standard ATP Rankings. In a high-friction sport like tennis, momentum in the last 30 days is a much stronger predictor of success than a 12-month average.

### How it all came out:
The model achieved an 87% accuracy rate when validated against historical outcomes. The most significant finding was the "3rd-hour tipping point," identifying exactly when physical stamina begins to override veteran experience. Based on an elite Elo-to-Age ratio, the model highlighted Jannik Sinner as the dominant force for the 2025 season.

### What this Changes:
This model moves the needle for Sports Broadcasting by enabling real-time "Live Win-Probability" graphics that factor in player fatigue, making the viewer experience more immersive. Additionally, it offers Coaching Staffs a data-backed blueprint to adjust conditioning or on-court tactics—such as playing more aggressively to shorten points as players approach their identified fatigue thresholds.

[**View Project**](https://github.com/Ri-jain/Sport-Analytics)

---------------------------

## Mobility Optimization & Analyis

## 1.MBTA Commuter Rail Optimization 

### Inspiration Behind :
As someone who love to travel and explore cities, this project idea came about as a part of Business Modelling class at Northeastern University. Having travelled to Tokyo, past year, I was really fascinated by tokyo's rail infrastructure and how they managed to optimize their infrastructe and run different categories of trains on same infrastructure. This really motivated me to be creative and come up with a solution where we prototyped a new express line on Boston's MBTA Commuter rail infrastructure.

### Strategy Behind:
I engineered a data-driven model to identify service gaps and architect a new Express tier:

01. Demographic Layering        :  Integrated MBTA usage data with District Population data to ensure our model prioritized high-density neighborhoods and maintained social equity.
02. Integer Programming (PuLP)  : Developed a mathematical optimization model in Python to identify "low-impact" stops to bypass, maximizing speed while preserving essential service connections.
03. Financial Stress-Testing    : Executed a 1,000-iteration Monte Carlo simulation to forecast revenue growth and ridership elasticity, ensuring the model was as profitable as it was fast.

I focused on a Zero-CapEx framework. The goal was to prove that the most powerful tool for urban transit isn't more concrete, but better data optimization.

### How it all came out: 
The prototype demonstrated a 9.25-minute saving per trip, which scales to thousands of hours saved for the Boston workforce annually. The financial impact is equally significant, with a $18.6M projected increase in annual revenue driven by ridership growth. Environmentally, the model predicts the removal of 6,300+ cars from Boston roads daily, showcasing that the best tool for urban transit isn't more concrete, but better data optimization.

### What this Changes:
This project reshapes Urban Policy by proving that city planners can achieve modernized results through low-cost software and scheduling overhauls rather than massive construction budgets. It also lays the groundwork for Dynamic Scheduling, suggesting a future where the MBTA implements "Smart Scheduling" that adjusts express routes in real-time based on live population movement or weather-driven demand.

[**View Project**](https://github.com/Ri-jain/MBTA-Optimization-Project)

-------

## 2. European Air Traffic Trends (2016–2024)

### Inspiration Behind:
Growing up, I always had a fascination with aviation. While my career path led me to data, I’ve never lost that fascination with how the world moves through the sky. So this project really came as a part of a Data Mining Class at Northeastern University. When the pandemic grounded global fleets, I saw a unique opportunity to study a "system in reset." I took on this project to quantify the resilience of the aviation industry, tracking how 300,000+ flights navigated the friction of COVID-19 and Brexit to find a new "normal."

### Strategy Behind:
01. Data Harmonization: Standardized and merged over 300,000 records from Kaggle, Eurostat, and ACI Europe, creating a unified time-series spanning 2016 to 2024.
02. Predictive Modeling: Developed Moving Average models to forecast traffic trends. I adjusted these models to account for "black swan" events like lockdowns and the structural shifts caused by Brexit.
03. Segmentation Analysis: Beyond raw volume, I analyzed the divergence between Low-Cost Carriers (LCCs) and traditional hubs to identify who was truly driving the recovery.

I focused on Trend Elasticity. By achieving high model accuracy, I was able to distinguish between temporary seasonal spikes and permanent shifts in European travel behavior.
  
### How it all came out:
The models achieved a 95%+ R² score, accurately capturing the sky's recovery curve. The analysis revealed a massive concentration of traffic, with just 10 airports driving over 40% of the passenger recovery. It also identified a permanent structural shift: a lag in business travel at major hubs like London and Frankfurt, contrasted by the aggressive dominance of LCCs in Southern and Eastern Europe.

### What this Changes:
These insights allow for a massive shift in Airline Strategy, suggesting a move away from wide-body "Hub-to-Hub" investment toward smaller, fuel-efficient planes for high-growth LCC routes. From an Economic Forecasting perspective, government tourism boards can use this recovery data to predict future hospitality demand, ensuring that regional infrastructure keeps pace with passenger surges in leisure hubs

[**View Project**](https://github.com/Ri-jain/European-Air-Traffic-Analysis)

-----------------------------

## Healthcare Analytics

### Inspiration Behind:
This came as another passion project. Healthcare is an environment defined by high stakes and high friction, where delays in data can lead to delays in critical care. I wanted to apply my optimization mindset to a field where better data directly impacts human lives. This project was driven by a desire to move from reactive hospital management to a proactive, data-driven system that anticipates patient needs before they become emergencies.

### Strategy Behind:
I treated the patient journey as a complex system requiring precise technical interventions:

01. Bottleneck Identification: Analyzed over 26,000 inpatient records to identify care delivery bottlenecks and optimize resource allocation for specialty surgical procedures.
02. Risk Stratification Modeling: Developed predictive risk models using Logistic Regression and Decision Trees to forecast patient readmission risks.
03. Clinical KPI Engineering: Engineered critical metrics such as Length-of-Stay and Cost-to-Serve to visualize provider performance and translate complex clinical data into actionable strategies.

I focused on Clinical Actionability, simulating a Patient Support Program (PSP) to enable proactive, targeted interventions for high-risk patient cohorts.

### How it all came out:

The project demonstrated that large-scale clinical datasets can be transformed into clear roadmaps for improving health outcomes. By moving away from anecdotal observations and toward evidence-based strategies, the model provides a Single Source  for hospital administrators to optimize surgical throughput and reduce the likelihood of patient readmission.

### What this Changes:

This work changes the Healthcare Management landscape by shifting the focus from simply "managing volume" to "optimizing the quality of the pathway." By implementing these risk models, hospitals can pivot toward Value-Based Care, where resource allocation is tied directly to recovery outcomes rather than procedure counts. Furthermore, it proves that Digital Health Interventions can be used to scale patient support beyond the hospital walls, reducing the burden on physical ER infrastructure.

[**View Project**](https://github.com/Ri-jain/Healthcare_Analytics)
