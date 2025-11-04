# Cyclistic Bike-Share Case Study

## Project Overview
This comprehensive case study analyzes Cyclistic bike-share data to understand usage patterns between annual members and casual riders. The goal is to develop data-driven marketing strategies to convert casual riders into annual members, maximizing long-term growth and profitability.

## Business Context
Cyclistic is a fictional bike-share company in Chicago with 5,824 bikes across 692 stations. The company offers flexible pricing: single-ride passes, full-day passes, and annual memberships. Annual members are more profitable, and the marketing team believes converting casual riders presents the greatest growth opportunity.

## Project Structure

### 📋 Documentation Files
- **[scenario.md](scenario.md)**: Company background, business task, and key questions
- **[cyclistic-case.md](cyclistic-case.md)**: Complete case study following the 6 data analysis phases (Ask, Prepare, Process, Analyze, Share, Act)
- **[cases.md](cases.md)**: Detailed business questions, hypotheses, and strategic implications
- **[cyclistic-datasets.md](cyclistic-datasets.md)**: Comprehensive data source descriptions and preparation details
- **[observation.md](observation.md)**: Key insights and findings from data analysis
- **[instructions.md](instructions.md)**: Step-by-step guide for data querying and preparation

### 🔍 SQL Queries
- **[entire_year_query.sql](entire_year_query.sql)**: BigQuery SQL to create summary table for full year analysis
- **[summer_query.sql](summer_query.sql)**: BigQuery SQL focused on summer months (July-September) trends

## Key Business Questions
1. **How do annual members and casual riders use Cyclistic bikes differently?**
2. **Why would casual riders buy Cyclistic annual memberships?**
3. **How can Cyclistic use digital media to influence casual riders to become members?**

## Data Analysis Process

### Phase 1: Ask
- Defined business task and key stakeholders
- Established clear success criteria

### Phase 2: Prepare
- Identified data sources (Cyclistic trip data, weather, geographic boundaries)
- Assessed data credibility and limitations

### Phase 3: Process
- Cleaned and transformed raw data
- Handled missing values and data inconsistencies
- Created derived metrics (trip duration, day of week, etc.)

### Phase 4: Analyze
- Conducted descriptive and comparative analysis
- Identified patterns in usage, geography, and seasonality
- Quantified differences between user types

### Phase 5: Share
- Created visualizations in Tableau
- Developed compelling data narrative
- Presented findings to stakeholders

### Phase 6: Act
- Provided actionable recommendations
- Outlined implementation strategy
- Defined success metrics and next steps

## Key Findings

### Usage Patterns
- **Members**: Consistent weekday commuting (7-9 AM, 5-7 PM), shorter trips (12-15 min)
- **Casual Riders**: Weekend leisure usage, longer trips (25-30 min), peak in summer

### Strategic Insights
- Members generate 3x more revenue per user than casual riders
- 30% of casual riders show conversion potential
- Summer months drive 50% of casual rider revenue

## Recommendations

### 1. Seasonal Marketing Campaigns
Launch targeted campaigns during summer months with limited-time membership offers to reduce perceived commitment.

### 2. Digital Engagement Strategy
Utilize app notifications and email marketing to highlight cost savings and member benefits for frequent users.

### 3. Flexible Pricing Options
Introduce 6-month memberships and pause/resume features to address commitment concerns.

### 4. Partnership Development
Collaborate with local businesses and events to offer exclusive member perks.

## Technical Implementation

### Data Sources
- **Primary**: Cyclistic trip data (3.8M rides, April 2019 - March 2020)
- **Weather**: NOAA GSOD data (temperature, wind, precipitation)
- **Geographic**: US zip code boundaries and neighborhood data

### Tools Used
- **BigQuery**: Data querying and aggregation
- **SQL**: Complex joins and transformations
- **Tableau**: Data visualization and dashboard creation

### Data Processing Steps
1. Execute entire year and summer queries in BigQuery
2. Download results as CSV files
3. Import into Tableau for visualization
4. Create interactive dashboards with key insights

## File Execution Instructions

### Prerequisites
- Google Cloud Platform account with BigQuery access
- Uploaded zip code reference table
- Tableau Desktop or Public for visualization

### Steps
1. **Data Querying**: Run `entire_year_query.sql` and `summer_query.sql` in BigQuery
2. **Data Download**: Save results as CSV files
3. **Visualization**: Import CSVs into Tableau and create dashboard
4. **Analysis**: Review findings in `observation.md`
5. **Presentation**: Use complete case study for stakeholder presentation

## Project Deliverables
- ✅ Complete case study documentation
- ✅ Executable SQL queries for data extraction
- ✅ Data preparation and validation instructions
- ✅ Key insights and strategic recommendations
- ✅ Ready-to-use Tableau dashboard foundation

## Impact and Value
This analysis provides Cyclistic with:
- Data-driven understanding of user behavior
- Targeted marketing strategies for member conversion
- Foundation for measuring campaign effectiveness
- Framework for ongoing data analysis and optimization

## Contact and Attribution
This case study is part of the Google Data Analytics Professional Certificate capstone project. All data sources, methodologies, and findings are presented for educational and professional development purposes.

---
*Prepared as a comprehensive demonstration of end-to-end data analysis skills, from business understanding through actionable recommendations.*
