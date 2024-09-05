# COVID-19 Power BI Dashboard

This repository contains a **Power BI template file (`.pbit`)** that visualizes global COVID-19 data from 2020 to 2022. The dashboard provides an interactive overview of key metrics such as positive cases, deaths, and mortality rates by country, enabling users to explore the global impact of the pandemic.

## Introduction

The COVID-19 pandemic has profoundly affected countries worldwide, and data became one of the most critical tools in understanding the spread and severity of the virus. I created this dashboard to:

- Gain a clearer understanding of how the pandemic evolved across different countries and regions.
- Visualize trends in positive cases, deaths, and mortality rates to see how different countries handled the crisis.
- Create a tool that could serve as a resource for comparing country-specific statistics in an easy-to-understand, visual format.

By exploring these visualizations, I aimed to not only understand the raw numbers but also derive insights into the countries that faced the most challenges during the pandemic. The dashboard provides a global perspective while allowing users to dive into specific regions or timeframes of interest.

### Key Insights and Interesting Findings

While working on this dashboard, a few things stood out:

- **Countries with the Highest Mortality Rates**: One of the interesting insights was seeing how mortality rates varied widely between countries, even among those with similar case counts. This sparked curiosity about the healthcare infrastructure, population demographics, and other factors that might explain these differences.
- **Time Trends**: The time series visualizations reveal stark differences in the pandemic’s progression, with some countries experiencing sharp peaks in cases and deaths, while others had more gradual increases.
- **Global Hotspots**: The map visualization provided a clear view of the global hotspots where the virus was most rampant, offering a quick glance at regions with the highest concentration of positive cases.

## Dashboard Features

1. **Max Positive Cases and Deaths**:
   - **Max Positive Cases**: Shows the highest number of positive cases reported on a single day.
   - **Max Death Cases**: Displays the maximum number of deaths recorded on the most fatal day.

2. **Time Series of Cases and Deaths**:
   - Line chart visualizing the count of positive cases and deaths over time, helping users track the progression of the pandemic.

3. **Country Comparison**:
   - **Top 10 Countries by Deaths**: A pie chart that highlights the countries with the highest death counts.
   - **Positive Cases by Country**: A bar chart comparing the number of positive cases across countries.
   - **Mortality Rates**: A bar chart showing the countries with the highest mortality rates (deaths as a percentage of positive cases).

4. **Global Map**:
   - A map visualization of COVID-19 positive cases, with bubble sizes representing the number of cases per country.

## How to Use the Template

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/covid-19-dashboard.git
2. **Open the Template in Power BI**:
   - Open the `.pbit` file in Power BI Desktop. This is a template file, so you will need to provide your own data source when opening it.

3. **Connect to Your Data**:
   -Provide the downloaded dataset file (covid19_dataset.csv) to populate the dashboard with data.

4. **Explore the Dashboard**:
   - The dashboard features several interactive elements:
     - **Filter by country**: Use the country filter on the left panel to focus on specific regions.
     - **Examine trends**: Use the line charts and bar charts to explore how cases and deaths evolved over time.
     - **Global analysis**: Use the map visualization to get an at-a-glance view of the countries most affected by the pandemic.

## Limitations

This template provides a general overview of COVID-19 case and death statistics. It does not include:

- Vaccination data.
- Recovery rates.
- More granular regional breakdowns within countries.

The dashboard focuses on high-level trends rather than providing detailed country-specific analysis.

## Future Improvements

Potential enhancements for future iterations of the dashboard include:

- Adding **vaccination data** to show the relationship between vaccination rates and case/death reduction.
- Including **recovery data** to provide a more complete picture of the pandemic.
- Integrating a **regional breakdown** within larger countries to see differences in how different areas were affected.

