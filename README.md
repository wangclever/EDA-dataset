Description of example data in paper 'Emotional fluctuations under different tourism experiences: An exploratory electrodermal activity analysis'
======

**1. General information**

Through a field study, we captured EDA signals of eight participants by Empatica E4 during five-days travel. Totally, the raw EDA data records are 6559931. After great efforts of data cleaning, which includes Butterworth filtering, down-sampling, and so on, the final cleaned data set consists of 8566 records. To help the review process, we provide examples of data we used in the paper **'Emotional fluctuations under different tourism experiences: An exploratory electrodermal activity analysis'**. 

**2. Data structure**
 
The data set is organized with two example data: raw data set and cleaned data set. Both are from the same participants and in the same period.

2.1. Raw data set

Which is sampled at 4Hz by Empatica E4.
    
- 'date': The number of days in the field study (from 1 to 5).
    
- 'time': Beijing time in millisecond corresponding to the Unix timestamp expressed by Empatica E4.
    
- 'EDA': Raw sensor data from Empatica E4 is expressed as micro siemens (μS) in 4Hz, while the initial time of the session is expressed as Unix timestamp in UTC.
    
2.2. cleaned data set
    
Which is obtained after data cleaning and merged with manually recorded information corresponding to participants' visiting time. 
    
- 'date': The number of days in the field study (from 1 to 5).
    
- 'new_time': Recoded time based on the order in which the raw data was recorded (unit: minute).
    
- 'experience': Recorded tourism experiences are grouped by attractions and tourists' activities, in two fields:
    
> - Natural experience (includes natural scenery, visiting insects & animals).
> - Social experience (includes culture scenery, shopping).

- 'attra_type': Attraction types, in four fields:

> - Natural scenery.
> - Visiting insects & animals.
> - Culture scenery.
> - Shopping.

- 'attra_name': Records of attraction names that participants visited at different times.

- 'weather': Records of real-time weather conditions during the travel.

- 'emotion': Data from raw EDA signals that have been cleaned and pre-processed.
