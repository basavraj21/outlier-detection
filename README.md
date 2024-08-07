outlier detection in Cyclone Inlet Gas Temp and Cyclone Outlet Gas temp, using the db-scan clustering algorithm  

#DBScan Clustering
To find the number of outliers I decided to apply DBScan Clustering.
DBScan is a clustering-based machine learning technique for detecting fraud, outliers, and anomalies.
It takes as input multidimensional data and groups it based on the model's parameters, such as epsilon and minimum samples. 
The programme decides whether or not specific values in the dataset are outliers based on these factors.



From DBScan Clustering, we find that in our Dataset, we have around 2720 Outliers.
The Cyclone Inlet Gas Temp and Cyclone Outlet Gas temp, the outliers lie in the middle range of Temperatures,
In the Cyclone Material Temp, much outliers are in the higher temperature ranges, while few are in lower region. In the Cyclone Inlet and Outlet Gas Draft,
the outliers lie in the higher pressure ranges, and in the Cyclone Cone Draft, the outliers mostly lie in the lower pressure ranges.
