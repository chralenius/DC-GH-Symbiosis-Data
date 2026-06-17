# Data center-to-greenhouse symbiosis-data
This process data contains measurement reading for a data center-to-greenhouse energy symbiosis, used for research purposes.

Authors
Christoffer Alenius (a*), Andrea Toffolo (a), Mattias Vesterlund (ab) Mikael Risberg (a)
*Corresponding Author: christoffer.alenius@ltu.se
a Energy Engineering, Department of Engineering Sciences and Mathematics, Luleå University of Technology, SE-97187 Luleå, Sweden
b ICE Data Center, RISE Research Institutes of Sweden AB, 973 47 Luleå, Sweden
________________________________________
Data Collection Period
•	Start date: 7 Dec 2023
•	End date: 11 May 2023
Location and Company
•	Boden, Sweden
•	Data Center Systems, RISE Research Institutes of Sweden AB
Methods
Data were recorded using an open-source management infrastructure comprising Kairos, Zabbix, Kafka, and Grafana. The data were collected via a data center edge node installed in the greenhouse and subsequently mirrored and archived for long-term storage at the ICE Data Center.
________________________________________
Dataset Contents
\DC_GH_symbiosis_data/
├── data_set
├── flow.csv
├── humidity.csv
├── power.csv
├──setpoints.csv
└── temperatures.csv
├── DC.PNG
├── GH.PNG
└──Sensorlist_DC-GH.xlsx

File Inventory
Filename	              Description
data_set	              Folder containing raw data
DC.PNG	                Image with name of data center process units
GH.PNG	                Image with name of greenhouse process units
Sensorlist_DC-GH.xlsx 	Sensor list of names of sensors and their measured quantities in the data center and greenhouse
flow.csv	              Flows through the individual fans (m3/h or liters/s)
humidity.csv 	          Relative humidity in the ventilation, greenhouse, data center (%)
power.csv 	            Power supply to the greenhouses artificial lighting (W)
setpoints. csv	        Setpoints for the greenhouse supply fan, greenhouse air temperature, and the damper settings to the DC and ambient (%).
temperatures. csv	      Temperatures in and out of the data center, the temperatures in the greenhouse and the ambient temperature (°C)
