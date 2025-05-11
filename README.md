# COVID-19 Data Analysis Project

A comprehensive analysis of COVID-19 data across Kenya, the United States, and India, examining trends in cases, deaths, and vaccination rates using data from Our World in Data (OWID).

## Project Objectives

- Analyze and visualize COVID-19 case trends across selected countries
- Compare mortality rates and total deaths between nations
- Track vaccination progress and coverage across different regions
- Identify patterns and anomalies in COVID-19 data
- Calculate and visualize weekly averages of new cases

## Tools and Libraries Used

- Python 3.x
- Pandas - For data manipulation and analysis
- Matplotlib - For creating static visualizations
- Seaborn - For enhanced statistical visualizations
- Jupyter Notebook - For interactive data analysis

## How to Run/View the Project

1. Ensure you have Python installed with the required libraries
2. Clone this repository
3. Download the OWID COVID-19 dataset (owid-covid-data.csv)
4. Open the Jupyter Notebook (owid-covid-data.ipynb)
5. Run the cells sequentially to see the analysis and visualizations

## Key Insights and Findings

### Major Trends
- United States showed the highest COVID-19 cases and deaths over time, followed by India and Kenya
- The United States led in vaccination rollout speed and coverage
- India experienced a significant surge in cases during mid-2021 (Delta variant period)

### Vaccination Progress
- United States achieved over 65% full vaccination coverage
- Kenya showed slower vaccination progress (~25% coverage)
- India demonstrated steady improvement in vaccination rates over time

### Data Patterns and Anomalies
- Vaccination rates correlate with reduced case trends
- Some countries showed periodic data reporting gaps
- Weekly averaging helped smooth out daily reporting fluctuations

### Methodological Notes
- Missing values were handled through linear interpolation
- Seven-day averages were used to smooth daily case variations
- Data visualization focused on key metrics: total cases, deaths, and vaccination rates