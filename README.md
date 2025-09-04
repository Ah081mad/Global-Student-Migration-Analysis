# Global-Student-Migration-Analysis

## Statement of the Problem
In recent years, international student migration has become a critical aspect of global education and workforce mobility. However, universities, governments, and policymakers face challenges in understanding student migration trends, financial support distribution, and post-graduation outcomes. Without clear insights, it is difficult to design policies that ensure equal access to scholarships, improve student employability, and align education with labor market demands.
This project seeks to analyze patterns in student migration using real-world-like data to uncover who migrates, what they study, how they fund their education, and their eventual career outcomes.

## Tools Used
- Power BI
- Power Query
- DAX

## Dataset
The dataset includes records of Student ID, Origin country, Destination country, Destination city, University name, Course name, Field of study, Year of enrollment, Scholarship received, Enrollment reason, Graduation year, Placement status, Placement country, Placement company, Starting salary, GPA, Visa status, Post-graduation visa, Language proficiency test, Test score.

## Data Preparation and Cleaning Process
To ensure accuracy and usability, the data went through several preparation stages:

1.Data Importation: The dataset was loaded into Power BI for visualization after initial inspection.

2.Data Cleaning (using Power Query):

- Removed duplicate records of student IDs to avoid over-counting.
- Standardized categorical fields (e.g., “Yes/No” for scholarships, consistent capitalization in country names).
- Handled missing values by replacing nulls in numeric fields with averages and flagging incomplete categorical records.
- Converted date columns into a usable Year format for time-based trend analysis.
- Ensured GPA scores and salary figures were in correct numeric types for aggregation.

## Key Questions Explored
The dashboard was built to answer the following critical questions:
- What is the trend of student migration over time?
- Which fields of study attract the highest number of migrating students?
- How is scholarship support distributed among students?
- What is the employment outcome of migrating students?
- Is there a relationship between GPA, field of study, and starting salary?
  
## Key Insights
1. Overall Student Migration
The dataset tracks over 2 million students who migrated globally for studies.
Canada stands out as both a top origin and destination country, suggesting strong student mobility with Canada at the center.

2. Enrollment Trends
- Enrollment peaked in 2022, followed by a noticeable decline in 2023.
- This trend may reflect global events (e.g., COVID-19 travel restrictions) or changing migration policies.

3. Scholarships & Access
- A majority of students did not receive scholarships.
- Fields like Medicine, Law, and Engineering show higher scholarship allocation compared to Arts and Social Sciences, highlighting unequal access across disciplines.

4. Placement Outcomes
- Just over 49% of students remain “Not placed” after graduation, while 51% secure placements.
- The UK, India, Russia, and UAE emerge as top placement destinations, with notable numbers also in Canada and Germany.
- This shows global demand for graduates, but also a quarter of students face employability challenges.

5. ROI: GPA, Salary, and Field of Study
- The scatter plot trendline confirms a positive correlation: higher GPA → higher average starting salary.
- However, field of study is the strongest driver of salary differences.
- Medicine, Law, and Engineering graduates earn well above the trendline, showing strong labor market demand.
- Arts and Social Sciences graduates earn below the trendline, indicating lower salary outcomes despite similar GPAs.
Employers prioritize field of study over small GPA variations in determining salary levels.

## Recommendations
Based on the insights, the following recommendations are proposed:
- Scholarship Equity: Expand scholarship opportunities to underfunded disciplines such as Arts and Social Sciences to promote inclusivity and balanced talent development.
- Career Placement Support: Strengthen university-industry linkages and post-study work visa policies to reduce the 49% unemployment gap among international graduates.
- Policy Guidance for Students: Provide early career counseling to help students align their chosen field of study with labor market demand and earning potential.
- Monitoring Migration Trends: Track annual migration fluctuations to anticipate the effects of global crises, immigration laws, and education reforms on student movement.
- Data-Driven Education Planning: Governments and institutions should use such analyses to forecast skills shortages and strategically invest in disciplines critical for economic growth.
 

