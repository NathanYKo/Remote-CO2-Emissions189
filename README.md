

---

# Remote-CO2-Emissions189

---
<p align="center">
Jun Hwang,
</p>

<p align="center">
Isaiah Jones,
</p>

<p align="center">
Nathan Ko
</p>

---

## Abstract

This study explores the relationship between the brief transition to remote work in 2020 and $\mathrm{CO_2}$ consumptions within the U.S. with the goal.... Utilizing a dataset from  U.S. Energy Information Administration, we embark on a comprehensive analysis using a variety of statistical methods including linear regression and hypothesis testing, to uncover....  Through linear regression, we aim to explore the probabilistic and statistical relationship. This research evaluates the environmental impact of increased remote work by comparing carbon footprints before, during, and after the pandemic, focusing on how shifts in remote work affect carbon emissions, urban planning, and infrastructure development. It provides valuable insights for governments, companies, and communities to adapt policies and projects that support sustainability goals and accommodate future commuting trends





## 1. Introduction

By evaluating the environmental impact of increased remote work by comparing carbon footprints before the pandemic, during the pandemic, and after the pandemic. Comparing carbon footprints to evaluate the environmental impact before, during, and after the pandemic is important for many reasons. Understanding how remote work affects carbon emissions can help governments make rules, helping meet goals to reduce pollution. Insights from this analysis can help many companies that are committed to sustainability goals to understand how shifting work patterns may contribute to the goals. 
This research can also give an intricate analysis of the environmental change due to increased remote works, in which urban planners and infrastructure developers can adjust their projects to accommodate a future with potentially less commuting, which may reshape public transportation schedules, reducing road expansions, or repurposing office space areas into residential or green spaces. Moreover, communities can better prepare for any future disruptions, whether they’re due to health issues, environmental concerns, or technology changes. In this study, we will… 

## 2. Demographic and Behavioral Data
	
### 2.1 Data Source
Our data comes from the U.S. Energy Information Administration and... It comprises CO2 emissions data for all fifty states from 1970 to 2021. With other columns.
We have two datasets: 

	
### 2.2 Exploratory Data Analysis


<p align="center">
<img src = "images/lineplot_CO2.png">
	
**Figure 1: Lineplot**
</p>
<p>
This line plot displays the changes in CO2 emissions over time from 2018 to 2021 for selected states. The y-axis shows the CO2 emissions in million metric tons (MMT), and the x-axis represents the years.
Texas has the highest CO2 emissions, while other states show varying levels of emissions with some fluctuations over the years.
It is also possible to see that there is a sudden drop in CO2 Emissions from 2019 to 2020, which is the year when COVID-19 peaked.     
</p>

<p align="center">
<img src = "images/lineplot_WFH.png">

**Figure 2: Lineplot**
</p>
<p>
This line plot illustrates the change in the number of people working from home from 2018 to 2021 for selected states. The y-axis shows the number of people working from home, and the x-axis represents the years. Most of the states such as California shows a significant increase in the number of people working from home, especially around 2020, likely due to the COVID-19 pandemic.    
</p>

<p align="center">
<img src = "images/corrplot.png">


**Figure 3: Correleation Scatter plot**
	</p>
</p>
<p>
This scatter plot shows the relationship between the number of people working from home and the CO2 emissions in million metric tons (MMT). Each point represents a state. The correlation coefficient is 0.60, indicating a moderate positive correlation between working from home and CO2 emissions.
</p>


<p align="center">
<img src = "images/merged_lineplot.png">
	
**Figure 4: Merged Line Plot**
</p>

<<<<<<< Updated upstream
## 3 Regression model
=======
## 3. Predictive Model
>>>>>>> Stashed changes
	
### 3.1 Linear Regression





### 3.1.1 Assumptions and Model Diagnostics

<p align="center">
<img src = "images/residual.png">

**Figure 5: Residual Plot**
		</p>
</p>

<p align="center">
<img src = "images/QQplot.png">
	<p align="center">

**Figure 6: QQplot**
		</p>
</p>
<p>
The histogram of residuals and Q-Q plot are provided to see the general trend and to assess if the dataset follows a normal distribution. In this histogram, the residuals appear to be normally distributed, centered around zero, with a bell-shaped curve. 
This suggests that the regression model fits the data well and that the assumptions of normality and homoscedasticity (constant variance) of residuals are likely satisfied.    
</p>


### 3.1.2 Preprocessing, Modeling and Prediction
	


	
### 3.2 Hypothesis Testing
	





	
**Figure 8: Confusion matrix**
</p>

	
## 4.  Conclusion and Future Works
	


































References

[1] U.S. Energy Information Administration. (2023). State energy-related carbon dioxide emissions by year. EIA. 
		https://www.eia.gov/environment/emissions/state/
      
[2] (2024). . United States Census Bureau.
      https://data.census.gov/
      
