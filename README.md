# College-Geospatial-Analytics-Division-Tuition-Mapping
## Download and view in google colab to see the plotly interactive visualizations

This project explores the relationship between U.S. colleges' location, athletic division, and tuition costs using geospatial visualization. The goal was to identify regional patterns and insights across over 1,180 U.S. institutions with athletic programs.
📊 Project Features

Enriches college location data by geocoding city/state into latitude & longitude.

Interactive visualizations using Plotly to map:

Division I, II, III schools across the country.

Out-of-state tuition distribution.

Extracted insights on how region correlates with division level and tuition range.

📁 Dataset Overview

The dataset includes:

name: College name

school_website: Official athletic site

division: NCAA Division I, II, or III

conference: Athletic conference

location: City and state

tuition_in_state, tuition_out_of_state: Annual tuition costs

gpa: Average accepted GPA

enrollment: Number of enrolled students

Data sourced internally for academic and non-commercial research purposes.

🔧 Tools & Libraries

Python, Pandas

Plotly Express, Seaborn, Matplotlib

Geopy (for geocoding)

TQDM (for progress bars)

📌 Key Insights

Division III schools are more concentrated in the North, reflecting the presence of smaller liberal arts institutions.

Division I schools dominate in the South, often reflecting greater athletic emphasis.

High out-of-state tuition values cluster around the coasts, especially in the Northeast and California.

