# Visual Analysis of Health Factors in Diabetes


![Visualization](C:\Users\19727\AI\SMU-VIRT-AI-PT-02-2024-U-LOLC\Group-3_Project1\Document\README_image.png)


## Introduction
This study aims to visually analyze the ShanghaiT1DM and ShanghaiT2DM datasets to uncover correlations and insights regarding various health factors in individuals with diabetes.

## Key Questions Addressed
1. **Understanding Health Factors in Diabetes**
   - How do weight, blood sugar levels, age, cholesterol, and gender interrelate in individuals with diabetes, and how can these correlations inform strategies for maintaining overall health?

2. **Diabetes-Related Health Connections**
   - What are the specific connections between blood sugar levels and prevalent diabetes-related complications such as eye, nerve, and kidney problems, and how can these visualized connections guide strategies for mitigating associated risks and promoting well-being?

3. **Gender, Heart Risks, and Blood Sugar**
   - Do men and women with diabetes face differing heart risks based on blood sugar levels, and how can visualized correlations aid in developing tailored heart health management strategies for specific gender-related risks in the context of diabetes?

## Research Objectives
By addressing these questions, the study aims to provide comprehensive visual insights into the interplay of various health factors in individuals with diabetes, with the ultimate goal of contributing to improved diabetes management and overall health outcomes.

**Significance of Research:** This study holds significant promise in enhancing our understanding of the complex interrelationships between health factors in individuals with diabetes. The findings may benefit the healthcare industry in the following ways:

1. **Informed Treatment Strategies:** Healthcare professionals can utilize the visualized correlations and insights to develop more informed and personalized treatment strategies for individuals with diabetes, taking into account the interplay of various health factors.

2. **Preventive Care and Risk Mitigation:** The identified connections between blood sugar levels and diabetes-related complications can guide healthcare providers in implementing proactive measures for mitigating associated risks and promoting well-being in patients with diabetes.

3. **Tailored Health Management:** Visualized correlations regarding gender-specific heart risks based on blood sugar levels can aid in developing tailored heart health management strategies for men and women with diabetes, thus improving the overall care for individuals with this condition.

4. **Enhanced Patient Education:** The visual insights from this study can contribute to enhanced patient education, empowering individuals with diabetes to better understand the interrelationships between various health factors and make informed decisions about their health and well-being.

In summary, the findings of this study have the potential to significantly enhance the quality of care and management of diabetes within the healthcare industry, ultimately leading to improved health outcomes for individuals with diabetes.


### Integration of Visualization Techniques

The datasets allow for the application of complex visualization techniques which are crucial for data-driven decision-making in healthcare. By using tools like Python and Seaborn, we can demonstrate how to effectively communicate complex data through: 

- **Scatter Plots and Box Plots:** Visualizing relationships between different variables such as HbA1c levels and microvascular complications [3].
- **Heat Maps:** Showing correlation matrices that help in understanding the interdependencies among various clinical parameters [5].

These visualization techniques not only enhance our research experience but also equip us with the skills needed to handle sophisticated data analyses in our future careers. The inclusion of such practical data manipulation helps bridge the gap between theoretical knowledge and real-world application, making the study process more comprehensive and impactful.

![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/bmidist.png)
The analysis of the sample set revealed that most patients fell within the body mass index range of 18.5 - 25 kg/m², in relation to the second quartile. This range is identified by the Center for Disease Control as representing a healthy or optimal weight status for the general population. 


![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/bmidistgender.png)
It was observed that there was a relatively equal proportion of male and female participants overall. However, a detailed analysis revealed a significant difference of 29.89% between the genders in terms of their representation within the optimal weight range. This finding underscores the significance of considering gender-specific variations in body composition and associated health outcomes.


![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/bmidmc.png)
There is an almost even distribution of macrovascular complications across the entirety of this testing. You could infer that BMI may not have much effect on whether or not a diabetic patient will have a greater or less than chance to develop these complications.


![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/boxplotfastingplasma.png)
Overall elevated FPG levels are linked to a higher risk of chronic microvascular complications. With a whisker not appearing on top of Neuropathy, Retinopathy, and Nephropathy indicates the max value is closer to the mean and not far enough to be measured in a separate quartile. Even though it still contains a single outlier on the high end. The breakdown of patients had 89 patients with no complications present, 16 with just neuropathy, and 8 who had both neuropathy and retinopathy, and the remainder tapers off from there.


![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/histogram.png)
The histogram indicates there is a peak amplitude between age of diabetes diagnosis and the risk of microvascular disease. The data shows that early detection may mitigate the likelihood of complications. Most of the patients in the 50-70s range showed more macrovascular complications due to late diagnosis. Conversely, individuals diagnosed in their late 70s and on, demonstrate that a later in life diagnosis does not equate to an increase in macrovascular complications.


![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/hypoglycemia.png)
The bar chart depicting hypoglycemia incidence reveals a relatively low occurrence rate, with only 11.0% of the sampled patients experiencing hypoglycemic episodes. Factors contributing to an elevated risk of hypoglycemia include low BMI, inadequate dietary habits, insufficient physical activity, and the presence of concurrent complications such as microvascular and macrovascular diseases. It is noteworthy that this sample set deviates from most expected trends, potentially influenced by dietary habits or local cultural variations.


![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/lineplothba1c.png)
HbA1c is the measure of average blood glucose levels over a period of time, commonly used to diagnose and monitor diabetes.  Within this study, an observable sine curve pattern emerges in the median HbA1c levels among individuals managing diabetes. Initially, there is a peak followed by a consistent decline over the initial five years, then followed by a gradual rise over the subsequent five-year period. This sine wave continues in regular intervals with diminishing returns. The shading represents the variability of the data around the confidence intervals and  reliability of the estimated trend.


![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/scatteragecholesterol.png)
Cholesterol constitutes a significant health factor impacting individuals with diabetes. The widely accepted median value is 200 mg/dL or 5.2 mmol/L. In this study you can see a mean of approximately 4.8 mmol/L across all patients which aligns with the standards of the National Library of Medicine.


![Visualization](https://github.com/LaShawnSykes/Group-3_Project1/blob/Aaron-Cranor/PNGs/stackedbarchart.png)
In this data set males were at higher risk of macrovascular complications when their HbA1c levels were at 61-70 and above 100 mmol/mol. The females were more at risk in the 51-60 range. Notably males were more likely than females to develop macrovascular complications.
These discernible gender discrepancies emphasize the necessity for tailored approaches to diabetes management, acknowledging the distinct risk profiles and outcomes evident between males and females


# Correlation Insights from the Datasets
<Insert information about the correlation insights from the all of the visualizations presented >

## Challenges and Considerations

**Data Quality:** Managing data quality is a fundamental challenge in diabetes research. Issues such as missing data points and inconsistencies must be addressed through rigorous data preprocessing techniques. This includes data cleaning to remove inaccuracies, normalization to standardize data ranges, and feature selection to identify the most relevant variables for analysis [20].

## Limitations of Existing Datasets

# Impact of Dataset Size and Representativeness

Our exploration of the ShanghaiT1DM and ShanghaiT2DM diabetes datasets has revealed a critical aspect regarding dataset size and representativeness. The  dataset illustrates the challenges posed by limited dataset scope. While it serves as a useful tool for data correlation and insight, its restricted coverage may not effectively represent the complex and varied nature of real-world diabetes cases [9].

# Absence of a Control Dataset and Its Impact

The absence of a control dataset in the context of our research highlights the need for larger, more diverse datasets to improve the robustness and applicability of research findings in practical settings. This limitation emphasizes the necessity for comprehensive and varied data sources to ensure that research findings are both scientifically valid and ethically sound.


## Conclusion

Through our exploration of the ShanghaiT1DM and ShanghaiT2DM datasets, we've embarked on a comprehensive journey to understanding the potentials of data visualization and correlation in enhancing diabetes research. The use of various visualization techniques such as scatter plots, heat maps, and box plots has provided us with intricate insights into the relationships between different diabetes-related variables. These correlations, crucial for advancing diabetes care, illustrate the significant benefits of employing advanced data analysis tools in healthcare research. By analyzing these patterns, we've reaffirmed the importance of data-driven decisions in medical sciences, reinforcing the thesis that sophisticated data visualization and correlation techniques are pivotal in extracting meaningful insights for diabetes management.

Reflecting on the broader implications of our findings, it is evident that the integration of data correlation and visual insights into research and educational settings holds profound potential for revolutionizing diabetes care and management. The article's discussions underscore the necessity for further research and the adoption of these methodologies across healthcare disciplines. By leveraging the visual representations and analyses presented, researchers and practitioners can gain a deeper understanding of diabetes complexities, thereby enhancing predictive accuracies and treatment outcomes. It is with this foundation that we advocate for the continued exploration and utilization of such advanced data analysis techniques, ensuring the progression toward more informed and effective diabetes management strategies.

## FAQs

1. What is the most straightforward method for visualizing a correlation between two variables?
   - The simplest method to visualize a correlation between two variables is by using a scatterplot. This type of plot displays values for two numeric variables as dots on a graph, which helps in identifying any potential relationships between them without the need for calculating a correlation coefficient.

2. How does data storytelling differ from a data dashboard?
   - Data storytelling involves crafting a narrative around data to present it in a contextual and engaging manner. It employs various techniques to convey the story behind the data. On the other hand, a data dashboard is a tool that displays all relevant data in one place, allowing users to interpret and create their own narratives based on the comprehensive data provided.

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