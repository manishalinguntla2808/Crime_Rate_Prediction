
# 🔐 Crime Rate Prediction by Area

This project aims to **predict crime rates in Chicago's community areas** based on historical crime data, demographic information, and school safety data.

---

## 🎯 Project Objectives

- Analyze the relationship between crime, demographics, and educational infrastructure.
- Predict crime rates for different community areas using machine learning.
- Create interactive visualizations to display patterns and trends.
- Deliver actionable insights that could help in urban planning and public safety strategies.

---

## 🧰 Tools & Technologies

- **Python** (Pandas, Matplotlib)
- **Jupyter Notebooks**
- **Tableau** (for interactive visualizations)
- **Git/GitHub** (for version control)

---

## 📁 Project Structure

```
📦 CrimeRatePrediction/
├── 📁 data           # Raw datasets (CSV files)
├── 📁 notebooks      # Jupyter Notebooks with analysis and modeling
├── 📁 tableau        # Tableau dashboards and screenshots
├── 📁 outputs        # Processed data and model results
└── README.md         # Project documentation
```

---

## 🗂️ Datasets Used

| Dataset | Source | Description |
|--------|--------|-------------|
| `ChicagoCrimeData.csv` | Chicago Data Portal | Includes type of crime, location, date, and community area |
| `CensusData.csv` | U.S. Census Bureau | Population, income, education levels per community area |
| `ChicagoPublicSchools.csv` | Chicago Open Data | School names, types, locations, and safety ratings |

---

## 📊 Tableau Dashboard

Interactive dashboards built in Tableau include:

- [Chicago Crime Rate Count](https://public.tableau.com/app/profile/manisha.linguntla/viz/ChicagoCrimeRateCount/CrimeCount)
- [Community area with income < 11000](https://public.tableau.com/app/profile/manisha.linguntla/viz/Communityareawithincome11000/Communityareawithincome11000)
- [Crimes involving Minors](https://public.tableau.com/app/profile/manisha.linguntla/viz/Crimesinvolvngminors/CrimesinvolvingMinors)
- [Kidnapping crimes involving child](https://public.tableau.com/app/profile/manisha.linguntla/viz/Kidnappingcrimesinvolvingchild/Kidnappingcrimesinvolvingchild)
- [Crimes reported at School](https://public.tableau.com/app/profile/manisha.linguntla/viz/Crimesreportedatschool/Crimesreportedatschool)
- [Average Safety Score by school type](https://public.tableau.com/app/profile/manisha.linguntla/viz/Averagesafetyscorebyschooltype/Averagesafetyscorebyschooltype)
- [Top 5 % households below poverty](https://public.tableau.com/app/profile/manisha.linguntla/viz/Top5householdsbelowpoverty/Top5householdsbelowpoverty)
- [Community Area Number with highest crime rate](https://public.tableau.com/app/profile/manisha.linguntla/viz/Areanumberwithhighestcrimerate/Areanumberwithhighestcrimerate)
- [Community Area with highest Harship index](https://public.tableau.com/app/profile/manisha.linguntla/viz/Areawithhighestharshipindex/Areawithhighesthardshipindex)
- [Community Area with highest crime rate](https://public.tableau.com/app/profile/manisha.linguntla/viz/Areawithhighestcrimerate/Areawithhighestcrimerate)
- [Chicago Crime Rate Dashboard](https://public.tableau.com/app/profile/manisha.linguntla/viz/ChicagoCrimeratedashboard/ChicagoCrimeratedashboard)
- **[Tableau Story Board](https://public.tableau.com/app/profile/manisha.linguntla/viz/ChicagoCrimeratestoryboard/ChicagoCrimerateStoryboard)
---

## 🔍 Key Questions & Findings

### Problem 1: Total number of crimes recorded in the CRIME table
- **Finding**: Total number of crimes recorded was **533**.

### Problem 2: Community areas with per capita income less than $11,000

| COMMUNITY AREA | NUMBER | PER CAPITA INCOME |
|----------------|--------|-------------------|
| West Garfield Park | 26 | 10,934 |
| South Lawndale     | 30 | 10,402 |
| Fuller Park        | 37 | 10,432 |
| Riverdale          | 54 | 8,201 |

### Problem 3: Case numbers for crimes involving minors (excluding children)
- **Finding**: Found **2 case numbers** involving minors:  
  `['HL266884', 'HK238408']`

### Problem 4: Kidnapping crimes involving a child

| Case Number | Primary Type | Description |
|-------------|--------------|-------------|
| HN144152    | KIDNAPPING   | CHILD ABDUCTION/STRANGER |

### Problem 5: Types of crimes reported at schools
- **Finding**: 7 unique types of crimes at schools:
  - Assault
  - Battery
  - Criminal Damage
  - Criminal Trespass
  - Narcotics
  - Public Peace Violation
  - Theft

### Problem 6: Average safety score by school type

| School Type | Avg Safety Score |
|-------------|------------------|
| ES (Elementary School) | 49.52 |
| HS (High School)        | 49.62 |
| MS (Middle School)      | 48.00 |

### Problem 7: Top 5 community areas with highest % households below poverty line

| COMMUNITY AREA | NUMBER | % BELOW POVERTY |
|----------------|--------|-----------------|
| Riverdale       | 54     | 56.5% |
| Fuller Park     | 37     | 51.2% |
| Englewood       | 68     | 46.6% |
| North Lawndale  | 29     | 43.1% |
| East Garfield Park | 27 | 42.4% |

### Problem 8: Most crime-prone community area (by number only)
- **Finding**: Community area number **25** (Austin).

### Problem 9: Community area with highest hardship index
- **Finding**: **Riverdale** (Area 53) with a hardship index of **98.0**.

### Problem 10: Community area with the most number of crimes
- **Finding**: **Austin** had the highest number of reported crimes.

---

## 📌 Conclusion

This project demonstrates how combining **crime records**, **demographic data**, and **educational statistics** can uncover meaningful patterns that help understand and predict criminal behavior in urban environments.

### Key Takeaways:

- **Austin** is the most crime-prone community area.
- **Riverdale** not only has the highest hardship index but also the highest poverty levels.
- **School safety scores** and **income levels** show a negative correlation with crime rates — communities with better schools and higher income levels tend to have lower crime.
- Predictive modeling and visual dashboards can assist law enforcement and policymakers in targeting high-risk areas more efficiently.
