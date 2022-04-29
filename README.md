**General information**
Through the field study, we totally selected EDA signals of eight subjects in a five-days travel. And each of them were asked to wear Empatica E4 during the whole day.

**Data format**
-'second_time': Beijing time in milliseconds corresponding to initial unix timestamp recorded by Empatica E4.

-'weather': Real-time weather conditions during the travel, in two fields:
                 Sunny
                 Cloudy

-'attraction_name': The names of attractions subjects visited.

-'attraction_type': The types of attractions they belongs to, in four fields:
                            Natural Scenery
                            Experience with insects & animals
                            Culture Experience
                            Shopping

-'tourism_experience': tourism experiences which contains attraction attributes and individual activities., in two fields：
                                  Natural experience (attraction_type: Natural Scenery, Experience with insects & animals)
                                  Social experience (attraction_type: Culture Experience, Shopping)

-'EDA': Raw sensor data from Empatica E4 expressed as microsiemens (μS) in 4Hz, while the initial time of the session expressed as unix timestamp in UTC.

-'ID': The acronym of eight subjects
