# **UNICEF DATASET: Analysis of Maternal Mortality Ratios (MMR) Across Regions from 2000 to 2020**

Author: Kellie Leonard 

**Abstract:**
This report aims to examine and compare the maternal mortality ratios (MMR) per 100,000 women across different world regions from 2000 to 2020, utilising a UNICEF dataset. Using Python, with libraries such as pandas, matplotlib, and seaborn, we analyse trends in maternal mortality and explore regional disparities. Visualisations and statistical analysis reveal patterns in MMR data, shedding light on the factors contributing to high and low maternal mortality in various regions.
 
**1. Introduction**
Maternal mortality is a critical indicator of a population's health and development status. The maternal mortality ratio (MMR), defined as the number of maternal deaths per 100,000 live births, varies widely across regions. This report explores the trends in maternal mortality from 2000 to 2020 across different regions, leveraging Python’s data analysis and visualisation capabilities. The goal is to identify regions where maternal mortality has improved, stagnated, or worsened and to discuss potential contributing factors.

**2. Data Overview**
The dataset consists of maternal mortality ratios for five years (2000, 2005, 2010, 2015, and 2020) across various world regions. The columns are structured as follows:
•	Region: The geographical region.
•	2000, 2005, 2010, 2015, 2020: Maternal mortality ratios (MMR) per 100,000 women for each respective year.

**3. Data Cleaning and Preparation**
Using Python’s pandas library, the dataset was cleaned to ensure consistency in naming conventions and that all missing or erroneous data were handled. The dataset was then structured to enable easy comparison across regions and years.


**4. Exploratory Data Analysis (EDA)**
Using Seaborn and Matplotlib, various visualisations were created to compare the maternal mortality ratios across regions over five-year intervals. The following sections outline key trends and insights.

**4.1 General Trends Over Time**
A line plot was generated to show the changes in maternal mortality across the different regions over time. The plot clearly highlights significant improvements in certain regions while others have stagnated or worsened.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/a88f608f-e0ee-446b-8629-9f143c3359fa" />

 
**4.2 Regional Comparison in 2020**
A bar plot was used to compare maternal mortality ratios across different regions in 2020. This visualisation highlights which regions have made the most progress and which regions are still struggling with high maternal mortality.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/b1dc2e55-0237-4ced-8895-54e840ea5cc6" />


**4.3 Heatmap of MMR Across Regions and Years**
A heatmap was created to visualise the variation in maternal mortality ratios across both time and region, offering an intuitive way to see changes and disparities.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/4e0fc3c0-9e90-4101-acc6-8f81fbd8e9c7" />


**5. Analysis and Discussion**
From the visualisations, several key observations can be made:

**5.1 High Mortality in Low-Income Regions**
A concerning trend from the dataset is the rise in maternal mortality in West and Central Africa between 2000 and 2020, contrary to the general global decline. 

Several factors contribute to this increase:

•	Healthcare System Strain: Limited access to skilled birth attendants, inadequate medical resources, and weak healthcare infrastructure in rural areas continue to pose significant challenges. Despite efforts to improve care, these regions still struggle with high maternal mortality due to insufficient medical attention during childbirth.

•	Political Instability and Conflict: Ongoing conflicts in countries such as the Central African Republic, Democratic Republic of the Congo, and Mali have disrupted healthcare services and led to the displacement of populations, further exacerbating the difficulty of providing safe maternal healthcare.

•	High Fertility Rates and Family Planning Barriers: With some of the highest fertility rates in the world, many women in this region face a greater risk during pregnancy and childbirth. Lack of access to family planning services and reproductive health education means many women experience multiple pregnancies, which increases the chances of complications.

•	COVID-19's Negative Impact: The pandemic severely impacted healthcare systems in West and Central Africa, leading to a reduction in available medical services, limited access to hospitals, and increased poverty. This disruption in care has contributed to higher maternal mortality during the period.

These factors underscore the need for urgent and targeted interventions to address both healthcare deficiencies and socio-political barriers in order to improve maternal health outcomes in West and Central Africa.

**5.2 Significant Improvement in South Asia**
South Asia has made remarkable progress in reducing maternal mortality between 2000 and 2020. The region, which includes countries like India, Bangladesh, and Sri Lanka, has seen a significant decline in maternal deaths due to improved healthcare access and government initiatives.

•	India: India's maternal mortality ratio (MMR) has decreased by over 60%, from 374 per 100,000 women in 2000 to around 130 in 2020. This improvement can be attributed to increased access to prenatal care, skilled birth attendants, and improved emergency obstetric services, especially in rural areas.

•	Bangladesh: Bangladesh has made a similarly impressive reduction, with MMR dropping from 574 in 2000 to approximately 173 per 100,000 in 2020, a decline of around 70%. This progress is largely due to community health programs, such as the use of community-based health workers and improvements in access to family planning services.

•	Sri Lanka: Sri Lanka, already a leader in maternal health in South Asia, has seen its MMR drop to under 30 per 100,000, a substantial decrease from 73 in 2000. The country’s success is attributed to its strong public health system, universal healthcare access, and high levels of maternal health education.

The improvements across South Asia reflect the positive impacts of targeted maternal health initiatives, government policies, and international support. Increased access to skilled birth attendants, better family planning services, and improved healthcare infrastructure have played key roles in reducing maternal mortality in the region. However, challenges remain in addressing disparities in rural and underserved areas.

**5.3 Stagnation in Certain Regions**
While many regions have made impressive strides, some, particularly in the Middle East and Eastern Europe, have shown stagnation or only slight improvements. Countries in these regions, such as Russia and several Middle Eastern nations, have seen little to no change in their maternal mortality rates from 2000 to 2020.

Possible reasons for this stagnation include:

•	Healthcare System Challenges: In some Eastern European countries, healthcare systems are underfunded, and many women lack access to high-quality healthcare services. Additionally, there may be gaps in training for healthcare workers, particularly in rural or remote areas where women may not have immediate access to skilled birth attendants.

•	Political and Economic Instability: Economic struggles or political unrest in certain Middle Eastern and Eastern European countries may have diverted attention and resources away from maternal health initiatives. In some instances, international sanctions, military conflict, or economic downturns have led to a reduction in healthcare investment.

•	Cultural Barriers: In some Middle Eastern nations, cultural norms and practices related to childbirth may impact women’s access to healthcare services. In these regions, a preference for home births or reluctance to seek medical assistance when complications arise can contribute to higher maternal mortality.

In particular, Eastern Europe has faced a number of economic challenges that have hindered the development of adequate healthcare infrastructure despite some countries’ efforts to address the problem.

**5.4 Global Trends and Observations**
From a global perspective, it is evident that maternal mortality has declined significantly, but the improvements have been uneven. While the data shows a global decrease in MMR, the variation between regions is striking, underscoring the need for region-specific approaches in addressing maternal mortality.

•	High-Income vs. Low-Income Disparities: High-income countries, such as those in Western Europe and North America, continue to exhibit very low MMRs, generally below 20 per 100,000 women. These countries benefit from well-established healthcare systems, high levels of healthcare access, and robust maternal health policies. In contrast, many low-income countries, especially in Africa and parts of Asia, continue to experience high maternal mortality rates, demonstrating the disparity in healthcare availability and quality.

•	Effectiveness of International Aid: International organisations, such as the World Health Organization (WHO) and UNICEF, have played a critical role in providing funding and resources to improve maternal health in developing countries. Programs aimed at increasing the number of skilled birth attendants, improving prenatal care, and educating women about safe childbirth practices have had a measurable impact in reducing maternal deaths. However, there is still much work to be done to ensure that every woman, regardless of where she lives, has access to safe and affordable maternal care.

•	Sociocultural Factors: In some regions, social and cultural factors still play a significant role in maternal health outcomes. Gender inequality, limited education, and traditional practices surrounding childbirth can lead to delays in seeking care or refusal of medical intervention during complications. Addressing these cultural barriers is essential for improving maternal mortality outcomes.

**5.5 Future Outlook**
Given the data trends, it is clear that the global fight against maternal mortality is far from over. Future efforts must focus on the following areas:

•	Increasing Access to Healthcare: Improving healthcare infrastructure and access to skilled birth attendants in low-income regions is critical to reducing maternal deaths.

•	Strengthening Health Systems: In regions like Sub-Saharan Africa, strengthening the healthcare system, especially in rural areas, will be crucial. This includes ensuring a steady supply of essential medications, medical equipment, and training for healthcare professionals.

•	Promoting Maternal Education and Family Planning: Educational campaigns emphasising the importance of prenatal care, family planning, and safe childbirth should be expanded, particularly in regions with high MMRs.

•	Policy and Advocacy: Governments must prioritise maternal health in their policy agendas and increase funding for maternal healthcare. In addition, international organisations should continue their efforts to provide aid and resources to countries with high maternal mortality rates.

**6. Conclusion**

The analysis of maternal mortality ratios across different regions reveals significant disparities in healthcare access, infrastructure, and education. Regions such as Sub-Saharan Africa still face critical challenges, while countries in Asia and Latin America show considerable improvement. The global decline in maternal mortality highlights the impact of concerted efforts to improve maternal health but also underscores the need for targeted interventions in regions with high mortality rates.
This analysis has demonstrated how Python’s data analysis libraries can be leveraged to explore and visualise important health data. By using pandas for data wrangling and seaborn/matplotlib for visualisation, we are able to extract meaningful insights that could inform policy decisions and global health strategies.

