# Global AI Job Market Analysis Using SAS

## Business Background

The rapid growth of Artificial Intelligence has transformed the global job market, creating increasing demand for skilled professionals across different industries and regions. Organizations, job seekers, and policymakers require data-driven insights to understand salary trends, experience requirements, remote work opportunities, and compensation structures within the AI workforce.

Traditional approaches to labor market analysis often struggle to identify emerging trends and compensation patterns due to the large volume and complexity of job market data. Therefore, analytics-driven approaches are required to support workforce planning, salary benchmarking, and career decision-making.

---

## Business Problem

Organizations and professionals face challenges in understanding the factors that influence salaries and compensation in the global AI job market. Key questions include:

* Does experience significantly affect salary levels?
* How does remote work influence compensation?
* Do larger companies offer better compensation packages?
* What factors drive total employee compensation in AI-related roles?

Without analytical insights, organizations may struggle with competitive compensation strategies, while job seekers may lack information regarding career progression and salary expectations.

---

## Project Objective

This project aims to analyze the Global AI Job Market dataset using SAS to identify salary and compensation patterns across different experience levels, remote work categories, and company characteristics.

The objectives of this study are:

* Analyze salary trends across experience categories.
* Examine the relationship between years of experience and salary.
* Evaluate the impact of remote work arrangements on salary and compensation.
* Investigate compensation differences across company sizes.
* Generate actionable insights through statistical analysis and visualization.

---

## Data Preparation & Feature Engineering

Data preprocessing and feature engineering were conducted using SAS to improve data quality and analytical accuracy.

### Data Preprocessing

* Missing values in salary were imputed using median values.
* Missing values in years of experience were handled using median imputation.
* Missing values in remote ratio were imputed using mean values.
* Missing values in education required and company size were replaced with "Unknown".
* Outliers and skewness were identified through exploratory analysis.

### Feature Engineering

Several new variables were created to support analysis:

* Log Salary Transformation
* Remote Work Category (On-Site, Hybrid, Remote)
* Experience Category (Entry, Mid, Senior, Expert)
* Total Compensation
* Company Size Salary Premium

---

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted using SAS procedures including PROC MEANS, PROC FREQ, PROC CORR, and PROC SGPLOT.

The analysis explored:

* Salary distribution patterns
* Experience and salary relationships
* Compensation trends across experience levels
* Remote work and salary comparisons
* Company size and compensation relationships
* Correlation between salary, benefits, and experience

---

## Key Insights

* Experience level is one of the strongest determinants of salary in the global AI job market.
* Salaries increase consistently from entry-level to expert-level positions.
* A positive relationship exists between years of experience and salary.
* Total compensation increases significantly with experience level.
* Remote work arrangements show only minor differences in salary and compensation.
* Company size has limited influence on total compensation compared to experience and role-related factors.
* Benefits score contributes positively to total compensation packages.

---

## Screenshots 
**Total Compensation**

<img width="832" height="629" alt="image" src="https://github.com/user-attachments/assets/d57d74dd-c812-4c49-833b-71d8f3cf2564" />

**Salary Across Experience Category**

<img width="735" height="540" alt="image" src="https://github.com/user-attachments/assets/f4bff4ed-ed50-48e2-9e3f-ecc051b461f1" />

**Years of Experience and Salary**

<img width="673" height="504" alt="image" src="https://github.com/user-attachments/assets/ed84b994-578d-400f-ac2d-bc2cfc6fd01e" />


<img width="779" height="590" alt="image" src="https://github.com/user-attachments/assets/9e979dc8-7f07-464a-8272-7e21bdcd766b" />

**Total Compensation and Experience**

<img width="789" height="600" alt="image" src="https://github.com/user-attachments/assets/de1f2449-ae94-4631-b2f3-3dd4890e6e6c" />

**Total Compensation by Company Size**

<img width="689" height="522" alt="image" src="https://github.com/user-attachments/assets/5c6822be-8f3a-46b8-a42a-607fd8b57472" />

**Salary and Remote Work**

<img width="749" height="558" alt="image" src="https://github.com/user-attachments/assets/f394b175-ceb3-4caa-ab87-30da6ac1ff2c" />








## Discussion

The findings indicate that career progression and accumulated experience have a substantially greater impact on compensation than remote work arrangements or company size. While remote, hybrid, and on-site roles exhibit slight salary differences, experience remains the dominant factor influencing both salary and total compensation.

The analysis further demonstrates the value of feature engineering techniques such as log salary transformation and total compensation calculation in uncovering meaningful labor market trends.

---

## Conclusion

This project successfully analyzed the Global AI Job Market dataset using SAS-based preprocessing, feature engineering, and exploratory data analysis techniques. The results highlight that experience level, years of experience, and role progression are the primary drivers of salary and total compensation in the AI workforce.

The project demonstrates how data analytics can support workforce planning, compensation benchmarking, and strategic decision-making within the rapidly evolving global AI job market.

