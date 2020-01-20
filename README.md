# Argo Sensor Analysis

Argo is a global array of more than 3,800 free-drifting profiling floats that measures the temperature and salinity of the upper 2,000 meters of the ocean. All data is publicly available. http://www.argo.ucsd.edu/

I wrote the parsing script "Single_CSV_API_Argovis_get_data_region.py" to scrape Argo data utilizing a .pkl file. From this dataset (~ 5 GB), I created a Amazon RDS through PostgreSQL and uploaded the data through the "Argo_RDS.ipynb" file. This project was then passed on to another group that worked on spectral clustering and data visualization. 
