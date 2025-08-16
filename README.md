# Analyzing Global Air Travel Patterns and Delays Using Flight Data
Project Description: 
This project analyzes air travel delay patterns using the U.S. Department of Transportation On-Time Performance dataset.
It identifies the most delay-prone carriers and airports, examines seasonal trends, and uses an interactive model to determine delay likelihood for specified parameters.
The provided Python scripts support data processing, summarization, and the interactive model for this analysis.
Python Files
1. ot_flight_finder.py:
Reads raw DOT data into a dataframe using pandas.
It then cleans and groups the data in preperation for the interactive widget.
Finally it runs the widget with the proper datafram.
2. ot_summaries.py:
Reads raw DOT data into a dataframe using pandas.
Cleans and dates the data properly.
Sepereates data into summaries for each of the respective visualizations.
3. Flight-Delay-Data folder:
Stores the row data and processed data from the summaries file.

Research Questions & Answers:
Which airlines contribute most to delays?
Envoy Air, JetBlue, and Frontier had the highest percentage of delays; American Airlines had the highest total delay minutes.
Which airports have the most delays?
Newark (EWR), Chicago Midway (MDW), and Dallas Love Field (DAL) were top delay-prone airports.
Are delays seasonal?
Yes. Peaks occur in July, January, and December, correlating with holiday travel and summer demand.

Final Report: https://docs.google.com/document/d/12THeETg5ocJd8KmjF-7wHQ-1D7jnVFdxqU3Kf-BV54k/edit?usp=sharing

Video Presentation: https://www.canva.com/design/DAGwMChu_as/g0Y3W0QPG8ojCVaVkLmNlg/view?utm_content=DAGwMChu_as&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h92a8e3d95d
