## 📌 Introduction
School shootings have been a persistent and tragic issue in the United States, affecting students, families, and communities nationwide. As someone who attended school in the U.S., this issue hits close to home. The goal of this project is to analyze historical data on school shootings from 1990 to 2024, uncovering trends, severity, and geographic patterns. Through data analysis, we can contribute to informed discussions that may help shape policies aimed at improving school safety.

## 🎯 Why This Project?
School violence is a pressing issue that demands a data-driven approach to understanding its root causes. By analyzing this dataset, we can:

✔️ Identify key trends and patterns over time.  
✔️ Highlight geographic areas most affected.  
✔️ Examine the severity of incidents and potential contributing factors.  
✔️ Provide insights that could inform policy changes and preventive measures.

## 📌 Table of Contents   
- [📊 Day 1: Data Cleaning and Handling Missing Information](#-day-1-data-cleaning-and-handling-missing-information)  
- [📊 Day 2: Data Analysis & Summary](#-day-2-data-analysis--summary)  
- [🎨 Day 3: Visualizing Data with Tableau](#-day-3-visualizing-data-with-tableau)  
- [📝 Day 4: Report Writing & Final Insights](#-day-4-report-writing--final-insights)  
  
---

## 📊 Day 1: Data Cleaning and Handling Missing Information
**Dataset Source:** [School Shootings in the USA (1990-2024)](https://www.kaggle.com/datasets/ecodan/school-shootings-us-1990present?select=pah_wikp_combo.csv)  

### 🔍 Overview
The dataset includes details such as dates, locations, fatalities, and descriptions of school shootings. Before analysis, the data needed cleaning to ensure accuracy and consistency.

### 🔹 Original Dataset Attributes
- **Date** – Date of the incident.
- **City, State** – Location details.
- **AreaType** – Classification (Urban, Suburban, Rural).
- **School** – Type of school (High School, Middle School, etc.).
- **Fatalities, Wounded** – Number of victims.
- **Dupe** – Duplicate rows.
- **Source** – Data source.
- **Desc** – Incident description.

### 🔹 Transformations & Enhancements
- Standardized date formats and removed duplicates.
- Added **Month** & **Day of Week** fields.
- Categorized severity levels: **Low, Moderate, High**.
- Grouped data by **region** (Northeast, South, Midwest, West).

[Back to Top](#-project-contents)
---
## 📊 Day 2: Data Analysis & Summary
The cleaned dataset will be analyzed to uncover:
- Trends over time (increase/decrease in incidents).
- Severity of shootings across different locations.
- Correlation between urbanization levels and shooting frequency.

This report summarizes the key findings from an analysis of school shooting data in the United States between 1990 and 2024. Six charts were used to explore trends, patterns, and contributing factors related to these incidents.

1. Trends Over Time: The annual number of school shootings has increased dramatically in recent years, particularly since 2018. While fluctuations existed in the period from 1990 to the mid-2010s, the current decade shows a significant and concerning upward trend. This highlights the escalating nature of the crisis and the urgent need for effective interventions.
![Number of School Shootings (1990-2024) by Year](https://github.com/user-attachments/assets/26b18c0c-749e-4966-8902-a5b27d105119)
￼
2. School Type: High schools are disproportionately affected by school shootings, accounting for the largest share of incidents. Colleges and universities also experience a significant number of shootings, though considerably fewer. Middle and elementary schools, while less frequent, are not immune, demonstrating the vulnerability of students across all age groups.
![Number of School Shootings by School Type (1990-2024)](https://github.com/user-attachments/assets/6222e6fd-d240-4b30-beb3-1ee7f56a48e7)
￼
3. Timing of Incidents: Analysis of monthly patterns reveals potential seasonal influences. January and February, along with September and October, show a higher concentration of incidents. June and July exhibit the lowest number of shootings, likely due to the fact that school is typically not in session during these months, suggesting a strong correlation with the academic calendar.
![Number of Shootings for each Month (1990-2024)](https://github.com/user-attachments/assets/870e556e-184d-4f41-90af-36d87adf5071)

4. Geographic Distribution: The geographic distribution of school shootings is uneven, with Texas having the highest number of incidents, followed by California. Several other states also experience a notable number of shootings, while many others have comparatively few. This suggests that state-specific factors, such as gun laws, mental health resources, and socioeconomic conditions, may play a role.
![Number of School Shootings (1990-2024) by State](https://github.com/user-attachments/assets/70d13bf1-75b6-407d-ac88-41cac7fe3a62)

5. Regional Analysis: When considering the number of schools in each region, the South has the highest number of schools. Further analysis is needed to calculate and compare the rate of school shootings per school in each region to account for this variation in school density. This rate calculation is crucial for a more nuanced understanding of regional disparities.
![Number of Schools per Region (1990-2024)](https://github.com/user-attachments/assets/f25c8648-1348-49d1-a66c-dcdb0ca05a26)

6. Community Context: The majority of school shootings occur in urban areas, followed by suburban and then rural settings. However, it's important to consider population density and the number of schools in each area type when interpreting these findings. Further analysis is needed to understand the specific factors contributing to these incidents in different community contexts.
![Number of Shootings per Area Type (1990-2024)](https://github.com/user-attachments/assets/f47d1c09-3451-4812-b731-44040ed769ca)

This analysis reveals several critical trends and patterns in school shootings. The increasing frequency of incidents, the vulnerability of high schools, the potential seasonal influences, and the geographic disparities underscore the complexity of the issue and the need for multifaceted prevention strategies. Further research, particularly calculating rates of incidents per school/population and exploring contributing factors in different contexts, is crucial for developing effective interventions and informing policy discussions.

[Back to Top](#-project-contents)

---

## 🎨 Day 3: Visualizing Data with Tableau  
Today, I used **Tableau** to create a dashboard that visualizes school shootings in the U.S. from **1990 to 2024**. Key insights include:  

📊 **Yearly Trends** – Analyzing how incidents have fluctuated over time.  
🗺️ **Geographic Distribution** – Mapping where school shootings have occurred across the country.  
🏫 **School Type Analysis** – Comparing incidents across elementary, middle, high schools, and universities.  

🔗 **View the Dashboard:** [Tableau Public – School Shootings in USA (1990-2024)](https://public.tableau.com/app/profile/yoada.zeleke/viz/SchoolShootingsinUSA1990-2024/Dashboard1)  

![School Shootings USA in 1990-2024](https://github.com/user-attachments/assets/7ca6ebcd-e756-4719-bc5d-3b52f602e97b)  

[Back to Top](#-project-contents)

---

## 📝 **Day 4: Report Writing & Final Insights**  
Today, I analyzed key findings from the **Tableau dashboard** and compiled a **mini report** summarizing insights on school shootings in the U.S. (1990-2024).  

🔗 **View the Interactive Dashboard:** [Tableau Public – School Shootings in USA (1990-2024)](https://public.tableau.com/app/profile/yoada.zeleke/viz/SchoolShootingsinUSA1990-2024/Dashboard1)  

### 🔍 **Key Insights:**  
- **📈 Yearly Trends:** There has been a **notable increase in incidents over the decades,** with **2018 & 2022** marking the highest occurrences.  
- **🗺️ Geographic Hotspots:** **California, Texas, and Florida** have reported the most incidents, with a concentration in **urban areas.**  
- **🏫 School Type Analysis:** **High schools** are the most commonly affected, but **college/university** shootings tend to result in **higher fatalities.**  
- **🧠 Mental Health & Contributing Factors:**  
  - Many shooters had **documented histories of mental illness** or behavioral concerns.  
  - **Lack of early intervention, social isolation, and access to firearms** are recurring themes.  
  - The **role of bullying, social rejection, and extremist ideologies** has been observed in multiple cases.  

### 💔 **Deadliest School Shootings (1990-2024):**  
These tragic events had the highest number of casualties and lasting impacts:  

1. **Virginia Tech Massacre (2007)** – 32 killed, 17 injured.  
2. **Sandy Hook Elementary School (2012)** – 26 killed, 2 injured.  
3. **Robb Elementary School, Uvalde, TX (2022)** – 21 killed, 17 injured.  
4. **Stoneman Douglas High School, Parkland, FL (2018)** – 17 killed, 17 injured.  
5. **Columbine High School, CO (1999)** – 13 killed, 24 injured.  
6. **Red Lake Senior High School, MN (2005)** – 9 killed, 5 injured.  
7. **Santa Fe High School, TX (2018)** – 10 killed, 13 injured.  

📌 **Read the Full Report:** [GitHub Report (Coming Soon)]  

📊 **Data Source:** [Kaggle Dataset – School Shootings (1990-Present)](https://www.kaggle.com/datasets/ecodan/school-shootings-us-1990present?select=pah_wikp_combo.csv)  

[Back to Top](#-project-contents)

---

## 📌 Conclusion
This analysis highlights the alarming increase in school shootings, particularly in high schools and urban areas. The geographic disparities and seasonal patterns suggest that multiple factors—legislation, mental health resources, and community conditions—may influence these trends. Further research is needed to explore these correlations in depth.

📢 *Stay tuned for updates on upcoming analyses!*  
📩 **Want to discuss this project or collaborate? Reach out via [LinkedIn](https://www.linkedin.com/in/yoadabzeleke/)!**
