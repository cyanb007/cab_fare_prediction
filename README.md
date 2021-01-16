# ed_projects
Initial projects for the study of data science

Problem Statement :

You are a cab rental start-up company. You have successfully run the pilot project and now want to launch your cab service across the country. You have collected the historical data from your pilot project and now have a requirement to apply analytics for fare prediction. You need to design a system that predicts the fare amount for a cab ride in the city.




Datasets:

We have two datasets.
1. train_cab.csv
2. test.csv

The datasets contain the following features.
Independant Attributes/Features (in both of the datasets) :
    * pickup_datetime - timestamp value indicating when the cab ride started.
    * pickup_longitude - float for longitude coordinate of where the cab ride started.
    * pickup_latitude - float for latitude coordinate of where the cab ride started.
    * dropoff_longitude - float for longitude coordinate of where the cab ride ended.
    * dropoff_latitude - float for latitude coordinate of where the cab ride ended.
    * passenger_count - an integer indicating the number of passengers in the cab ride.
    
    
Dependant Attribute/Feature (only in train_cab.csv) :

* fare_amount - Fare of the cab paid by passengers in their respective rides.

Usage:
Primarily, python 3, Jupyter notebook are needed. 
Datasets and ipython notebook are needed to be placed in the same folder.
To run the ipynb notebook, in the ipynb user need to modify : PATH = "User_defined_path_to_desired_folder"



