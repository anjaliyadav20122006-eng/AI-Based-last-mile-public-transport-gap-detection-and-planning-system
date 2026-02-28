# AI-Based-last-mile-public-transport-gap-detection-and-planning-system
"Analyzes Mumbai transport accessibility using demographic/geospatial data. Identifies underserved wards, classifies service levels, and recommends new transport stop locations. Features interactive dashboards for simulating impacts, predicting stress scores, and assessing disruptions, plus real-time weather monitoring."

Smart Transport AI Dashboard
Data Preparation: Loaded and cleaned various transport and demographic datasets, integrating geographical coordinates for wards.

Accessibility Analysis: Calculated the nearest public transport stop for each ward and classified their service levels (Excellent, Good, Moderate, Poor).

Visualization: Mapped service levels on an interactive Folium map to visually identify underserved areas.

Advanced Analysis: Applied K-Means clustering to group wards by population and accessibility, refining these into 'High', 'Medium', and 'Low Service' clusters.

Performed correlation analysis and used the Elbow Method for optimal clustering.

Recommendations: Identified 'Low Service' clusters and calculated an optimal new transport stop location, which was then added to a map.

Impact Modeling: Developed a 'stress score' (population x distance) and trained a Linear Regression model to predict it, enabling quantitative assessment of accessibility challenges.

Interactive Dashboards (Gradio): Created several interactive tools:

New Stop Placement: Simulate adding new transport stops and see the impact on service levels.

Stress Score Prediction: Dynamically predict ward stress scores based on various inputs.

Disruption Simulation: Model how events like traffic affect service levels.

Weather App: Provides real-time weather conditions for wards.

All dashboards are accessible via a central Gradio Portal.
This project effectively combines data science, geospatial analysis, and interactive visualization to provide a comprehensive tool for improving Mumbai's urban transport planning.
