# Project Portfolio

Hi, I'm Rishabh Jain. I'm a Business Professional with 4+ years of professional experience working with data,strategy and execution.

 Welcome to my Portfolio!

I work for solutions to real life challenges. My passion is rooted in optimization. I always aim to work on challenges that addresses our everyday friction and affect how we live and work. This portfolio is a showcase of my skills that spans understanding about data in different industries , business strategy in real world and my curiosity for solving various problems.

## Projects


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
The result really came out to be

Model Accuracy     : **87%** (Validated against 2024 outcomes).
The Eureka Moment  : Identified the 3rd hour of play as the "stamina tipping point" where youth overrides experience. 
The Forecast       : Highlighted **Jannik Sinner** as the dominant force for 2025 due to his elite Elo-to-Age ratio. 

[**View Project**](https://github.com/Ri-jain/Sport-Analytics)

---------------------------

## Mobility Optimization & Analyis

### 1.MBTA Commuter Rail Optimization 

## Inspiration Behind :
As someone who love to travel and explore cities, this project idea came about as a part of Business Modelling class at Northeastern University. Having travelled to Tokyo, past year, I was really fascinated by tokyo's rail infrastructure and how they managed to optimize their infrastructe and run different categories of trains on same infrastructure. This really motivated me to be creative and come up with a solution where we prototyped a new express line on Boston's MBTA Commuter rail infrastructure.

## Strategy Behind:
I engineered a data-driven model to identify service gaps and architect a new "Express" tier:

01. Demographic Layering        :  Integrated MBTA usage data with District Population data to ensure our model prioritized high-density neighborhoods and maintained social equity.
02. Integer Programming (PuLP)  : Developed a mathematical optimization model in Python to identify "low-impact" stops to bypass, maximizing speed while preserving essential service connections.
03. Financial Stress-Testing    : Executed a 1,000-iteration Monte Carlo simulation to forecast revenue growth and ridership elasticity, ensuring the model was as profitable as it was fast.

I focused on a Zero-CapEx framework. The goal was to prove that the most powerful tool for urban transit isn't more concrete, but better data optimization.

## How it all came out

Efficiency Gain        : 9.25 Minutes saved per trip, scaling to thousands of commuter hours saved annually.
Revenue Impact         : $18.6M Projected Annual Growth driven by increased service frequency and ridership.
Environmental ROI      : Estimated removal of 6,300+ cars from Boston roads daily, significantly reducing urban carbon emissions.

[**View Project**](https://github.com/Ri-jain/MBTA-Optimization-Project)

-------

### 2. European Air Traffic Trends (2016–2024)

## Inspiration Behind :
Growing up, I always had a fascination with aviation. While my career path led me to data, I’ve never lost that fascination with how the world moves through the sky. So this project really came as a part of a Data Mining Class at Northeastern University. When the pandemic grounded global fleets, I saw a unique opportunity to study a "system in reset." I took on this project to quantify the resilience of the aviation industry, tracking how 300,000+ flights navigated the friction of COVID-19 and Brexit to find a new "normal."

## Strategy Behind:

01. Data Harmonization: Standardized and merged over 300,000 records from Kaggle, Eurostat, and ACI Europe, creating a unified time-series spanning 2016 to 2024.
02. Predictive Modeling: Developed Moving Average models to forecast traffic trends. I adjusted these models to account for "black swan" events like lockdowns and the structural shifts caused by Brexit.
03. Segmentation Analysis: Beyond raw volume, I analyzed the divergence between Low-Cost Carriers (LCCs) and traditional hubs to identify who was truly driving the recovery.

I focused on Trend Elasticity. By achieving high model accuracy, I was able to distinguish between temporary seasonal spikes and permanent shifts in European travel behavior.
  
## How it all came out

Predictive Power: Achieved a 95%+ R² score in year-over-year traffic modeling, accurately capturing the recovery curve.
Market Insight: Discovered that just 10 airports drove over 40% of the total passenger recovery, signaling a massive concentration of traffic in key leisure hubs.
Strategic Shift: Identified a permanent lag in business travel at major hubs (London/Frankfurt), contrasted by the aggressive dominance of LCCs in Southern and Eastern Europe.

[**View Project**](https://github.com/Ri-jain/European-Air-Traffic-Analysis)

-----------------------------




