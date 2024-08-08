**Disease Prevalence and Risk Analysis**
![image](https://github.com/user-attachments/assets/38fbd249-3ca9-402e-809e-a8093b106164)



**Introduction:**

This project builds upon insights from my previous machine learning model, which you can view in my GitHub repository. In that project, cancer emerged as the most high-risk disease. However, this raises an important question: does high prevalence equate to high risk? Interestingly, some states with lower prevalence rates show a higher incidence rate, meaning the disease is increasing more rapidly in those areas, even though fewer people have it overall. Notably, these regions are where Asian Pacific Americans predominantly reside.

To explore these patterns further, I used Tableau to layer and visualize the data. By creating detailed basemaps, I could illustrate the geographic distribution of cancer prevalence and risk. Additional layers were added to highlight areas with high incidence rates, despite low prevalence. This layering approach allowed me to clearly see and analyze the differences, providing a deeper understanding of the underlying trends and helping to uncover critical insights for public health authorities.

**Data Source**

The CDC's Division of Population Health offers a standard set of 124 health indicators agreed upon by experts. These indicators help states, territories, and large cities to consistently gather and share data on chronic diseases, which is crucial for public health. Besides, the CDI website not only gives specific data for each state but also acts as a portal to more data and information resources.

https://catalog.data.gov/dataset/u-s-chronic-disease-indicators-cdi 

**Objectives**

Conduct exploratory data analysis (EDA) to clean and preprocess the dataset.
Calculate incidence rates to determine the frequency of new disease cases within specific populations.
Identify high-risk groups by comparing incidence rates across different demographics.
Visualize the relationship between disease prevalence and risk using Tableau.

**Methodology**

Data Cleaning and Preparation: Over 50% of the dataset consisted of duplicates and poorly named columns, which were cleaned and refined to ensure data quality.

Incidence Rate Calculation: Merged state population data with disease data to calculate incidence rates using VLOOKUP in Excel. Developed a formula to categorize data by disease, year, and area to count new cases.

Risk Classification: Categorized each observation as low risk or high risk based on whether it fell below or above the average incidence rate for each disease.

**Visualization in Tableau:**

Created heatmaps to visualize high-risk groups by race and disease.
Developed basemaps to illustrate the geographic distribution of cancer prevalence and risk among Asian Pacific Islanders (APIO).
Highlighted areas with low prevalence but high risk, revealing critical insights for public health authorities.
Key Findings
The analysis revealed that regions with lower prevalence rates, such as the northeast, Alaska, New Mexico, and Hawaii, exhibited higher risk levels for cancer among APIO populations. These insights emphasize the importance of robust metrics for public health practice and underscore the need for targeted healthcare initiatives in these areas.

**Conclusion**

This project demonstrates the value of combining epidemiological metrics with data visualization tools like Tableau to uncover critical public health insights. By understanding the distinction between disease prevalence and risk, public health authorities can better allocate resources and develop targeted interventions to improve healthcare outcomes.
