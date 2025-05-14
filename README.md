# US Domestic Airline Flights Performance Dashboard

## Overview

This interactive web-based dashboard, built using Dash and Plotly, visualizes U.S. domestic airline data between 2005 and 2020. It enables users to generate detailed performance and delay reports based on selected years and report types. The dashboard is designed for data exploration, allowing insights into various metrics such as flight cancellations, delays, diversions, and traffic by state or airline.

## Features

- 📈 **Yearly Airline Performance Report**
  - Monthly flight cancellations by category
  - Average monthly flight time by reporting airline
  - Percentage of diverted landings by airline
  - Choropleth map of flights originating from each state
  - Treemap of flights arriving in each state per airline

- 🕒 **Yearly Airline Delay Report**
  - Monthly average delay times by airline due to:
    - Carrier-related delays
    - Weather conditions
    - NAS (National Aviation System) delays
    - Security issues
    - Late aircraft

## Technologies Used

- **Dash** – Python framework for building web apps
- **Plotly** – Graphing library for interactive visualizations
- **Pandas** – Data manipulation and analysis
- **HTML/CSS** – Layout and styling

## Installation & Run

1. Clone the repository or download the script.
2. Install dependencies:
   ```bash
   pip install dash pandas plotly
