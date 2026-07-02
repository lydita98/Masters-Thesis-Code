# Masters-Thesis-Code
Code for my thesis project is provided: "Explainable Forecasting of Terrorism Incidents: A SHAP-based Analysis on the Global Terrorism Database"
- the five different feature configurations for the model are all in seperate Juypter Documents, all with an "x" as the first letter. Other Scripts without an "x" can be ignored
- access and download the Global Terrorism Database via the following link: https://www.start.umd.edu/download-global-terrorism-database
- convert the Excel file into a csv file and name it "globalterrorismdb_0522dist_csv.csv"
- access the Quality of Government Database via the following link: https://www.gu.se/en/quality-government/qog-data/data-downloads/standard-dataset and download the time-series csv-file
- both files "qog_std_ts_jan26.csv" and "globalterrorismdb_0522dist_csv.csv" must be in the same folder as the Jupyter files
- (Databases are too big to upload in GitHub)
- "x GTD-only, 9 Features, EDA.ipynb" -> Code for baseline model, feature configuration of 9 features + EDA
- "x GTD-only, 15 Features.ipynb" -> Code for model with feature configuration of 15 features
- "x GTD-only, 18 Features.ipynb" -> Code for model with feature configuration of 18 features
- "x GTD extended by QoG, 32 Features.ipynb" -> Code for GTD merged with QoG data, feature configuration of 32 features
- "x GTD extended by QoG, 40 Features.ipynb" -> Code for GTD merged with QoG data, feature configuration of 40 features
