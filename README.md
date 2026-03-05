# NHS Referral to Treatment (RTT) Operational Pressure Analysis – 2025
## Executive Summary
This project develops an interpretable operational pressure model using NHS England Referral to Treatment (RTT) waiting list statistics.

Using monthly national data from April to December 2025, the analysis evaluates waiting list dynamics, breach patterns beyond the 18-week constitutional standard, and long-wait concentrations exceeding 52 weeks.

A composite pressure score is introduced to provide a structured indicator of system strain across time.

Rather than treating NHS statistics as descriptive reporting, the project demonstrates how national operational datasets can support decision-support frameworks for capacity prioritisation, backlog management, and escalation planning within public healthcare systems.
## Project Overview
This project analyses NHS England Referral to Treatment (RTT) incomplete pathway data from April 2025 to December 2025.

The objective is to transform publicly available national waiting list data into structured decision-support insights for operational pressure management.

Rather than focusing on descriptive statistics alone, this project develops an interpretable pressure model and escalation framework to support NHS operational strategy.

---

## Data Source

* NHS England RTT Incomplete Pathways Full Extracts  
* Monthly data: April 2025 – December 2025  
* Publicly available provider-level aggregated data  

All analysis is based exclusively on publicly published statistics.

---

## Key Metrics Analysed

* Total Waiting List Size  
* Percentage Waiting >18 Weeks  
* Percentage Waiting >52 Weeks  
* Month-on-Month Change  
* Composite Pressure Score (Normalised Indicator)  

## Analytical Methodology
The analysis applies structured exploratory analysis to monthly RTT incomplete pathway datasets.

The workflow includes:

* Aggregation of provider-level statistics to evaluate national waiting list behaviour  
* Calculation of percentage breaches beyond the 18-week constitutional standard  
* Identification of extreme long-wait concentrations exceeding 52 weeks  
* Month-to-month trend evaluation to detect operational pressure changes  
* Construction of a composite pressure score combining backlog size and breach severity

The composite indicator is normalised to allow comparison across months, enabling clearer interpretation of operational stress levels over time.

## Key Findings (Apr–Dec 2025)

* National waiting list declined gradually from April to November 2025  
* >52 week waits reduced significantly toward late 2025  
* April 2025 represented peak operational pressure  
* November 2025 represented lowest pressure period in dataset  
* Certain surgical specialties show sustained long-wait concentration  

## Operational Decision Insights
The analysis highlights several operational patterns within the RTT system during 2025.

First, overall waiting list pressure gradually improved between April and November 2025, suggesting the impact of backlog recovery initiatives and increased treatment capacity.

Second, the proportion of patients waiting beyond 52 weeks declined significantly, indicating targeted efforts to eliminate extreme long waits.

However, specialty-level analysis reveals that certain surgical pathways continue to accumulate long-wait patients. These concentrated bottlenecks suggest that capacity constraints are not evenly distributed across the system.

From an operational perspective, this indicates the need for targeted specialty-level interventions rather than uniform national responses.
## Visual Evidence

### National Waiting List Trend
![Total Waiting List](images/01_total_waiting_by_month.png)

### Pressure Score Trend
![Pressure Score](images/05_pressure_score_trend.png)

### High-Risk Specialties (Heatmap)
![Specialty Risk Heatmap](images/07_specialty_risk_heatmap.png)

---

## Decision-Support Framework

This project introduces:

* Pressure Score ranking model  
* Operational escalation tiers  
* Monitoring thresholds  
* Governance-aware automation boundaries  

The focus is structured decision support — not automated decision execution.
## Operational Escalation Model
Based on the composite pressure score and breach thresholds, an operational escalation structure can be defined for RTT waiting list management.

Level 1 — Stability Monitoring  
Waiting list pressure remains within acceptable limits. Operational teams maintain routine monitoring and capacity planning while preserving buffer capacity.

Level 2 — Managed Pressure  
Where 18-week breaches increase or backlog growth accelerates, operational review is triggered. Actions may include targeted backlog clearance initiatives and pathway efficiency improvements.

Level 3 — Critical Pressure  
Where long-wait patients (>52 weeks) exceed acceptable thresholds, system-level intervention is required. Potential responses include temporary capacity redistribution, cross-provider collaboration, or focused backlog recovery programmes.

This framework illustrates how operational metrics can inform structured escalation decisions rather than passive monitoring.
## Strategic Relevance
Although based on NHS England RTT statistics, the analytical framework developed in this project is transferable to broader operational environments where demand, backlog, and capacity constraints must be managed simultaneously.

The pressure scoring approach demonstrates how aggregated operational data can support structured prioritisation and escalation planning across complex systems.

The methodology highlights the potential for decision-intelligence frameworks to complement traditional reporting dashboards by translating analytical signals into operational strategy.
## Repository Structure

/notebooks → Full analytical workflow  
/images → Generated charts and visual outputs  

## Limitations

This analysis is based on publicly available aggregated statistics rather than patient-level data.

As a result:

* Provider-level variation cannot be explored in depth  
* Individual treatment pathways cannot be analysed  
* Causal inference regarding operational interventions is limited

The purpose of the project is therefore decision-support interpretation rather than predictive modelling or operational forecasting.

## Analytical Methodology

The analysis applies structured exploratory analysis to publicly available NHS England RTT incomplete pathway datasets.

The workflow includes:

* Aggregation of monthly national waiting list statistics  
* Measurement of breach levels beyond the 18-week constitutional standard  
* Identification of extreme long-wait concentrations exceeding 52 weeks  
* Month-to-month trend evaluation to detect operational pressure shifts  
* Construction of a composite pressure score combining backlog scale and breach severity

The pressure score is normalised to allow consistent comparison of operational strain across different time periods.

## Governance & Analytical Boundaries

* No patient-level identifiable data used  
* No predictive modelling deployed  
* No live operational systems connected  
* Designed for decision-support context only  

The analysis prioritises interpretability, auditability, and responsible automation principles.
