# Portfolio
This portfolio includes a variety of undergraduate, personal, and professional projects.

## [Duke Energy: Statistical Modeling for Customer Energy Usage (R)](https://github.com/ddemo829/Duke-Energy-Statistical-Modeling-R)
My work experience with Duke Energy involved collaborating with my team to develop statistical models for approximately 200 of Duke Energy's customers (~8,600 observations per customer; ~1,700,000 observations total) around the state of North Carolina in order to target inefficient HVAC systems. This project (written in R) involved:

* Modeling hourly customer kWh usage between September 2021 and September 2022 against key explanatory variables such as outdoor temperature and date-time, along with a variety of variable transformations.
* Wrangling customer data to maintain strong data integrity.
* Starting with simple models, then adding more complexity when needed.
* Utilizing for-loops, industry standard train-test splits, and Mean Squared Error (MSE) calculations to determine highest performing models.
* Visualizing model strength through MSE calculations and residual plots using ggplot2 packages.
* A written report and presentation summarizing the key findings to a senior data scientist at Duke Energy.

### Scatter plot of customer kWh usage by outdoor temperature with seasons
![](Portoflio images/customer scatter.jpg)

### Residual plot and MSE distribution for linear model
![](Portoflio images/lm residual plot.jpg) ![](Portoflio images/lm mse.jpg)

### Residual plot and MSE distribution for cube root model (summer)
![](Portoflio images/cubrt residual and mse.jpg)

## [Ace Industrial Supply: Data Copying and Formatting Automation (Excel VBA)](https://github.com/ddemo829/Ace-Industrial-Supply-Data-Automation-VBA)
My work experience with Ace Industrial Supply involved programming Excel macros in VBA in order to efficiently copy and reformat data into a readable format for databases. This project involved:

* Seeking a consistent structure of messy data to brainstorm potential areas for automation.
* Writing versatile code that accounts for a variety of inconsistent formats and structures.
* Testing out smaller, less complex macros to ensure copy and formatting accuracy of messy data before final implementation.
* Delivering exported data to supervisor.

### Messy data → formatted clean data
<p align="center">
 <img src="Portoflio images/ACE messy data.jpg" width="300" Height="250"> 
 <img src="Portoflio images/ACE clean data.jpg">
</p>  

### Screen recording of macro [here](https://youtu.be/yYXebG6os84)


## [The Effects of Visual and Auditory Cues on Human Reaction Time (SAS)](https://github.com/ddemo829/The-Effects-of-Visual-and-Auditory-Cues-on-Human-Reaction-Time-SAS)
The goal of this undergraduate project for my team and I was to showcase our understanding of Analysis of Variance (ANOVA), contrasts, confidence intervals, and experimental design. This project (written in SAS) involved:

* Handwriting and interpreting a "decomposition diagram" to visualize segments of variation among blocks, factor levels, and residuals. We then referenced the ANOVA table in SAS's proc glm to verify our calculations.
* Interpreting ANOVA F statistic, family wise confidence intervals, and contrasts.
* In a presentation, explaining the complexities of experimental design to a non-technical audience.

### Decomposition of variance and ANOVA table results
<p align="center">
 <img src="Portoflio images/STS3250 decomp.jpg"> 
 <img src="Portoflio images/STS3250 Anova table.jpg">
</p>  

