# NexTech: HR Analytics

## Problem Definiton

Mitigating the drivers of employee attrition is essential to safeguarding a company’s financial health and sustaining operational efficiency.
Departure of skilled workforce entails both direct and indirect financial costs like Onboarding, adaption costs, opportunity costs.

**Objective of the study**
- Identify key drivers of employee attrition
- Uncover anomalies in the organization
- Path forward : Identify practical measures to retain the talent

**Study Baseline:** 
The baseline attrition rate in this sample is 16.1% (237 out of 1470 employees). This is the starting point to analyze causes for attrition.

## Data Souce
A verified corporate dataset (based on IBM HR Analytics data) was extracted for the study. The total sample size comprises 1,470 observations, ensuring high representativeness and statistical significance for the insights derived.

The data source architecture gathered following information:
1. **Demographic metrics**: Age, gender, MaritalStatus, Education, EducationField, DistanceFromHome
2. **Job Information**: Department, JobRole, JobLevel, BusinessTravel, OverTime, NumCompaniesWorked, EmployeeNumber, StandardHours
3. **Compensation**: HourlyRate, DailyRate, MonthlyRate, MonthlyIncome, PercentSalaryHike, StockOptionLevel
4. **Tenure**: TotalWorkingYears, YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion, YearsWithCurrManager, TrainingTimesLastYear
5. **Satisfaction**: Input received from anonymous survey conducted internally to measure EnvironmentSatisfaction, JobSatisfaction, JobInvolvement, RelationshipSatisfaction, WorkLifeBalance

## Analysis of the steps performed

The company’s organizational structure was examined, operating across three key macro-processes (departments):
- Research & Development (R&D): The technical unit responsible for creating intellectual property and developing products.
- Sales: The commercial unit focused on revenue generation and client base retention.
- Human Resources (HR): The support function responsible for personnel administration and staff development.

![alt text](<Page 2 Overview.png>)

## Audit of parameters pertaining to data collection

### Job Parameters

![alt text](<Page 3 Job Parameter Analysis.png>)

**Overtime patterns**: 

Among the 416 employees reporting workplace burnout, 127 (30.5%) exited the organization. In contrast, the turnover rate among employees without burnout concerns is significantly lower at 10.4%. This highlights a strong correlation between burnout and attrition risk. 

The findings reinforce the established burnout hypothesis: employees working overtime resign nearly three times more frequently than those adhering to regular schedules. Specifically, turnover among specialists with overtime workloads is 30.5%, compared to just 10.5% for those maintaining balanced hours.

 **Job level & Job Role**: 
 
 Attrition is disproportionately concentrated at the Entry and Junior levels, accounting for 82.3% of total separations. This trend is particularly concerning, as employees at these levels are gaining skills and hands-on experience before leaving, resulting in repeated investments in recruitment, training, onboarding, and associated opportunity costs. 
 
 Elevated attrition is also observed in specific roles, including Sales Executive, Research Scientist, Laboratory Technician, and HR Executive, indicating role-specific retention challenges.

### Compensation 

![alt text](<Page 4 Comp Analysis.png>)

Attrition driven by financial considerations is most pronounced within the Research & Development function, where turnover remains elevated despite the presence of higher‑income outliers.

In contrast, the Sales and Human Resources departments exhibit the opposite trend: employees with higher monthly incomes demonstrate stronger retention, while attrition is concentrated among those with lower daily rates and monthly earnings.

This pattern underscores the existence of a critical salary threshold. Employees earning below this level are more likely to disengage, experience demotivation, and ultimately exit the organization, whereas those above the threshold show greater stability and commitment.

### Survey Result 

![alt text](<Page 5 Survey Result Analysis.png>)

**Job Satisfaction, Environment Satisfaction and Work-life Balance** 

Despite high levels of job satisfaction, environment satisfaction, and positive work-life balance, attrition persists. A deeper review reveals that satisfaction trends in the HR department follow similar trajectories, whereas the R&D and Sales departments display divergent patterns among these parameters.

Overall, work-life balance ratings are favorable, with 84.2% of employees reporting Good to Better outcomes. Additionally, 60.3% of employees express High to Very High satisfaction with their current manager, and the same proportion report satisfaction with their most recent promotion.

Long periods since last promotion strongly predict imminent departure

Extended time with same manager without growth signals disengagement


### Personal Parameters

![alt text](<Page 6 Personal Parameter Analysis-1.png>)

**Commutation**: Attrition is notably higher among employees commuting long distances (>6 km daily), with 63.3% citing this as a reason for leaving.

**Education Background**: Employees with educational backgrounds in Medical and Life Sciences exhibit higher turnover compared to other fields.

**Marital status also influences attrition**: single employees demonstrate a greater tendency to resign compared to their married or divorced counterparts.

### Employee Tenure
![alt text](<Page 7 Tenure Analysis.png>)

**Employee Experience & Retention Insight**

Employees with limited external exposure—specifically those who have not worked with more than one organization—demonstrate a higher tendency to leave compared to employees with experience across three or more companies. This trend suggests that the organization offers a genuinely strong work-life balance and other favorable conditions, enabling it to establish a competitive advantage within the industry.


### Attrition by Business Travel and Performance Rating

![alt text](<Page 8 Business Travel and Perofmance Rating.png>)

**Performance Rating**: Employees with an ‘Excellent’ performance rating exhibit a higher propensity to leave the organization, and this trend is consistently observed across all departments.

**Business Travel**:In terms of business travel, the highest turnover is recorded among employees who travel infrequently. This pattern is also evident across departments, suggesting that limited travel engagement may correlate with increased attrition risk.

### % Salary Hike
![alt text](<Page 9 Salary Hike.png>)

Employees who received the least % salary hike (11-15%) left the organization than the ones who received more salary hike.

## Three strategic pillars for the path forward
1 Stabilize — Stop the bleed
- Conduct immediate stay interviews in high-attrition departments
- Audit Over-Time distribution and enforce sustainable limits
- Fast-track compensation review for below-market income bands
- Identify top-10 flight-risk employees using data model signals
- Introduce a 30-day check-in cadence for early-tenure employees
- Launch emergency engagement pulse survey in red-flag departments

2 Strengthen — Build retention infrastructure
- Design transparent career ladder with clear promotion criteria per level
- Introduce structured manager effectiveness reviews (360°)
- Benchmark pay against market and close gaps within 2 salary cycles
- Launch a work-life balance initiative — flexible hours, hybrid policy
- Formalise education field–role alignment in hiring to reduce mismatch exits
- Create job rotation opportunities for stagnant mid-level employees

3 Sustain — Build a predictive talent culture
- Embed attrition prediction model into quarterly HR reviews
- Establish bi-annual employee satisfaction survey with dept-level reporting
- Tie manager KPIs to team retention and satisfaction scores
- Create a "High Risk Cohort" watch-list updated from live Power BI data
- Build leadership development track to reduce promotion bottlenecks
- Report attrition metrics at board level on a quarterly basis



