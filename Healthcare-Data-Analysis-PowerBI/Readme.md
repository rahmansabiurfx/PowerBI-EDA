# Emergency Room Analytics Dashboard using Power BI

A comprehensive healthcare analytics project analyzing 9,216 emergency room visits to uncover patterns in patient demographics, department utilization, and service delivery efficiency.

# Problem Statement: Emergency Room Analytics Gap

## Challenge
The emergency department serves 9,000+ patients annually but operates without data visibility, causing inefficient resource allocation, unknown service patterns, and inability to optimize operations.

## Solution
Develop a Power BI dashboard to analyze patient demographics, department utilization, wait times, and temporal patterns for data-driven operational decisions.

## 📊 Dashboard Overview

This Power BI dashboard transforms raw healthcare data into actionable insights through interactive visualizations and real-time filtering capabilities.

![Excel](https://github.com/rahmansabiurfx/PowerBI-EDA/blob/main/Healthcare-Data-Analysis-PowerBI/Assets/dashboard.jpg)

---

## 🎯 Key Performance Indicators

### Patient Volume & Gender Distribution

The dashboard prominently displays total patient visits with a gender breakdown, showing nearly equal distribution between male and female patients. This KPI card provides immediate insight into overall ER utilization and gender equity in emergency services.

**Key Findings:**
- Total Visits: 9,216
- Male Patients: 4,705 (51.0%)
- Female Patients: 4,487 (49.0%)
- Average Wait Time: ~35 minutes (consistent across genders)

![Excel]([https://github.com/rahmansabiurfx/Excel-EDA/blob/main/Healthcare-Data-Analysis/Assets/stat1.PNG](https://github.com/rahmansabiurfx/PowerBI-EDA/blob/main/Healthcare-Data-Analysis-PowerBI/Assets/dashboard.jpg))
---

## 📈 Demographic Analysis

### Racial Distribution Chart

This pie chart reveals the diverse patient population served by the emergency department. The visualization uses graduated blue tones to clearly distinguish between racial categories while maintaining visual harmony.

**Distribution Breakdown:**
- White: 55.5% (5,106 patients) - Majority population
- African American: 27.9% (2,570 patients)
- Asian: 21.17% (1,950 patients)
- Two or More Races: 16.89% (1,556 patients)
- Other categories each below 12%

![Race Distribution Pie Chart](images/race_pie_chart.png)

### Age Group Composition

The age distribution analysis shows a balanced spread across adult populations with lower pediatric volumes, crucial for resource planning and specialized care provisions.

**Age Segmentation:**
- Adult (25.91%) & Senior (25.03%) - Combined 50%+ of visits
- Middle Aged: 24.8%
- Children: 12.88%
- Teen: 8.92%
- Infant: 2.39% (lowest utilization)

![Age Group Pie Chart](images/age_pie_chart.png)

---

## 🏥 Department Performance Analysis

### Weekday vs Weekend Utilization

This stacked bar chart provides critical insights into department-specific utilization patterns, revealing significant weekday concentration across all departments. The visualization enables quick identification of weekend service gaps.

**Key Patterns:**
- Renal Department: 84.88% weekday (highest concentration)
- General Practice: 72.39% weekday
- Most departments: 70-75% weekday utilization
- Weekend services consistently underutilized (15-33%)

![Weekday Weekend Chart](images/weekday_weekend_chart.png)

### Department Referral Matrix

The comprehensive matrix table shows department referrals broken down by age groups, enabling targeted service planning and resource allocation.

**Volume Leaders:**
1. General Practice: 1,840 total referrals
2. Orthopedics: 995 referrals
3. Physiotherapy: 276 referrals
4. Specialized departments: <250 referrals each

![Department Matrix](images/department_matrix.png)

---

## 🔍 Interactive Features

### Dynamic Filtering System

The dashboard includes powerful filtering capabilities that update all visualizations in real-time:

**Date Range Selector:**
- Covers April 2019 to October 2020
- Slider interface for intuitive date selection

![Date Filter](images/date_filter.png)

**Age Group Filter:**
- Dropdown menu with "All" option
- Instant cross-visual filtering
- Enables age-specific analysis

![Age Filter](images/age_filter.png)

---

## 💡 Key Insights & Recommendations

### 1. Weekend Optimization Opportunity
The consistent 70/30 weekday/weekend split across all departments suggests potential for:
- Weekend staffing reduction
- Weekday capacity expansion
- Alternative weekend service models

### 2. Demographic-Driven Service Design
With adults and seniors comprising 50%+ of visits:
- Develop age-specific care pathways
- Implement geriatric emergency protocols
- Create family-friendly pediatric areas

### 3. Department Load Balancing
High concentration in General Practice and Orthopedics indicates:
- Need for triage optimization
- Potential for specialized urgent care units
- Opportunity for preventive care programs

### 4. Equity Monitoring
Near-equal gender distribution and consistent wait times demonstrate:
- Equitable access to emergency services
- No gender-based service disparities
- Model for maintaining healthcare equity

---

## 🛠️ Technical Architecture

### Dashboard Specifications
- **Canvas Size**: 1200 x 900 pixels
- **Theme**: Dark background with blue accent palette
- **Layout**: Grid-based responsive design
- **Interactivity**: Full cross-filtering enabled

### Data Model Components
- Patient demographic dimensions
- Time intelligence for temporal analysis
- Department hierarchy for drill-down capability
- Calculated measures for dynamic KPIs

### Advanced Analytics Implementation
Created custom DAX measures to calculate:
- Dynamic average wait times by gender
- Weekday vs weekend percentage distributions
- Age group proportions with real-time filtering
- Department utilization rates
- Cross-dimensional patient counts

---

## 📋 Business Impact

This dashboard enables healthcare administrators to:

1. **Optimize Resource Allocation**
   - Data-driven staffing decisions
   - Department-specific capacity planning
   - Peak hour identification

2. **Improve Patient Experience**
   - Reduce wait times through pattern analysis
   - Enhance age-appropriate services
   - Monitor and maintain service equity

3. **Strategic Planning**
   - Evidence-based expansion decisions
   - Preventive care program development
   - Community health needs assessment

---

## 🎯 Conclusion

This Emergency Room Analytics Dashboard successfully transforms complex healthcare data into clear, actionable insights. By analyzing 9,216 patient visits across 18 months, the dashboard reveals critical patterns in patient demographics, department utilization, and service delivery efficiency.

The dashboard empowers administrators to spot the weekday-weekend split, identify overwhelmed departments, and verify equitable wait times across patient groups. What was once scattered data is now a practical tool for smarter staffing decisions and strategic planning. This project demonstrates how thoughtful analytics can directly improve both healthcare operations and patient experiences.
---

*This project demonstrates advanced Power BI skills applied to real-world healthcare challenges, showcasing the ability to transform complex data into actionable business intelligence.*
