# Stack-Overflow-Developer-Survey
# Stack Overflow Developer Survey – Data Analyst Capstone Project

**Author:** Shrikishan B  
**Program:** IBM Data Analyst Professional Certificate  
**Project Type:** Data Analytics Capstone Project

---

## 1. Project Overview

This project analyzes Stack Overflow Developer Survey data to identify trends in programming languages, databases, cloud platforms, web frameworks, developer demographics, and technology preferences.

The analysis also examines job posting distribution across selected cities and average annual salaries associated with different programming languages.

The primary objective is to transform raw datasets into meaningful insights using Python, Pandas, SQL, data visualization, and IBM Cognos Analytics.

## 2. Project Objectives

- Analyze current and future programming language preferences.
- Identify popular database technologies and emerging trends.
- Examine job posting distribution across selected locations.
- Compare average annual salaries across programming languages.
- Analyze developer demographics, education, and employment status.
- Develop interactive dashboards to communicate analytical findings.

## 3. Tools and Technologies

| Technology | Purpose |
|---|---|
| Python | Data processing and analysis |
| Pandas | Data cleaning and manipulation |
| SQL / SQLite | Data querying and analysis |
| IBM Cognos Analytics | Dashboard development |
| Jupyter Notebook | Exploratory data analysis |
| APIs and Web Scraping | Data collection |

## 4. Project Methodology

The project follows an end-to-end data analytics workflow.

1. **Data Collection:** Collected datasets using APIs, web scraping activities, and course-provided resources.
2. **Data Wrangling:** Identified and handled missing values, duplicate records, and inconsistent data.
3. **Exploratory Data Analysis:** Examined distributions, patterns, and relationships within the datasets.
4. **SQL Analysis:** Used SQL/SQLite queries to retrieve and analyze structured information.
5. **Data Visualization:** Created charts to identify trends and compare results.
6. **Dashboard Development:** Built interactive dashboards using IBM Cognos Analytics.
7. **Interpretation:** Translated analytical results into meaningful findings and implications.

---

## 5. Key Analysis and Numerical Findings

### 5.1 Job Market Analysis – Job Postings by Location

The analysis examined job posting counts across seven selected locations.

| Location | Number of Job Postings |
|---|---:|
| Washington DC | 5,316 |
| Detroit | 3,945 |
| Seattle | 3,375 |
| New York | 3,226 |
| Los Angeles | 640 |
| San Francisco | 435 |
| Austin | 434 |

**Key Insights:**

- Washington DC recorded the highest number of job postings (5,316).
- Detroit ranked second with 3,945 postings.
- Seattle recorded 3,375 postings.
- Austin had the lowest number among the analyzed locations, with 434 postings.

### 5.2 Programming Language Analysis – Current Usage

The following table presents the top 10 programming languages based on respondent counts.

| Rank | Programming Language | Respondents |
|---:|---|---:|
| 1 | JavaScript | 37,492 |
| 2 | HTML/CSS | 31,816 |
| 3 | Python | 30,719 |
| 4 | SQL | 30,682 |
| 5 | TypeScript | 23,150 |
| 6 | Bash/Shell | 20,412 |
| 7 | Java | 18,239 |
| 8 | C# | 16,318 |
| 9 | C++ | 13,827 |
| 10 | C | 12,184 |

**Key Insights:**

- JavaScript leads current usage with 37,492 respondents.
- HTML/CSS ranks second with 31,816 respondents.
- Python ranks third with 30,719 respondents.
- SQL also demonstrates strong representation with 30,682 respondents.

### 5.3 Programming Language Analysis – Future Preferences

The analysis also examined the programming languages developers prefer to work with in the future.

| Rank | Programming Language | Respondents |
|---:|---|---:|
| 1 | Python | 25,047 |
| 2 | JavaScript | 23,774 |
| 3 | SQL | 22,400 |
| 4 | HTML/CSS | 20,721 |
| 5 | TypeScript | 20,239 |
| 6 | Rust | 17,232 |
| 7 | Go | 13,837 |
| 8 | Bash/Shell | 13,744 |
| 9 | C# | 12,921 |
| 10 | C++ | 10,873 |

**Key Insights:**

- Python moves from third position in current usage to first position in future preference.
- JavaScript remains among the leading programming languages.
- Rust and Go enter the future top 10.
- Java and C are no longer represented in the future top 10.

**Analytical Implication:** Python, JavaScript, and SQL demonstrate strong relevance in developer preferences, while Rust and Go indicate growing interest in additional programming technologies.

### 5.4 Database Analysis – Current vs Future Preferences

| Database | Current Usage | Future Preference |
|---|---:|---:|
| PostgreSQL | 25,536 | 24,005 |
| MySQL | 21,099 | 12,269 |
| SQLite | 17,365 | 13,489 |
| Microsoft SQL Server | 13,275 | 7,905 |
| MongoDB | 13,007 | 10,982 |

**Key Insights:**

- PostgreSQL maintains the first position in both current usage and future preference.
- SQLite moves from third to second position.
- MySQL moves from second to third position.
- Supabase enters the future top 10, while Oracle drops out.

**Analytical Implication:** PostgreSQL continues to demonstrate strong developer preference, while changing rankings indicate evolving database technology interests.

### 5.5 Average Annual Salary Analysis

The following results compare average annual salaries across the top 10 programming languages in the analyzed dataset.

| Programming Language | Average Annual Salary |
|---|---:|
| Swift | 130,801 |
| Python | 114,383 |
| C++ | 113,865 |
| JavaScript | 110,981 |
| Java | 101,013 |
| Go | 94,082 |
| R | 92,037 |
| C# | 88,726 |
| SQL | 84,793 |
| PHP | 84,727 |

**Key Insights:**

- Swift recorded the highest average annual salary at 130,801.
- Python ranked second at 114,383.
- C++ and JavaScript also recorded average salaries above 110,000.
- PHP recorded the lowest average salary among the ten languages analyzed.

*Note: The original presentation does not explicitly specify the currency or salary period beyond annual salary.*

### 5.6 Developer Demographics

The demographic analysis examined respondents across age groups, countries, education levels, and employment status.

**Key Findings:**

- The largest age groups were 35–44 and 45–54 years.
- The United States represented the largest respondent base.
- Bachelor's degree holders formed the largest education group.
- Full-time employees represented the largest employment group.

---

## 6. Interactive Dashboard Development

Three dashboard sections were developed using IBM Cognos Analytics.

### Dashboard 1 – Current Technology Usage

Examines:
- Top 10 programming languages.
- Database technologies.
- Cloud platforms.
- Web frameworks.

### Dashboard 2 – Future Technology Trends

Examines:
- Future programming language preferences.
- Future database preferences.
- Cloud platform preferences.
- Future web framework trends.

### Dashboard 3 – Developer Demographics

Examines:
- Respondent age distribution.
- Country-wise respondent distribution.
- Formal education levels.
- Employment status.

---

## 7. Overall Findings and Business Implications

| Analysis Area | Major Finding | Implication |
|---|---|---|
| Job Market | Washington DC leads with 5,316 postings. | Location-based job market analysis can help identify opportunities. |
| Programming Languages | Python ranks first in future preferences. | Python skills remain relevant for future development opportunities. |
| Databases | PostgreSQL leads current and future preferences. | Database skills remain important for developers. |
| Salary Analysis | Swift records the highest average salary. | Programming language specialization may be associated with salary differences. |
| Demographics | Respondents are concentrated in working-age groups. | Demographic analysis helps understand survey participation patterns. |

## 8. Project Outcomes

Through this project, the following analytical capabilities were demonstrated:

- Data collection and preprocessing.
- Data cleaning and manipulation using Python and Pandas.
- Exploratory data analysis.
- SQL-based data querying.
- Data visualization and interpretation.
- Interactive dashboard development.
- Analytical reporting and insight generation.

## 9. Conclusion

This capstone project demonstrates an end-to-end data analytics workflow, covering data collection, data preparation, exploratory analysis, SQL querying, visualization, and interactive dashboard development.

The analysis identified important trends in programming language preferences, database technologies, job postings, salary comparisons, and developer demographics.

The findings highlight Python and PostgreSQL as leading technologies in future preferences and demonstrate how data analytics can transform raw information into meaningful insights for informed decision-making.

---

**Project completed as part of the IBM Data Analyst Professional Certificate on Coursera.**
