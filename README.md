# Data-pipeline
This project provides a fully integrated data pipeline workflow using Python. It is designed to handle Excel or CSV datasets, including large retail or business datasets, and perform the following tasks: 
Data Loading:  Load Excel or CSV files into pandas DataFrames.  Supports large datasets with multiple rows and columns.  
Data Cleaning & Preprocessing:Remove duplicate rows.Remove negative numeric values.Reset index for clean data ordering.Handle missing values (numeric = mean, categorical = mode).
Basic & Advanced Analysis:Basic descriptive statistics (describe()).Optional advanced analysis using Random Forest Classifier for predictive modeling.
Data Visualization:Generate histograms for numeric columns.Save visualizations as PNG files.Optional interactive visualizations via Streamlit dashboard.
Real-Time Data Simulation:Demonstrates streaming of first few rows with delay, useful for live dashboards or monitoring systems.
Export & Reporting:Export data summary to Excel (summary.xlsx).Export summary to PowerPoint (summary.pptx).Apply formatting to highlight high values in Excel.Optionally export cleaned dataset for Power BI integration.
Automation & Logging:Automatic logging of key pipeline steps (pipeline.log).Open exported reports automatically.
Optional Streamlit Dashboard:Interactive dashboard to preview data and visualize numeric distributions.
Technologies & Libraries Used:
Python: pandas, numpy, matplotlib, scikit-learn, openpyxl, python-pptx, streamlit
