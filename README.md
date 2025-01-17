# Bikeshare-data-analysis
Data Analysis on Us Bike Share Data. This project contains three csv file as datasets. They are _chicago.csv_, _new_york_city.csv_ and _washington.csv_. In this project is about accepting these datasets and analysing the data.

## Installation:
This project need 2 major libraries **NumPy** & **Pandas**

* Enter `conda install numpy`
* Enter `conda install pandas`

## The datasets:
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

* _Start Time_ (e.g., 2017-01-01 00:07:57)
* _End Time_ (e.g., 2017-01-01 00:20:53)
* _Trip Duration_ (in seconds - e.g., 776)
* _Start Station_ (e.g., Broadway & Barry Ave)
* _End Station_ (e.g., Sedgwick St & North Ave)
* _User Type_ (Subscriber or Customer)

The _Chicago_ and _New York City_ files also have the following two columns:

* _Gender_
* _Birth Year_

## Usage:
#### Input:

* In this project, the three datasheets are in puts files in which data is sorted according to the requirements.
* These has an interactive interface in which user have the choice of choosing city whose data is to be sorted.
* Once, required city data is chosen the user can choose the how the data can be sorted. i.e. the user is given three choices which are     sort by month, day or nether.
    
#### Output:
The data is accepted and sorted according to the user’s specifications.
Once, required data is sorted out the data is analysed and sorted accordingly. i.e. 
    
* Popular travel time.
     * Most common month.
     * Most common day of the week.
     * Most common hour of the day.
              
* Popular station and trip.
     * Most common start station
     * Most common end station
     * Most common trip (i.e. most frequent combination start station and end station)
              
* Travel duration 
     * Total travel time 
     * Average travel time
     
* User Information
     * Count of each user type
     * Count for each gender for _New York_ and _Chicago_ 
     * Oldest customer and recent customer for _New York_ and _Chicago_
     * Most common year of birth for _New York_ and _Chicago_
     
## More Information 
* Stack Overflow
* Udacity Python Foundation Nanodegree Program
* GitHub

 
