# Visual Analysis of Health Factors in Diabetes

## Abstract

This study delves into visual analysis of the ShanghaiT1DM and ShanghaiT2DM datasets, aiming to unveil correlations and insights into various health factors among individuals with diabetes. By addressing key questions regarding health factors, diabetes-related complications, and gender-specific risks, the research endeavors to provide comprehensive visual insights crucial for improved diabetes management and overall health outcomes. The datasets, publicly accessible and unique in capturing real-life data from patients diagnosed with Type 1 and Type 2 diabetes mellitus, offer a rich resource for diabetes research. Detailed compositions of the datasets, encompassing clinical characteristics, laboratory measurements, medications, and dietary information, facilitate robust data analysis. Leveraging data visualization techniques, the study not only enhances understanding but also equips professionals with the skills necessary for handling complex data analyses in diabetes management, contributing to better healthcare practices and outcomes.

![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/main/README_image.png)


## Project Overview

This study aims to visually analyze the ShanghaiT1DM and ShanghaiT2DM datasets to uncover correlations and insights regarding various health factors in individuals with diabetes. Through visualization and data correlation, the research addresses the following key questions:

1. **Understanding Health Factors in Diabetes**
   - How do weight, blood sugar levels, age, cholesterol, and gender interrelate in individuals with diabetes, and how can these correlations inform strategies for maintaining overall health?

2. **Diabetes-Related Health Connections**
   - What are the specific connections between blood sugar levels and prevalent diabetes-related complications such as eye, nerve, and kidney problems, and how can these visualized connections guide strategies for mitigating associated risks and promoting well-being?

3. **Gender, Heart Risks, and Blood Sugar**
   - Do men and women with diabetes face differing heart risks based on blood sugar levels, and how can visualized correlations aid in developing tailored heart health management strategies for specific gender-related risks in the context of diabetes?

By addressing these questions, the study provides comprehensive visual insights into the interplay of various health factors in individuals with diabetes, with the  goal of contributing to improved diabetes management and overall health outcomes.

## Overview of ShanghaiT1DM and ShanghaiT2DM Datasets

The ShanghaiT1DM and ShanghaiT2DM datasets, pivotal for diabetes research, are publicly accessible and specifically designed to foster advancements in diabetes management technologies and data-driven models [8][10][12]. Originating from Shanghai, China, these datasets provide a comprehensive view of diabetes through real-life data from patients diagnosed with Type 1 and Type 2 diabetes mellitus [8][10][12].

### Dataset Composition and Details

Dataset composition refers to what's inside a dataset and how it's set up. It includes things like what kind of data is there, how many pieces of information it holds, and any extra details that help make sense of it. Knowing the composition helps researchers and analysts figure out the best ways to work with the data and understand what it can tell us.

- **First of Its Kind:** These datasets are the first of their kind to be publicly available for T1DM and T2DM patients in China, providing unique insights into the diabetic conditions prevalent in the region [9].
- **Research Utilization:** They are instrumental in developing algorithms and models tailored for improved diabetes monitoring and management, reflecting their substantial utility in clinical and biomedical research [10][12].
- **Updates and Accessibility:** Authored by Qinpei Zhao and colleagues, the datasets are meticulously updated, with the latest update logged on January 4, 2023. They are hosted with a DOI link for easy access and reference in scholarly and clinical studies [11].
- **Patient Data:** The ShanghaiT1DM dataset includes data from 12 patients with Type 1 diabetes mellitus, while the ShanghaiT2DM dataset encompasses data from 100 patients with Type 2 diabetes mellitus [8].
- **Data Duration and Type:** Continuous glucose monitoring (CGM) data ranges from 3 to 14 days. Additionally, each dataset contains detailed daily dietary information, including self-reported time and weighed food intake [11].
- **Additional Medical Information:** Both datasets comprehensively cover clinical characteristics, laboratory measurements, medications, and the use of insulin and non-insulin hypoglycemic agents [11].

## Data Analysis

Data analysis is the process of examining, cleaning, transforming, and interpreting data to uncover insights, identify patterns, and make informed decisions.

### Data Collection

The summary sheets summarize the clinical characteristics, laboratory measurements and medications of the patients included in this study, with each row corresponding to one excel table in “Shanghai_T1DM” and “Shanghai_T2DM” folders. Clinical characteristics include patient ID, gender, age, height, weight, BMI, smoking and drinking history, type of diabetes, duration of diabetes, diabetic complications, comorbidities as well as occurrence of hypoglycemia. Laboratory measurements contain fasting and 2-hour postprandial plasma glucose/C-peptide/insulin, hemoglobin A1c (HbA1c), glycated albumin, total cholesterol, triglyceride, high-density lipoprotein cholesterol, low-density lipoprotein cholesterol, creatinine, estimated glomerular filltra-tion rate, uric acid and blood urea nitrogen. Both hypoglycemic agents and medications given for other diseases before the CGM reading were also recorded [1].

- **Researching Topics:** Identified potential sources for data collection, including databases, sensors, APIs, or user-generated content.
- **Dataset Selection:** Chose a dataset aligned with our goals for diabetes education.
- **Data Storage:** Organized collected data in secure, accessible folders for team use.

### Data Cleanup
- **Data Review:** Checked data for accuracy, completeness, anomalies, and inconsistencies.
- **Cleaning Process:** Addressed issues through data cleaning techniques.
- **Data Validation:** Ensured cleaned data reliability through validation for all team members.

### Data Exploration
- **Statistical Analysis:** Calculated basic statistics to understand data distribution.
- **Visualization:** Created visual representations (histograms, box plots, scatter plots, heat maps) to reveal patterns, trends, and outliers.
- **Preliminary Analysis:** Conducted initial analysis to test assumptions and identify potential relationships in the data.

## Integration of Visualization Techniques

From a data analysis perspective, these visualization techniques not only improve understanding but also equip professionals with the skills necessary for handling complex data analyses in their careers. Integrating practical data manipulation exercises helps bridge the gap between theoretical knowledge and real-world application, contributing to more effective diabetes management and overall health outcomes.

---
![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/bmidistgender.png)

It was observed that there was a relatively equal proportion of male and female participants overall. However, a detailed analysis revealed a significant difference of 29.89% between the genders in terms of their representation within the optimal weight range. This finding underscores the significance of considering gender-specific variations in body composition and associated health outcomes.

---
- **Q2. Can we find any clear connections between blood sugar levels and common diabetes-related issues like eye, nerve, or kidney problems?:**
  
![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/bmidmc.png)

There is an almost even distribution of macrovascular complications across the entirety of this testing. You could infer that BMI may not have much effect on whether or not a diabetic patient will have a greater or less than chance to develop these complications.

---
![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/boxplotfastingplasma.png)


Overall elevated FPG levels are linked to a higher risk of chronic microvascular complications. With a whisker not appearing on top of Neuropathy, Retinopathy, and Nephropathy indicates the max value is closer to the mean and not far enough to be measured in a separate quartile. Even though it still contains a single outlier on the high end. The breakdown of patients had 89 patients with no complications present, 16 with just neuropathy, and 8 who had both neuropathy and retinopathy, and the remainder tapers off from there.

---
- **Q3. How are heart problems linked to different blood sugar levels in people with diabetes, and what does this mean for staying healthy?:**

![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Lewis-Hill/graph.png)

The histogram indicates there is a peak amplitude between age of diabetes diagnosis and the risk of microvascular disease. The data shows that early detection may mitigate the likelihood of complications. Most of the patients in the 50-70s range showed more macrovascular complications due to late diagnosis. Conversely, individuals diagnosed in their late 70s and on, demonstrate that a later in life diagnosis does not equate to an increase in macrovascular complications.

---
- **Q4. How often do people with diabetes have low blood sugar, and what can we do to prevent it?:**

![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/hypoglycemia.png)

The bar chart depicting hypoglycemia incidence reveals a relatively low occurrence rate, with only 11.0% of the sampled patients experiencing hypoglycemic episodes. Factors contributing to an elevated risk of hypoglycemia include low BMI, inadequate dietary habits, insufficient physical activity, and the presence of concurrent complications such as microvascular and macrovascular diseases. It is noteworthy that this sample set deviates from most expected trends, potentially influenced by dietary habits or local cultural variations.

---
- **Q5. Do blood sugar levels change over time in people with diabetes, and how can we use this knowledge to manage our health better?:**

![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/lineplothba1c.png)

HbA1c is the measure of average blood glucose levels over a period of time, commonly used to diagnose and monitor diabetes.  Within this study, an observable sine curve pattern emerges in the median HbA1c levels among individuals managing diabetes. Initially, there is a peak followed by a consistent decline over the initial five years, then followed by a gradual rise over the subsequent five-year period. This sine wave continues in regular intervals with diminishing returns. The shading represents the variability of the data around the confidence intervals and  reliability of the estimated trend.

---
- **Q6. How do the findings about age and cholesterol in people with diabetes match up with what we hear from doctors?:**

![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/scatteragecholesterol.png)

Cholesterol constitutes a significant health factor impacting individuals with diabetes. The widely accepted median value is 200 mg/dL or 5.2 mmol/L. In this study you can see a mean of approximately 4.8 mmol/L across all patients which aligns with the standards of the National Library of Medicine.

---
- **Q7. Do men and women face different risks for heart problems if they have diabetes, and what should we know about it?:**
  
![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/stackedbarchart.png)

In this data set males were at higher risk of macrovascular complications when their HbA1c levels were at 61-70 and above 100 mmol/mol. The females were more at risk in the 51-60 range. Notably males were more likely than females to develop macrovascular complications.
These discernible gender discrepancies emphasize the necessity for tailored approaches to diabetes management, acknowledging the distinct risk profiles and outcomes evident between males and females


## Challenges and Considerations

In a dataset, challenges and considerations for data quality involve making sure the information is accurate and consistent.

**Data Quality:** Managing data quality is a fundamental challenge in diabetes research. Issues such as missing data points and inconsistencies must be addressed through rigorous data preprocessing techniques. This includes data cleaning to remove inaccuracies, normalization to standardize data ranges, and feature selection to identify the most relevant variables for analysis [20].

**Data Privacy:** Ensuring the privacy of patient data in diabetes datasets like ShanghaiT1DM and ShanghaiT2DM is crucial. Strict protocols and ethical guidelines must be adhered to in order to protect sensitive information, which can include everything from patient identities to their medical histories [20].

## Limitations of Existing Datasets

Existing datasets often come with limitations that can impact their usefulness for analysis and decision-making. One common limitation is the lack of completeness or accuracy in the data, which can arise due to errors in data collection, missing information, or outdated records. 

**Impact of Dataset Size and Representativeness**

Our exploration of the ShanghaiT1DM and ShanghaiT2DM diabetes datasets has revealed a critical aspect regarding dataset size and representativeness. The  dataset illustrates the challenges posed by limited dataset scope. While it serves as a useful tool for demonstrating machine learning algorithms, its restricted coverage may not effectively represent the complex and varied nature of real-world diabetes cases [9].

**Absence of a Control Dataset and Its Impact**

The absence of a control dataset in the context of our research highlights the need for larger, more diverse datasets to improve the robustness and applicability of research findings in practical settings. This limitation emphasizes the necessity for comprehensive and varied data sources to ensure that research findings are both scientifically valid and ethically sound.

**Absence of a Cost Dataset and Its Impact**

The lack of a cost dataset can have significant consequences. It makes it harder to understand the economic aspects of managing diabetes, hindering efforts to assess affordability and accessibility of treatments. Additionally, without this data, identifying disparities in healthcare access among diabetic patients becomes challenging, potentially worsening inequalities in health outcomes. Therefore, having a cost dataset is essential for comprehensive analysis and informed decision-making in diabetes management.

## Future Recommendations for Diabetes Management Research

Drawing from the insights gained from the analysis of diabetes datasets, this document outlines future research recommendations that address areas not extensively covered in this study. These recommendations are supported by references to underscore their relevance and necessity.

**Lifestyle Interventions**

- **Recommendation**: Further research into the efficacy of specific dietary modifications and exercise regimens on both Type 1 and Type 2 diabetes management.
   - Rationale: To identify and refine lifestyle-based interventions that can effectively complement medical treatments for diabetes, offering a holistic approach to disease management[1].

**Psychosocial Factors**

- **Recommendation**: Quantitative analysis of the impact of psychosocial factors (e.g., stress, social support, mental health) on diabetes management outcomes.
   - **Rationale**: To understand how these factors affect diabetes control and patient well-being, informing care models that address both medical and psychosocial needs[1].

**Precision Medicine Approaches**

- **Recommendation**: Exploration of personalized diabetes management plans utilizing genomics and bioinformatics.
-    **Rationale**: To optimize treatment efficacy and minimize adverse effects based on individual genetic profiles, biomarker variations, and lifestyle factors[1].

**Telemedicine and Remote Monitoring**

- **Recommendation**: Evaluation of the effectiveness and patient satisfaction of telemedicine and remote monitoring technologies in diabetes care.
   - **Rationale**: To identify best practices and improve patient-centered care models in the digital health technology sphere[1].
**Health Equity and Access**

- **Recommendation**: Research focused on mitigating barriers to diabetes care access, especially among underserved and minority populations.
   - **Rationale**: To provide evidence-based recommendations that ensure advancements in diabetes care are universally accessible[1].

**Integration of Complementary Therapies**

- **Recommendation**: Assessment of the roles of complementary therapies (e.g., acupuncture, nutritional supplements, mindfulness practices) in standard diabetes treatment protocols.
   - **Rationale**: To understand the benefits and risks of these therapies, informing guidelines for their safe integration into diabetes care[1].
**Longitudinal Studies**

- **Recommendation**: Conducting studies to track the progression of diabetes, management outcomes, and the long-term effects of interventions.
   - **Rationale**: To gain insights into the natural history of diabetes and the efficacy of various management strategies over time[1].

By addressing these areas, future research can significantly enhance the understanding and management of diabetes, contributing to improved patient outcomes and care practices.


## Conclusion

In delving into the ShanghaiT1DM and ShanghaiT2DM datasets, we have undertaken an extensive exploration to discern the capacity of data visualization and correlation for elevating diabetes research. The employment of diverse visualization methods, including scatter plots, heat maps, and box plots, has yielded deep insights into the complex interrelations among various diabetes-related variables. These correlations, crucial for the progression of diabetes care, highlight the profound advantages of utilizing sophisticated data analysis tools in healthcare research. This meticulous examination of patterns has reaffirmed the critical role of data-driven decision-making in the medical sciences, emphasizing that advanced data visualization and correlation are essential for deriving significant insights into diabetes management.

Looking ahead, it is crucial to harness these insights for devising innovative strategies for diabetes prevention and management. The integration of machine learning algorithms and artificial intelligence within our analytical frameworks promises to transform personalized healthcare delivery, enabling the customization of interventions to individual patient profiles. This move towards a data-driven healthcare approach not only promises to improve patient outcomes but also to create a more sustainable and efficient healthcare system.

Therefore, we must persist in advancing the frontiers of data science and medical research, aiming for a future where precision in care is a reality for every individual, tailored to their specific needs at the right moment.


## FAQs

1. What is the most straightforward method for visualizing a correlation between two variables?
   - The simplest method to visualize a correlation between two variables is by using a scatterplot. This type of plot displays values for two numeric variables as dots on a graph, which helps in identifying any potential relationships between them without the need for calculating a correlation coefficient.

2. How does data storytelling differ from a data dashboard?
   - Data storytelling involves crafting a narrative around data to present it in a contextual and engaging manner. It employs various techniques to convey the story behind the data. On the other hand, a data dashboard is a tool that displays all relevant data in one place, allowing users to interpret and create their own narratives based on the comprehensive data provided.

3. What are the limitations of using BMI to determine body composition?
   - While Body Mass Index (BMI) is a commonly used metric for assessing body composition, it has several limitations. BMI, calculated based on height and weight, may not accurately reflect an individual's body composition, particularly in cases of high muscle mass or differences in bone density. Moreover, BMI categories do not differentiate between fat mass, muscle mass, and bone density, leading to potential misclassification of individuals' health status. Additionally, BMI does not account for variations in body fat distribution, such as central obesity, which is associated with higher health risks. Age, gender, and ethnic differences further complicate the interpretation of BMI, as its relationship with health outcomes may vary across different demographic groups. Reliance on BMI alone for assessing body composition can result in individuals being misclassified, potentially leading to delayed or inadequate interventions for those with unhealthy body compositions categorized as "normal weight" according to BMI standards. Therefore, while BMI is a useful tool at the population level, it should be interpreted cautiously and complemented with other measures, such as waist circumference and body fat percentage, for a more comprehensive evaluation of body composition and associated health risks.

## Glossary

-**Diabetes:** A chronic medical condition characterized by elevated levels of blood sugar, resulting from the body's inability to produce or effectively use insulin.
-**HbA1c:** Hemoglobin A1c, a measure of average blood glucose levels over a period of time, commonly used to diagnose and monitor diabetes.
-**BMI:** Body Mass Index, a measure of body fat based on an individual's weight and height, often used to assess the risk of developing various health conditions, including diabetes.
-**Microvascular Complications:** Diabetes-related complications affecting small blood vessels, such as those in the eyes, kidneys, and nerves.
-**Macrovascular Complications:** Diabetes-related complications affecting large blood vessels, often associated with cardiovascular diseases such as heart disease and stroke.
-**Statistical Analysis:** The process of collecting, cleaning, analyzing, and interpreting numerical data to uncover patterns, trends, and associations within a dataset.
-**Correlation Studies:** Research methods aimed at identifying relationships or associations between different variables or factors within a dataset.
-**Visualization Techniques:** Methods of presenting data and statistical findings in visual formats, such as charts, graphs, and diagrams, to facilitate understanding and communication of complex information.
-**Age Distribution:** The representation of the distribution of individuals within a population based on their age, often used to analyze age-related patterns and trends in health conditions.
-**Statistical Tests:** Formal procedures used to make inferences about relationships or differences within a dataset, such as t-tests, ANOVA, and chi-square tests, to assess the significance of findings.

## Code availability 
The code for the analysis of the datasets and visualizations can be accessed in the GitHub repository, which is a JUPYTER notebook located within the code directory. The scripts can be executed with Python 3.6 and allows for reproducibility and code reuse.

## References

[1] - https://www.researchgate.net/publication/367252616_Chinese_diabetes_datasets_for_data-driven_machine_learning
[2] - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6718069/
[3] - https://www.kaggle.com/code/soheylbokaie/diabetes-data-analysis-insights-and-visualization
[4] - https://digital.ahrq.gov/sites/default/files/docs/citation/r21hs023865-lee-final-report-2018.pdf
[5] - https://www.researchgate.net/publication/374612719_Data_Visualization_of_Big_Data_for_Predictive_and_Descriptive_Analytics_for_Stroke_COVID-19_and_Diabetes
[6] - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6746071/
[7] - https://www.atlantis-press.com/journals/hcis/125965543/view
[8] - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9849330/
[9] - https://sites.google.com/view/uci-diabetes-datase-davgarl1j
[10] - https://www.nature.com/articles/s41597-023-01940-7
[11] - https://figshare.com/collections/Diabetes_Datasets_ShanghaiT1DM_and_ShanghaiT2DM/6310860
[12] - https://ui.adsabs.harvard.edu/abs/2023NatSD..10...35Z/abstract
[13] - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6176528/
[14] - https://diabetesjournals.org/care/article/46/7/1316/151548/Use-of-Real-World-Data-in-Population-Science-to
[15] - https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-019-0918-5
[16] - https://www.nature.com/articles/s41597-023-02469-5
[17] - https://www.linkedin.com/pulse/unveiling-insights-correlation-analysis-unleashing-power-bhaskaran-
[18] - https://medium.com/@JaveriaSaif/correlation-in-data-analytics-75fec1f2147d
[19] - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6375260/
[20] - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10544445/


