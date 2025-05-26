# Lockheed-Martin-Defense-Fleet-Readiness-Optimization-Project
This project simulates, analyzes, and predicts the readiness of a defense aircraft fleet using synthetic but realistic data modeled on Lockheed Martin’s operational landscape.
It combines:
Data analysis
Predictive maintenance modeling
SHAP explainability
Insightful data visualizations

/aircraft_data.csv          → Master list of all aircraft  
/maintenance_data.csv       → Maintenance logs (issues, subsystems, downtime)  
/readiness_data.csv         → Daily mission readiness status  
/flight_data.csv            → Flight utilization records  
/crew_data.csv              → Crew assignment and qualification details  
/Lockheed_Martin.ipynb      → Main Python notebook (predictive modeling + SHAP)  
/Lockheed_Martin DV.ipynb   → Advanced data visualization notebook

Predict high-risk aircraft likely to need maintenance

Use Random Forest models to classify risk levels

Explain predictions using SHAP visualizations

Analyze trends in:

Maintenance frequency

Downtime patterns

Flight hour utilization

Crew availability

Mission readiness over time

Generate actionable insights for operational optimization

##Dataset Details

| File                  | Description                                                    |
| --------------------- | -------------------------------------------------------------- |
| aircraft\_data.csv    | Aircraft type, tail number, service branch, total flight hours |
| maintenance\_data.csv | Subsystem issues, reported faults, resolution, downtime days   |
| readiness\_data.csv   | Date-wise aircraft mission readiness status                    |
| flight\_data.csv      | Daily flight hours, mission type per aircraft                  |
| crew\_data.csv        | Pilot name, qualification, flight hours, status                |

##Insights Provided

Which aircraft types require the most maintenance?

Which subsystems drive the longest downtimes?

How has readiness changed over time?

Which aircraft should be prioritized for proactive maintenance?


