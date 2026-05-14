Job Salary Prediction Dashboard and Analysis
1. Project Overview
The Job Salary Prediction Dashboard project is designed to analyze job-related salary data and identify meaningful patterns, trends, and relationships within the dataset. The project helps users understand salary distribution, industry trends, and factors influencing salaries through data visualization and reporting. The dashboard provides visual insights using charts and graphs, enabling easier decision-making for businesses, recruiters, and analysts.
2. Project Objectives
•	Analyze salary-related datasets
•	Identify trends and salary patterns
•	Detect anomalies and correlations
•	Visualize data using dashboards
•	Generate insights for business decisions
•	Provide recommendations based on analysis

3. Technologies Used
Technology	Purpose
Python	Data analysis and processing
Pandas	Data manipulation
Matplotlib	Data visualization
Power BI / Desktop	Interactive dashboard development and slicer creation
CSV Dataset	Source data
PDF Report	Documentation and reporting

4. Dataset Description
The dataset contains job and salary-related information used for prediction and analysis.
•	Job categories and specific titles (e.g., AI Engineer, Data Analyst)
•	Salary details (e.g., maximum salary, total salary spend, average salary)
•	Industry information (e.g., Finance, Consulting, Education)
•	Experience metrics (measured in total experience years)
•	Numerical and categorical workforce variables

5. Data Processing Steps
1.	Imported dataset from CSV file.
2.	Removed duplicate records to prevent skewed metrics.
3.	Identified numeric columns (salaries, years) and categorical columns (industries, titles).
4.	Cleaned missing or inconsistent data across fields.
5.	Prepared data for visualization and dashboard integration.


6. Dashboard Components
Page 1: Overview Dashboard
The Overview Dashboard establishes the baseline scale of the organization, breaking down broad operational metrics across fields, industries, and overall educational experience distributions.

<img width="975" height="544" alt="image" src="https://github.com/user-attachments/assets/df122bd5-3fe0-4332-ac0c-179f56296a33" />

 
•	KPI Metrics Cards: Displays structural operational volume including a 250K total corporate record count, a 36bn global cumulative salary spend, and a 333K peak salary ceiling.
•	Sum of Salary by Industry (Horizontal Bar Chart): Tracks total spending allocations across core economic sectors. The visual reveals a perfectly uniform distribution near 4bn per sector across Finance, Consulting, Media, Manufacturing, Education, Technology, Healthcare, and Telecom.
•	Sum of Experience Years by Education Level (Pie Chart): Breaks down workforce tenure volume by academic background. It shows an almost exact, equal split of roughly 20% per tier across five segments: Master (20.08%), High School (20.03%), Bachelor (20.01%), Diploma (19.94%), and PhD (19.94%).
•	Industry Segment Slicer: Located on the left side, this interactive filter menu allows users to filter the entire view by single or multiple industries like Consulting, Education, Finance, and Government.

Page 2: Salary Analysis Dashboard
The Salary Analysis Dashboard explores deeper, granular correlations, tracing individual job titles, average pay rates, and dense cross-sections of employee experience against direct salary bands.

 <img width="975" height="558" alt="image" src="https://github.com/user-attachments/assets/f0c2cba1-bd77-4629-afc6-dcd899740011" />

•	Salary Analysis by Job Title (Vertical Bar Chart): Compares cumulative salary budgets by roles. Specialized technical tracks lead the chart, with AI Engineers and Machine Learning Engineers capturing peak spending, while Data Analysts sit at the baseline.
•	Employee Count by Experience (Dual Axis Line Chart): Plots structural financial growth against talent volume. Total cumulative salary spending (dark line) climbs smoothly over experience years, while active employee counts (blue line) show sharp volatility, spiking heavily at 13 years and 18 years of tenure.
•	Average of Salary by Experience Years (Summary Card): Acts as a central baseline anchor displaying a global average salary of 173.18K alongside an rising visual trend vector.
•	Count of Company Size by Job Title, Experience, and Salary (Scatter Plot Matrix): A dense cluster mapping individual salaries from 0 to 20 years of experience. The plot highlights a definitive concentration ceiling where the vast majority of workforce coordinates rest under the 0.3M (300K) threshold.
•	Central Filtering Slicers: A dual control panel containing an interactive dual-node Salary Range Slider (filtering values from 31,867 to 333,046) and a sequential vertical checklist for tracking specific Experience Years (0 to 9+).
7. Key Findings
•	Insight 1: Salary values vary significantly across roles, with specialized technical tracks like AI Engineering commanding vastly superior funding compared to standard analytical tracks.
•	Insight 2: Certain job categories appear more frequently and maintain stable talent pools, suggesting high industry demand and mature recruitment pipelines.
•	Insight 3: Correlation analysis reveals that while cumulative salary spend scales predictably with experience years, individual salary distribution contains high variance within the same experience brackets.
•	Insight 4: The highly uniform distribution across education tiers and industry sectors indicates uniform sampling or synthetic properties within the source dataset.
•	
8. Business Recommendations
•	Use salary analysis for market-accurate compensation benchmarking during hiring.
•	Focus recruitment and retention efforts on high-demand categories like AI and Machine Learning.
•	Investigate salary distribution variances within specific experience brackets to optimize payroll allocation.
•	Utilize identified experience-to-salary correlations to build predictive hiring models and budget strategies.
•	

9. Final Story with Dashboard
The dashboard provides a complete overview of the salary dataset through charts and analytical insights. By combining salary distribution, category analysis, and correlation visualization, the project helps businesses understand workforce trends and make informed decisions regarding hiring, compensation, and planning. The project demonstrates how data analytics and dashboards can transform raw data into meaningful business intelligence.
10. Conclusion
The Job Salary Prediction Dashboard successfully analyzes salary-related data and presents valuable insights through visualizations and reports. The project improves understanding of salary trends and supports better strategic decision-making using data-driven analysis.
________________________________________
