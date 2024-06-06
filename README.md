

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

This study explores the intricate relationship between demographic characteristics, behavioral patterns, and individual well-being, with the goal of identifying key determinants of health status. Utilizing a dataset from Kaggle, we embark on a comprehensive analysis using a variety of predictive models including logistic regression and random forest, to uncover the factors that significantly impact an individual’s health status. Our research includes a wide range of variables such as sleep patterns, education level, employment status, marital status, and self-reported health status. Through logistic regression and random forest, we aim to explore the probabilistic and statistical relationship between these variables, the likelihood of good health based on these variables, and capture complex non-linear interactions between them. The findings from this research are expected to enhance our understanding of the multifaceted determinants of health and provide an effective model to predict individual well-being. Ultimately, this study aims to inform public health strategies and individual wellness practices, contributing to the improvement of health outcomes across diverse populations.

## 1 Introduction

By evaluating the environmental impact of increased remote work by comparing carbon footprints before the pandemic, during the pandemic, and after the pandemic. Comparing carbon footprints to evaluate the environmental impact before, during, and after the pandemic is important for many reasons. Understanding how remote work affects carbon emissions can help governments make rules, helping meet goals to reduce pollution. Insights from this analysis can help many companies that are committed to sustainability goals to understand how shifting work patterns may contribute to the goals. 
This research can also give an intricate analysis of the environmental change due to increased remote works, in which urban planners and infrastructure developers can adjust their projects to accommodate a future with potentially less commuting, which may reshape public transportation schedules, reducing road expansions, or repurposing office space areas into residential or green spaces. Moreover, communities can better prepare for any future disruptions, whether they’re due to health issues, environmental concerns, or technology changes. In this study, we will… 

## 2 Demographic and Behavioral Data
	
### 2.1 Data Source


	
### 2.2 Exploratory Data Analysis


<p align="center">
<img src = "images/pairplot.png">
	
**Figure 1: Pairplot**
</p>


<p align="center">
<img src = "images/boxplot3.png">

**Figure 2: Boxplot**
</p>


<p align="center">
<img src = "images/heatmap.png">

<p align="center">
**Figure 3: Heatmap**
	</p>
</p>



## 3 Predictive Model
	
### 3.1 Linear Regression





### 3.1.1 Assumptions and Model Diagnostics

<p align="center">
<img src = "images/redisuals.png">
	<p align="center">
**Figure 4: Residual Plot**
		</p>
</p>

<p align="center">
<img src = "images/logodds.png">
	<p align="center">
**Figure 5: Log-odds against predictors**
		</p>
</p>


<p align="center">
<img src = "images/ROCcurve.png">
<p align="center">
**Figure 6: ROC Curve**
	</p>
</p>


### 3.1.2 Preprocessing, Modeling and Prediction
	
<p align="center">
<img src = "images/logisticcm.png">
<p align="center">
**Figure 7: Confusion matrix**
	</p>
</p>

	
### 3.2 Random Forest Classification
	









<p align="center">
<img src = "images/randomforestconf.png">
	
**Figure 8: Confusion matrix**
</p>

	
## 4  Conclusion and Future Works
	


































References

[1] Kapturov, Alexander. (2024). Sleep Patterns. Kaggle.
      https://www.kaggle.com/datasets/kapturovalexander/sleep-patterns
      
[2] Bohi, Naimish. (2024). Sleep Patterns with Pandas. Kaggle.
      https://www.kaggle.com/code/naimishbhoi/sleep-patterns-with-pandas
      
[3] Giacometti, Alessandro. (2024). Sleep Health Analysis-How to Sleep Better. Kaggle.
      https://www.kaggle.com/code/alessandrogiacometti/sleep-health-analysis-how-to-sleep-better