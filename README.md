# Enhancing Road Safety in Chennai: Insights and Causes from ADAS Alerts Analysis

**Students:** Yash Jadhav, Rohan Gore,  Ayush Bhalerao  
**College Guide:** Ms. Kalyani Ghuge  
**Date of Submission:** 10th September 2023

---

## Abstract

This study delves into the analysis of alerts generated by the Level-2 Advanced Driver Assistance System (ADAS) installed in public buses in Chennai, India. It aims to uncover key insights and identify potential root causes contributing to road safety issues. The study encompasses a wide range of factors, from city planning to time-based events, and provides actionable recommendations not limited to Chennai but applicable to any city or road planning project. This report serves as a valuable resource for policymakers addressing complex road safety challenges.

---

## Introduction / Motivation

Chennai, with the highest number of road accident-related fatalities, underscores the critical road safety challenges in India. The deployment of Level-2 Advanced Driver Assistance Systems (ADAS) in public buses presents a crucial opportunity to address these concerns. This report conducts a comprehensive analysis of ADAS data to unravel alerts and their underlying causes, aiming to inform decision-making and formulate effective strategies for enhancing road safety in Chennai.

---

## Data Sources

1. ADAS dataset provided by Intel Unnati (Primary)
2. Secondary Source:
   - Ministry of Family and Health Welfare, Press Release by PIB Delhi, 27th Feb 2021 [2]
   - Indian Movie Theatre dataset [3]
3. Software used:
   - Kepler.gl
   - QGIS
   - Python- Pandas

---

## Analysis – Patterns and Insights

### 1. Congestion Hot-spots
Clusters of data reveal consistent warning alerts at "Roundabouts" and near "Highway Exits". High speeds on the national highway indicate issues with exit conditions. Identifying these areas allows for targeted road safety improvement efforts.

### 2. By Hour
Alerts peak during morning (6-8 AM) and evening (4-6 PM) rush hours, correlating with high traffic volumes, congested roads, and heightened driver stress. Recognizing this temporal pattern is crucial for devising specific road safety strategies.

### 3. Speed Range and Verification Map
- Lane departure warnings (cas_ldw) are more common at high speeds, indicating regular lane drifting on NH-32.
- Pedestrian warnings (cas_pcw) occur at lower speeds, concentrated on bypass and city roads.
- Forward collision alerts (cas_fcw) remain high at all speeds, suggesting a prevalent "Tailgating" driving style.

### 4. Day Wise Analysis
Alerts are predominant from Monday to Friday, aligning with typical workweek traffic patterns. Understanding these trends aids in implementing variable rules during these days.

### 5. Weekly Analysis
Alert frequency remains fairly constant but tends to reduce towards the end of the second month, reflecting changes in traffic flow and congestion over a two-month period.

### 6. Other Causes
Factors such as numerous railway stations and parallel railway paths contribute to congestion. Proximity to hospitals, theaters, parks, entertainment hubs, and industrial centers near highways further exacerbate the issue.

---

## Conclusion

This report provides a comprehensive analysis of ADAS alerts in Chennai, shedding light on critical insights and underlying causes affecting road safety. The findings serve as a foundational resource for policymakers addressing road safety challenges not only in Chennai but in any urban planning endeavor. By targeting congestion hot-spots, understanding temporal patterns, and addressing contributing factors, we can work towards creating safer roads and saving lives.

---

## References

1. Guzman, William & Young, Leslie & Peszynski, Konrad. (2018). Addressing the cause of the problem and not its symptom: Road congestion at Railway Stations.
2. [Press Release by PIB Delhi, 27th Feb 2021](https://pib.gov.in/PressReleasePage.aspx?PRID=1701407)
3. [Indian Movie Theatre dataset](https://github.com/HarshaDevulapalli/indian-movie-theatres#data)
