BUMBLEBEES — DOSM DATATHON 2026
AI-Driven Tourism Intelligence and Early-Warning System
for Sustainable Tourism Planning in Malaysia

============================================================
1. SOFTWARE REQUIREMENTS
============================================================

Primary dashboard software:
- Microsoft Power BI Desktop
- Version: [INSERT YOUR POWER BI DESKTOP VERSION]

Supporting analysis software:
- Python 3.13 (used for forecasting and AI/ML preprocessing)
- Microsoft Excel (used for data compilation and preparation)

IMPORTANT:
Python is NOT required to open or interact with the submitted Dashboard.pbix.
All final analytical outputs required by the dashboard are already included in
the submitted dashboard/data files.

To check the Power BI version:
Open Power BI Desktop > Help > About Power BI Desktop.

============================================================
2. DASHBOARD FILE
============================================================

Main interactive file:
Dashboard.pbix

Static documentation:
Dashboard.pdf

The Power BI dashboard contains five research-question pages:

RQ1 — Tourism Demand Outlook
RQ2 — Accommodation Capacity
RQ3 — Aviation Demand and Tourism Expenditure
RQ4 — Tourism and Resource Pressure
RQ5 — AI Tourism Sustainability Early-Warning System

============================================================
3. HOW TO OPEN THE DASHBOARD
============================================================

1. Install or open Microsoft Power BI Desktop.
2. Open the file "Dashboard.pbix".
3. Wait for all visuals to finish loading.
4. Use the page tabs at the bottom of the report to navigate between
   RQ1, RQ2, RQ3, RQ4 and RQ5.
5. Use the available slicers, maps and interactive visuals to explore
   the results.
6. Click a state on an interactive map to filter the related
   state-level charts and insights.
7. Click the selected state again, or use the visual's clear-selection
   function, to return to the overall view.

No additional Power BI plugins or custom add-ons are required.

============================================================
4. DASHBOARD NAVIGATION
============================================================

RQ1 — Tourism Demand Outlook
- Displays historical and forecasted hotel guest demand.
- Forecast period: 2026–2030.
- Use the Year and State filters to explore demand patterns.
- The forecast visual shows the expected tourism-demand trajectory
  towards 2030.

RQ2 — Accommodation Capacity
- Compares accommodation supply with tourism demand.
- Displays projected Average Occupancy Rate (AOR) and state-level
  capacity pressure.
- The demand-surge control can be used to examine alternative
  accommodation-pressure scenarios.

RQ3 — Aviation Demand and Tourism Expenditure
- Compares domestic and international aviation activity.
- Presents tourism expenditure and aviation-demand trends.
- Shows the relationship between tourism activity, expenditure and
  aviation accessibility.

RQ4 — Tourism and Resource Pressure
- Compares tourism intensity with resource-consumption pressure.
- Uses state-level tourism, electricity and waste indicators.
- Provides state-level tourism and resource priority profiles.

RQ5 — AI Tourism Sustainability Early-Warning System
- This is the main decision-support page.
- Click a state on the Malaysia risk map to update the state-specific
  information across the page.
- The selected state is shown in the "Current State" card.
- The State Insight panel displays the state's Risk Score,
  Early-Warning Level, AI Profile, AI Confidence and main risk drivers.
- Risk Dimensions shows the state's pressure across the five
  sustainability dimensions.
- AI Profile Membership shows the state's fuzzy membership across
  the four AI profiles.
- AI Recommendation updates according to the selected state's
  dominant risk conditions.
- Demand Shock Scenario shows how the state's sustainability risk
  may change under higher tourism demand.

============================================================
5. IMPORTANT ASSUMPTIONS AND LIMITATIONS
============================================================

1. Tourism-demand forecasts use complete annual hotel guest observations
   from 2017–2025. The 2026 Q1 observation is not treated as a complete
   annual value in the forecasting model.

2. Forecasts for 2026–2030 are model-based estimates and should be
   interpreted as planning projections rather than guaranteed outcomes.

3. Malaysia's national tourism-demand forecast uses Holt/ETS, while
   state-level forecasts use the individually validated best-performing
   forecasting model for each state.

4. The AI early-warning Risk Score is a relative state-level planning
   indicator based on five dimensions:
   - Tourism Demand Pressure
   - Accommodation Capacity Pressure
   - Resource Pressure
   - Aviation Accessibility Gap
   - Economic Value Gap

5. Fuzzy C-Means membership values represent the degree of membership
   in an AI profile. They are NOT calibrated probabilities.

6. The early-warning classification is intended as a decision-support
   tool and is not an official regulatory tourism-risk rating.

7. Data availability differs by indicator and year. The latest available
   observations are used where complete state-level data are unavailable
   for the same reference year.

8. Some state-level resource indicators are unavailable for selected
   federal territories. Missingness is handled within the analytical
   framework and is documented in the analysis output.

9. Scenario and demand-shock results are simulations designed to assess
   how risk may change if future tourism demand exceeds the baseline
   forecast.

============================================================
6. DATA AND REFRESH NOTES
============================================================

The submitted Dashboard.pbix is intended to be opened and explored
without requiring access to the original development computer.

If judges only wish to view and interact with the submitted dashboard,
no data refresh is required.

Supporting data files are included in the submission package where
permitted by the competition guidelines.

If a manual refresh is attempted, Power BI may request that the local
data-source paths be updated because the original analysis files were
stored on the development computer. This does not affect normal viewing
of the already submitted dashboard.

============================================================
7. SUBMISSION PACKAGE
============================================================

Recommended package structure:

Bumblebees_Datathon2026_Dashboard.zip
|
|-- Dashboard.pdf
|-- Dashboard.pbix
|-- Data.xlsx / Data.csv (where applicable and permitted)
|-- README.txt

============================================================
8. TEAM
============================================================

Team Name: Bumblebees

Project:
AI-Driven Tourism Intelligence and Early-Warning System
for Sustainable Tourism Planning in Malaysia

DOSM Datathon 2026
