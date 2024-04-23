# MIST4610 Project-2--Group-6


## Team Member Names: 

Group 6-

Hannah Ganeriwal [@hannahganeriwal](https://github.com/hannahganeriwal/MIST4610-Project-1--Group-6)

Luke Liu [@lukel04](https://github.com/lukel04/MIST4610-Project-1--Group-6)

Robert Black [@robertblack11](https://github.com/robertblack11/MIST4610-Project-1--Group-6)

Sarah Kirk [@sarahkirk03](https://github.com/sarahkirk03)

Wyatt Bewley [@wsb38150](https://github.com/wsb38150)

Zachary Bowles [@zeb19037](https://github.com/zeb19037/MIST4610-Project-1--Group-6)



## Describing your dataset and what data it contains:

We were able to pull this dataset from the data.gov website titled “NCHS - Leading Causes of Death: United States.” This dataset shows recorded information about deaths for the 10 leading causes of death in all 50 states in the United States, starting in 1999 until 2017. Populations used for computing death rates after 2010 are postcensal estimates based on the 2010 census, estimated as of July 1, 2010. The 10 leading causes include Alzheimers, Strokes, CLRD (chronic lower respiratory disease), Diabetes, Heart Disease, Influenza and pneumonia, Suicide, Cancer, Kidney Disease, and unintentional injuries. Within this dataset, there are 10,868 rows, and each row represents a specific cause of death in a specific year for a specific state. This means that each row is a death statistic for a disease in a specific state for the year. For each case, the dataset recorded the year of death (as an INT), the ICD classified 113 Cause Name (VARCHAR), the commonly used Cause Name (VARCHAR), the state the death occurred in (VARCHAR), the Deaths total (INT), and the Age-Adjusted Death Rate (DECIMAL), which is the amount of deaths per 100,000 people of the population. This results in a table of 10,868 rows and 6 columns. This dataset is very effective in communicating the death rates for each state. It is very easy to see what causes of death are the most prevalent. It also allows us to look into how these death rates changed over time, and what sort of effect the geography of them had on these rates.

## Question 1: 

### What are the leading causes of death from 1999-2017 and how can that correlate with advancements in medical treatments? Does the trend line suggest a change in the leading cause?

### Importance: 
This question is essential for evaluating the impact of medical advancements and public health interventions on population health outcomes. It can be significant to understand how mortality rates for specific causes of death, such as cancer and heart disease, which based on this data, are by far the 2 leading causes of death, have changed over time can provide insights into the effectiveness of interventions aimed at preventing, detecting, and treating these diseases. By correlating changes in mortality rates with advancements in medical treatments, screening programs and lifestyle interventions, we can thoroughly assess the progress made in reducing mortality from these diseases and identify areas for further improvement. 


### The manipulations applied to the data set as part of the analysis:
For this graph, we had to perform a few manipulations in order to get this outcome. This dataset was broken up by all the causes of death but also included one calculation which was the total sum of all causes, which we excluded to solely look at the individual causes or else our data set would have been skewed. To also get these exact results, we had to filter all the causes except cancer and heart disease. Additionally, we had to drag “trend lines” from the analytics tab in order to analyze the slope of the lines.

### Analysis and Results:	
Impact of Medical Advancements: By correlating changes in mortality rates for specific causes of death with advancements in medical treatments and public health interventions, the analysis assessed the effectiveness of interventions in reducing mortality from diseases like cancer and heart disease. 
This visualization is a trend line from 1999-2017 which provided insight into the temporal relationship between interventions and mortality outcomes. In 1999, the death rate for heart disease totaled to 13,059 and in 2017 it totaled to 8,466. Additionally, in 1999 for cancer, the total age adjusted death rate was 10,275 and in 2017 it was 7,905. 
We also analyzed a linear trend line for both death causes which is represented by a dashed line correlated to its relative color of cause. In Tableau, it was interesting to note how for heart disease the slope read -275 and for cancer the slope was -132. In this case for example, the intercept of -132 indicates that the age-adjusted death rate for cancer in 1999 was estimated to be 132 deaths per 100,000 population lower than what would have been expected based on the pre-existing trend. The decrease in age-adjusted death rates for both heart disease and cancer from 1999 to 2017 suggests a positive trend in mortality outcomes and that even without any further intervention, there would have been a decrease in death rates over time. 
Last thing to note that this graph provided insight on is that based on these trend lines, it is indicated that cancer will soon be the leading cause of death rather than heart disease. Based on the slopes that we analyzed, we can see that the decrease is much quicker for heart disease, which is why this projection is seen to be accurate. This compares to an article from the CDC stating, “Our projections indicate that cancer will soon become the leading cause of death in the United States if trends in risk of death from cancer and heart disease and population growth and aging continue” (CDC 2019) which aligns with our model. 


Centers for Disease Control and Prevention. "Trends in Cancer and Heart Disease Death Rates Among <br />
&emsp;Adults Aged 45–64: United States,1999–2017." Preventing Chronic Disease, vol. 16, 2019,<br /> &emsp;https://www.cdc.gov/pcd/issues/2016/16_0211.htm.

&emsp;

## Question 2: 
### Examine the proportional distribution of the 10 primary causes of death between the years 1999-2008 and 2008-2017 within the states of Georgia, South Carolina, and Alabama. Assess how the proportions of each cause of death changed within each state over the specified time frames.

### Importance
Analyzing the proportional distribution of the 10 leading causes of death over two different 10 year time periods across all states serves several purposes. Firstly, it helps in identifying emerging health trends by examining changes in the proportional distribution of causes of death, allowing public health officials to prioritize areas for intervention and prevention efforts as effectively as they can. Secondly, understanding the proportional distribution assists healthcare administrators in allocating resources more efficiently, as it provides insights into which health conditions are most prevalent and where resources are needed most urgently, especially targeting state specific health issues. Lastly, this analysis supports public health planning and policymaking by providing valuable information for setting priorities, designing targeted interventions, and developing strategies to address the most pressing health issues within specific populations and geographic regions. Overall, examining the proportional distribution of the 10 leading causes of death is essential for understanding population health trends, guiding resource allocation, evaluating intervention effectiveness, and informing public health planning efforts aimed at improving overall health outcomes and reducing premature mortality.

### The manipulations applied to the data set as part of the analysis:
Were there any manipulations or calculations that needed to be performed on the data, what were they, describe the purpose and how they were accomplished.	


### Analysis and Results:	
Analyze and visualize the results of your analysis and describe the implications of your analysis. Please provide any citations if required as well as supporting visualizations and analysis generated from Tableau. 


Tableau Packaged Workbook 
Save or Export your project as a Tableau packaged workbook file and provide it as part of the github repository.					
This group project is worth 12.5% of your final grade. 


