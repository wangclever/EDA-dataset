Data description for the paper 'Emotional fluctuations under different tourism experiences: An exploratory electrodermal activity analysis'
======

**1. General information**

Through a field study, we captured the EDA signals of eight participants by Empatica E4 during a five-day trip. Totally, the raw EDA data records are 6559931. After great efforts of data cleaning, Butterworth filtering, normalization, and feature extraction, the final cleaned data set consists of 8566 records. To help the review process, we provide the data structures and samples of our raw data set and cleaned data as follows. 

**2. Data structure**

The samples of raw data set and cleaned data set are both from the same participant and in the same period.

2.1. Raw data set
    
- 'date': Date numbers in the field study (from 1 to 5).
    
- 'time': Time in milliseconds (Chinese Standard Time).
    
- 'EDA': Raw sensor data expressed as micro siemens (μS) in 4Hz.
    
2.2. Cleaned data set

The cleaned data set contains manual records such as experience, and attra_types. 
    
- 'date': Date numbers in the field study (from 1 to 5).
    
- 'new_time': Recoded time in minutes.
    
- 'experience': Tourism experiences grouped by tourism attractions and tourists' activities, in two values:
    
> - Natural experience (includes natural scenery, visiting insects & animals)
> - Social experience (includes culture scenery, shopping)

- 'attra_type': Tourism attraction types, in four values:

> - Natural scenery
> - Visiting insects & animals
> - Culture scenery
> - Shopping

- 'attra_name': Tourism attraction names that participants visited at different times.

- 'weather': Real-time weather conditions during the travel.

- 'emotion': Computed EDA data after data pre-processing.
