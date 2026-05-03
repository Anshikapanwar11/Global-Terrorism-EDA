# Global Conflict Mapping: Strategic EDA of the UNGTA Terrorism Dataset

**Author:** Anshika Panwar  
**Project Type:** Exploratory Data Analysis (EDA)  
**Dataset:** United Nations Global Terrorism Analysis (UNGTA) (1970 - 2017)

## Project Overview
The global security landscape is defined by volatility, asymmetry, and rapidly shifting tactical methodologies. This project provides a comprehensive exploratory data analysis of over 180,000 historical terrorist incidents to extract actionable threat intelligence. 

By employing rigorous data wrangling and structured "UBM" (Univariate, Bivariate, Multivariate) visualization techniques, this analysis identifies geographic risk concentrations, evolutionary shifts in attack tactics, and the operational lethality of specific threat groups. The ultimate goal is to equip policymakers, defense contractors, and humanitarian NGOs with the data required to transition from reactive responses to proactive resource allocation.

## Technical Approach
* **Data Wrangling:** Extensive cleaning of a high-dimensional dataset (>100 variables), specifically handling missing casualty metrics and standardizing geographic identifiers for computational efficiency.
* **Visualization Strategy:** 
  * Establishing baseline distributions (e.g., historical attack frequency, dominant weapon types).
  * Analyzing correlations between human cost and geographic regions, and measuring the success probability of specific attack vectors.
  * Mapping complex geopolitical trends over time to identify extreme mass-casualty outliers.
* **Production-Grade Code:** All data visualization pipelines are wrapped in rigorous exception handling (`try-except` blocks) to ensure a flawless, deployment-ready execution.

## Key Insights & Business Impact
1. **The Modern Escalation:** Global incidents spiked exponentially post-2010, indicating that historical security paradigms are insufficient for the modern threat frequency.
2. **Geographic Concentration:** The Middle East & North Africa (MENA) and South Asia account for the overwhelming majority of global casualties, dictating where humanitarian and defense resources must be focused.
3. **Tactical Evolution:** The dataset reveals an aggressive pivot toward Explosives/Bombings, which yield the highest casualty rates and maintain an exceptionally high probability of success. Defense spending must prioritize blast-proofing and explosive detection over conventional small-arms mitigation.
4. **Target Vulnerability:** Private citizens and civilian infrastructure suffer significantly more casualties than hardened military targets.

## Built With
* **Python** (Pandas, NumPy)
* **Matplotlib & Seaborn** (Data Visualization)
* **Jupyter Notebook / Google Colab**

## Repository Contents
* `Global_Terrorism_EDA.ipynb`: The complete, deployment-ready Jupyter Notebook containing all data cleaning, logic, and visualizations.
