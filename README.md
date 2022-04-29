**General information**

Through the field study, we totally selected EDA signals of eight subjects in a five-days travel. And each of them were asked to wear Empatica E4 during the whole day.

**Data format**

-'unix_time': The intitial time format expressed by Empatica E4.

-'second_time': Beijing time in milliseconds corresponding to the unix timestamp.

-'tourism_experience': tourism experiences which contains attraction attributes and individual activities., in two fields：
                       Natural experience (attraction_type: Natural Scenery, Experience with insects & animals)
                       Social experience (attraction_type: Culture Experience, Shopping)
											 
-'attraction_type': The types of attractions they belongs to, in four fields:
                    Natural Scenery
                    Experience with insects & animals
                    Culture Experience
                    Shopping

-'attraction_name': The names of attractions subjects visited.

-'weather': Real-time weather conditions during the travel, in two fields:
            Sunny
            Cloudy

-'EDA': Raw sensor data from Empatica E4 expressed as microsiemens (μS) in 4Hz, while the initial time of the session  expressed as unix timestamp in UTC.

-'ID': The acronym of eight subjects

-'date': The number of days in the field study (from 1 to 5).
