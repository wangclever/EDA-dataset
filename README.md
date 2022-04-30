Introduction for data in 'Emotional fluctuations under different tourism experiences: An exploratory electrodermal activity analysis'
======

**1. General information**

Through a field study, we captured the EDA signals of eight subjects during a five-days travel. Before analysis, the raw EDA signals should been pre-processed as steps in **Section 3.3.** of paper **'Emotional fluctuations under different tourism experiences: An exploratory electrodermal activity analysis'**. To make it clear for understanding, we present an example of dataset in our research. 

  1.1. Data structure
  
  The dataset is organised with two files: Raw_data.xslx and Analysis_Data.xslx. Each file contains eight Sheets (named by ID) which corresponds to eight subjects.
  
  - 'Raw_data.xlsx': contains raw EDA signals expressed by Empactica E4.
  - 'Analysis_data.xlsx': contains data that obtained after pre-processing. 
  > The pre-process mentioned in Section 3.3. includes following steps:
  > 
  > - Butterworth filter
  > - Normalization
  > - Feature extraction
  
  1.2. Data description
  
  The total records of eight subjects during the whole travel in Raw_data.xslx are 6559931. While after data cleaning and pre-process, there are 8566 valid records in Analysis_data.xslx. 
  
**2. Data format**

  2.1. Raw_data
  
  - 'date': The number of day in the field study (from 1 to 5).
  
  - 'time': Beijing time in milliseconds corresponding to the Unix timestamp expressed by Empatica E4.
  
  - 'experience': tourism experiences which contains attraction attributes and individual activities, in two fields:
  > - Natural experience (attra_type: Natural scenery, Experience with insects & animals).
  > - Social experience (attra_type: Culture experience, Shopping)
  
  - 'attra_type': The types of attractions they belongs to, in four fields:
  > - Natural scenery
  > - Experience with insects & animals
  > - Culture experience
  > - Shopping
  
  - 'attra_name': The names of attractions subjects visited.
  
  - 'weather': Real-time weather conditions during the travel, in two fields:
  
  > - Sunny
  > - Cloudy

  - 'EDA': Raw sensor data from Empatica E4 expressed as microsiemens (μS) in 4Hz, while the initial time of the session expressed as Unix timestamp in UTC.

  - 'ID': The acronym of eight subjects

  2.2. Analysis_data
  
  - 'date': The number of day in the field study (from 1 to 5).
  
  - 'new_time': Recoding time based on the order in which the data was recorded (unit: minute).
  
  - 'experience': tourism experiences which contains attraction attributes and individual activities, in two fields:
  > - Natural experience (attra_type: Natural scenery, Experience with insects & animals).
  > - Social experience (attra_type: Culture experience, Shopping)
  
  - 'attra_type': The types of attractions they belongs to, in four fields:
  > - Natural scenery
  > - Experience with insects & animals
  > - Culture experience
  > - Shopping
  
  - 'attra_name': The names of attractions subjects visited.
  
  - 'weather': Real-time weather conditions during the travel, in two fields:
  
  > - Sunny
  > - Cloudy

  - 'EDA': Raw sensor data from Empatica E4 expressed as microsiemens (μS) in 4Hz, while the initial time of the session expressed as Unix timestamp in UTC.

  - 'ID': The acronym of eight subjects  
