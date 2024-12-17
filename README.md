# Project Team 18: Public Transportation  
*COSI 116A - Information Visualization, Fall 2024*  

**Team Members**:  
- Jason Chen  
- Capo Wang  
- Tri Phan  
- Isaac Zygmuntowicz  

**Instructor**: Prof. Dylan Cashman  
**Course**: Brandeis University, COSI 116A  

---

## Motivation  

After the global COVID-19 pandemic, people's habits and economic activities changed drastically. Public transportation was one of the most affected sectors due to social distancing and safety measures.  

This project visualizes **New York State public transportation data** from **March 2020 to October 2024**. Our work explores:  
- The decline and recovery of public transportation usage.  
- The impact of COVID-19 cases on ridership trends.  
- Spatial patterns of subway ridership across New York City.  

The project provides insights for government agencies and public transportation offices to better understand usage trends and plan future developments.

---

## Visualizations  

Our final visualization combines three interactive visualizations:  

1. **Heat Map**  
   - Displays subway ridership trends across different stations in New York City over time.  
   - Users can hover over stations to view detailed data.  

2. **Line Chart**  
   - Shows the overall public transportation ridership and COVID-19 cases over time.  
   - Supports brushing and filtering to explore trends for specific periods.  

3. **Bar Chart**  
   - Compares different public transportation types as a percentage of pre-COVID ridership.  
   - Allows users to filter the line chart by selecting transportation types.  

Together, these visualizations provide an interactive and comprehensive view of public transportation trends.

---

## Design Process  

Our project went through multiple iterations to ensure clarity and interactivity:

- **Initial Goals**:  
   - Show public transportation trends over time.  
   - Visualize spatial subway ridership patterns.

- **Challenges**:  
   - Handling and cleaning large datasets.  
   - Designing visualizations that balance clarity and detail.  

- **Decisions**:  
   - The **line chart** captures overall trends and integrates COVID-19 data to show correlations.  
   - The **bar chart** highlights recovery across different transportation types compared to pre-COVID levels.  
   - The **heat map** focuses on subway ridership due to its dominance and clear spatial representation.  

Each visualization was designed to complement the others, enabling deeper exploration through interactive brushing, filtering, and highlighting.  

---

## GitHub Pages  

The project is published on GitHub Pages. Access the live visualization here:  

[https://cosi116a-brandeis-infovis-fall23.github.io/cosi-116a-f24-final-project-repository-Asurazpr/](https://cosi116a-brandeis-infovis-fall23.github.io/cosi-116a-f24-final-project-repository-Asurazpr/)

## Data Sources  

The project uses the following datasets:  

- **Subway Ridership Data**:  
   - Combines early 2020 Turnstile data with later subway ridership records.  
   - Data processing included standardizing station names and merging datasets for consistency.  

- **MTA Daily Ridership Data**:  
   - Provides daily ridership counts for various transportation types (Subway, Buses, LIRR, etc.).  
   - Source: MTA Data Portal.  

- **COVID-19 Cases**:  
   - Statewide COVID-19 testing data for New York.  

These datasets were cleaned, merged, and analyzed to ensure accurate and meaningful visualizations.

---

## Task Analysis  

Our primary goals for the project were as follows:  

1. **Visualize trends in public transportation ridership**:  
   - Show how ridership changed over time during and after the COVID-19 pandemic.  

2. **Explore spatial patterns**:  
   - Highlight subway ridership by station across New York City using a heat map.  

3. **Compare ridership types**:  
   - Use a bar chart to compare ridership recovery percentages for different transportation modes.  

4. **Analyze correlations**:  
   - Explore the relationship between COVID-19 cases and ridership trends using a line chart.  

The interactive features allow users to filter, brush, and explore specific time periods and transportation types.

---

## Conclusion  

This project effectively visualizes the significant impact of the COVID-19 pandemic on public transportation in New York State. By integrating a heat map, a line chart, and a bar chart, we provide a comprehensive, interactive, and user-friendly exploration of ridership trends.  

### Key Insights:  
- Subway ridership declined drastically during the early phases of the pandemic but began to recover over time.  
- Correlations between rising COVID-19 cases and declining public transportation usage were observed.  
- Certain transportation types recovered at different rates compared to pre-COVID levels.  

The project offers meaningful insights for policymakers, urban planners, and transportation agencies to better understand and address changes in public transportation usage.
---

## Acknowledgments  

- **Instructor**: Prof. Dylan Cashman  
- **Tools Used**:  
   - D3.js  
   - Leaflet.js  
- **Data Sources**: MTA Data Portal, New York State COVID-19 Data, Subway Ridership data.  