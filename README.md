📊 Regional Desirability Dashboard – Providence County Analysis

📁 Project Overview
* **Objective:** Create a dashboard measuring county desirability and suitability
* **Region:** Providence County, Rhode Island
* **Coverage:** 33 zip codes
* **Dashboard:** [Interactive Tableau Visualization](https://public.tableau.com/app/profile/udhay.chityala/viz/UdhayChityalaDashboatrd/DashboardProvidence)

🗺️ Data Sources
* **U.S. Census Bureau:** 2022 American Community Survey 5-Year Estimates
* **Population Density Dataset:** FourFront Analytics
* **Variables Collected:**
   * Population & Density metrics
   * Education attainment levels
   * Healthcare coverage statistics
   * Business establishments
   * Income & Employment data

📐 Composite Score Methodology
| Variable | Weight | Relationship | Rationale |
|----------|---------|--------------|-----------|
| **Population Density** | 10% | Inverse | Lower density = Higher desirability |
| **Median Household Income** | 20% | Direct | Higher income = Better quality of life |
| **Education (Bachelor's+)** | 20% | Direct | More education = Economic opportunity |
| **Employment Rate** | 20% | Direct | Higher employment = Economic stability |
| **Total Employer Establishments** | 10% | Direct | More businesses = Job opportunities |
| **Without Healthcare Coverage** | 20% | Inverse | Less uninsured = Better health access |

🔧 Technical Implementation
* **Normalization:** Min-Max scaling (0-1 range)
* **Inversion Logic:** Applied to negative indicators
* **Score Calculation:** Weighted sum of normalized values
* **Visualization Platform:** Tableau Public
* **Interactivity:** Dynamic filtering by zip code

📈 Key Features
* **Geographic Mapping:** Visual representation of desirability scores
* **Multi-dimensional Analysis:** Six key socioeconomic factors
* **Comparative Views:** Zip code rankings and comparisons
* **Data Transparency:** All metrics visible for each region
* **Real-time Updates:** Connected to latest census data

🎯 Dashboard Capabilities
* **Score Distribution:** Identify high/low desirability areas
* **Factor Analysis:** Understand which variables drive scores
* **Trend Identification:** Spot patterns across the county
* **Decision Support:** Aid in location selection decisions
* **Policy Insights:** Highlight areas needing intervention

🧰 Technology Stack
* **Data Processing:** Python/Excel for preprocessing
* **Visualization:** Tableau Desktop/Public
* **Data Sources:** Census API, Public datasets
* **Statistical Methods:** Min-Max normalization, weighted scoring
* **Deployment:** Tableau Public cloud hosting

✅ Project Achievements
* Successfully integrated multiple socioeconomic indicators
* Created intuitive composite scoring methodology
* Developed interactive dashboard for public access
* Balanced positive and negative factors appropriately
* Provided actionable insights for regional planning

🚀 Future Enhancements
* **Time Series Analysis:** Track changes over multiple years
* **Additional Metrics:** Crime rates, school quality, amenities
* **Predictive Modeling:** Forecast future desirability trends
* **Comparison Tool:** Compare with other counties/states
* **API Integration:** Real-time data updates
* **Mobile Optimization:** Responsive design for all devices
