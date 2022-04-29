Introduction
====

**General information**

Through the field study, we totally selected EDA signals of eight subjects in a five-days travel. And each of them were asked to wear Empatica E4 during the whole day.
The number of records for each subjects are shown in the following table. There are totally 6559931 raw EDA data. 

| date  | CWS    | GQ     | MDL    | MDX    | MSY    | MYY    | WHY    | YQJ    |
|-------|--------|--------|--------|--------|--------|--------|--------|--------|
| 1     | 182332 | 171659 | 172373 | 172589 | 172396 | 148150 | 172757 | 80219  |
| 2     | 178535 | 178289 | 178535 | 178757 | 178733 | 177341 | 178373 | 177827 |
| 3     | 145373 | 144929 | 145403 | 142907 | 144929 | 145391 | 145031 | 145037 |
| 4     | 72689  | 169265 | 179207 | 179711 | 169283 | 172595 | 169799 | 169295 |
| 5     | 176609 | 171491 | 171827 | 188471 | 175091 | 173201 | 188405 | 175127 |
| total | 755538 | 835633 | 847345 | 862435 | 840432 | 816678 | 854365 | 747505 |

**Data format**

- 'unix_time': The intitial time format expressed by Empatica E4.

- 'second_time': Beijing time in milliseconds corresponding to the unix timestamp.

- 'tourism_experience':  tourism experiences which contains attraction attributes and individual activities., in two fields:<br/>
        1. Natural experience (attraction_type: Natural Scenery, Experience with insects & animals)<br/>
        2. Social experience (attraction_type: Culture Experience, Shopping)
											 
- 'attraction_type': The types of attractions they belongs to, in four fields:<br/>
        1. Natural Scenery<br/>
        2. Experience with insects & animals<br/>
        3. Culture Experience<br/>
        4. Shopping

- 'attraction_name': The names of attractions subjects visited.

- 'weather': Real-time weather conditions during the travel, in two fields:<br/>
        1. Sunny<br/>
        2. Cloudy

- 'EDA': Raw sensor data from Empatica E4 expressed as microsiemens (μS) in 4Hz, while the initial time of the session  expressed as unix timestamp in UTC.

- 'ID': The acronym of eight subjects

- 'date': The number of days in the field study (from 1 to 5).
