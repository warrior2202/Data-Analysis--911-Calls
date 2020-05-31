# Exploratory Data Analysis of 911 calls

In this project, I am going to analyze some 911 call data available in [Kaggle](https://www.kaggle.com/mchirico/montcoalert). 

### Software and libraries required:

  * Python 3
  * Jupyter Notebook
  * Numpy
  * Pandas
  * Matplotlib
  * Seaborn

 > Alternatively, you can install [Anaconda](https://www.anaconda.com/download/) which comes preinstalled with all the above software and libraries.

### Data:

The dataset contains the following features:

  + lat : String variable, Latitude
  + lng: String variable, Longitude
  + desc: String variable, Description of the Emergency Call
  + zip: String variable, Zipcode
  + title: String variable, Title
  + timeStamp: String variable, YYYY-MM-DD HH:MM:SS
  + twp: String variable, Township
  + addr: String variable, Address
  + e: String variable, Dummy variable (always 1)

### Analysis Done:

  - Top 5 zipcodes for 911 calls.
  - Most common reason for 911 calls? - Emergency Medical Sevices
  - Number of calls on each weekday for different reasons.
  - Number of calls in each weekday for different reasons.
  - Heatmap of calls on each weekday and each month.
    
     ![alt text](https://github.com/VamsiMohanRamineedi/Exploratory_Data_Analysis_911_Calls_Data/blob/master/Images/HeatMap.PNG 'Most calls between 4 p.m. to 6 p.m.')

  - Clustering calls by hour, day and month

     ![alt text](https://github.com/VamsiMohanRamineedi/Exploratory_Data_Analysis_911_Calls_Data/blob/master/Images/ClusterMap.PNG)










