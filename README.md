# 911DataAnalysis
Time series prediction of emergency call volumes from different locations of Baltimore city.

911 call log information was used in conjuction with area and demographic information from the US Census Bureau. The aim is to predict future call volumes for each census tract (200 in total). The results will be used with additional data - average response duration per call and the average hours avaiable per personnel on the emergency response team - to build an app that suggests workload demands in different districts of Baltimore (and also compare this with existing workforce strength)

Models explored: Heriarchical time series, Random Forest regression, Geospatial clustering

Demo link: https://docs.google.com/presentation/d/1erfGlp_qPg_SmTZ4vI-geDi_f1bHXMMPZO22qvMtdSo/edit?usp=sharing

App link: https://baltimore-911-streamlit.herokuapp.com/

Data source: https://data.baltimorecity.gov/Public-Safety/911-Police-Calls-for-Service/xviu-ezkt
