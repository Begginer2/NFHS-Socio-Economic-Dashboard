# 📊 Empowering India: A Data-Driven Analysis (NFHS-4 vs. NFHS-5)

## 📋 Project Overview:

This project serves as a Decision-Support System designed to bridge the information gap in India’s public health and socio-economic sectors. By transforming raw survey data from the National Data and Analytics Platform (NDAP) into interactive visualizations, it identifies critical disparities between rural and urban India.

The analysis specifically tracks the transition between NFHS-4 (2015-16) and NFHS-5 (2019-21) to provide policy makers with a roadmap for targeted infrastructure investment.

## 🚀 Key Dashboard Themes
The analysis is divided into three primary "Digital Command Centers":


* Economic & Digital Empowerment: Visualizing the **9.41% gender literacy gap** and its direct impact on digital and financial inclusion across India.


* Health & Survival: Identifying regional healthcare disparities by mapping high-priority mortality zones based on **infant mortality rates**.


* Quality of Living Standards: Highlighting the Rural-Urban infrastructure divide in institutional births and basic sanitation facilities.

  ## 🛠️ System Development Approach
The project follows a professional data lifecycle:


* Data Acquisition: Secondary data was extracted from the National Data and Analytics Platform (NDAP).


* Data Preprocessing: Used Power BI Power Query Editor to remove null values, handle outliers, and standardize state names.


* Data Modeling: Implementation of a Star Schema to establish relationships between different survey years.


* UI/UX Design: Applied consistent color palettes and intuitive navigation buttons to ensure the dashboard is accessible to all users.

 ## 🧠 Algorithm & Logic
This project utilizes DAX (Data Analysis Expressions) and logical algorithms to generate insights:


* Gap Analysis Formula: Average(Men_Literacy) - Average(Women_Literacy).


* Risk Categorization : If the Infant_Mortality_Rate > National Median, the state is flagged as "High Risk"; otherwise, it is labeled "Low/Stable Risk".


* Dynamic Interaction: Deployed slicers and cross-highlighting to allow real-time filtering by Residence Type and Survey Version.

## 📂 Repository Structure
* /Dashboard: The .pbix source file for the Power BI dashboard.

* /Data: The cleaned and normalized NFHS_5.csv dataset.

* /Presentation: The final Capstone Project presentation (.pptx and .pdf).

 ## 🔮 Future Scope

* Real-time Integration: Connecting to live government APIs for instant data updates.


* Predictive Analytics: Using Machine Learning to forecast future health trends.


* Granular Mapping: Expanding data from state-level to district-level for more localized policy impact.


  ## 🔗 References


* Website:  https://ndap.niti.gov.in/


* Data Source: https://ndap.niti.gov.in/dataset/national-family-health-survey
  
