## Datasets

This folder contains datasets used for the piracy risk analysis project.

- https://www.kaggle.com/datasets/n0n5ense/global-maritime-pirate-attacks-19932020/data

Context

Maritime piracy and armed robbery against ship are one of the contemporary challenges of the maritime industry. These two phenomena have a global impact on maritime trade and security.
Nowadays, the Gulf of Aden and the Indian Ocean are considered high risk areas in terms of piracy and armed robbery against ships activities. In this regard, both the international community and the coastal States of the region have deployed every effort to try to find ways to address the problem.

Content

This dataset contains information from more than 7,500 maritime pirate attacks that took place between January 1993 and December 2020, as well as country indicator data for the same time period. The pirate attack data was collected from the International Maritime Bureau (IMB), tidied, and augmented with geospatial data. The country indicator data was gathered from a variety of sources, notably The World Bank. The data is contained in Comma Separated Value (CSV) files.

pirate_attacks.csv

Date [Key] - Date of Attack. Used as a key with the Country Matrix data frame.
Time - Time the attack took place, either in UTC or Local Time.
Longitude - Longitude where the attack took place.
Latitude - Latitude where the attack took place.
Attack Type - Either NA (Missing), Attempted, Boarding, or Hijacked.
Location Description - A text description of the location. With attacks taking place at sea, it is not as simple as just naming a city or town.
Nearest Country [Key] - The country code whose shore is closest to the attack. The resolution is around 1 km, it can be much better depending on how detailed the mapping of the coast is in the vicinity.
EEZ Country [Key] - The Exclusive Economic Zone country code in which the attack took place, if it took place within an EEZ.
Shore Distance - Distance in kilometres to the shore from the attack location. This is the true geographic distance over the surface of the earth.
Shore Longitude - The longitude of the closest point on the shore to the attack.
Shore Latitude - The latitude of the closest point on the shore to the attack.
Attack Description - The text description of the attack if it exists.
Vessel Name - The name of the ship which was attacked if it is known.
Vessel Type - The type of vessel attacked if known.
Vessel Status - The status of the ship at the time it was attacked. Either NA (Missing), Berthed (Tied to a berth), Anchored (anchored at sea or in a harbour), or Steaming (ship underway).

