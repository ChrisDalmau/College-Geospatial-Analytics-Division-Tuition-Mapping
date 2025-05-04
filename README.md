# College-Geospatial-Analytics-Division-Tuition-Mapping
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

Division I schools are more concentrated in the South, especially in states like Texas, Georgia, and Florida.

Division III schools are more prevalent in the North, aligning with denser clusters of private liberal arts colleges.

Higher out-of-state tuition tends to concentrate on the coasts, particularly the Northeast and West Coast.

