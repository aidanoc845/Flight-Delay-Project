# Analyzing Global Air Travel Patterns and Delays Using Flight Data
Project Description: 
This project analyzes air travel delay patterns using the U.S. Department of Transportation On-Time Performance dataset and OpenSky Network flight data.
It identifies the most delay-prone carriers and airports, examines seasonal trends, and uses machine learning models to predict delay likelihood.
The provided Python scripts support data processing, summarization, and visualization for this analysis.
Python Files
1. ot_flight_finder.py
Loads and filters U.S. DOT flight delay data.
Extracts relevant carrier, airport, and date-based delay statistics.
Prepares data for visualizations (bar/line charts, heatmaps, maps).
2. ot_summaries.py
Aggregates cleaned flight data by carrier, airport, and month.
Generates summary tables for percentage of delays and total delay minutes.
Computes seasonal trends for predictive modeling.
Research Questions & Answers
Which airlines contribute most to delays?
Envoy Air, JetBlue, and Frontier had the highest percentage of delays; American Airlines had the highest total delay minutes.
Which airports have the most delays?
Newark (EWR), Chicago Midway (MDW), and Dallas Love Field (DAL) were top delay-prone airports.
Are delays seasonal?
Yes. Peaks occur in July, January, and December, correlating with holiday travel and summer demand.
Can we predict delays using available data?
Yes. A Random Forest classifier achieved 81.2% accuracy in predicting whether a flight would be delayed.
