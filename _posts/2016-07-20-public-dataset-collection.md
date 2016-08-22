---
layout: post
category : resources
tagline: "public energy dataset"
tags : [dataset, public]
---
{% include JB/setup %}

---------------------------

Updated @ 2016-08-22

#### UCI: ElectricityLoadDiagrams20112014 Data Set 

[Dataset Resource Site](https://archive.ics.uci.edu/ml/datasets/ElectricityLoadDiagrams20112014#)

**Introduction**

This data set contains electricity consumption of 370 points/clients. Data set has no missing values. Values are in kW of each 15 min. To convert values in kWh values must be divided by 4. 
Each column represent one client. Some clients were created after 2011. In these cases consumption were considered zero. 

All time labels report to Portuguese hour. However all days present 96 measures (24*15). Every year in March time change day (which has only 23 hours) the values between 1:00 am and 2:00 am are zero for all points. Every year in October time change day (which has 25 hours) the values between 1:00 am and 2:00 am aggregate the consumption of two hours. 

**Relevant Publications**

- Analysis Clustering of Electricity Usage Profile Using K-Means Algorithm
	- *Yasirli Amri, Amanda Lailatul Fadhilah, Fatmawati, Novi Setiani and Septia Rani, Materials Science and Engineering, 2016*

---------------------------

Updated @ 2016-07-20

#### UK-DALE: UK Domestic Appliance-Level Electricity Dataset

[Dataset Resource Site](http://www.doc.ic.ac.uk/~dk3810/data)

**Introduction**

This dataset records the power demand from five houses. In each house the data contributor records both the whole-house mains power demand every six seconds as well as power demand from individual appliances every six seconds. In three of the six houses, the whole-house voltage and current are also recorded at 16 kHz and every second.

This dataset will be updated as more data is recorded. Each release of the dataset is labelled with the month and year. The most recent release is for May 2016. UK-DALE now includes 3.5 years of data for house 1.

*Remarks*: the introduction above is from the data site and please refer it for more details.

**Relevant Publications**

- The UK-DALE dataset, domestic appliance-level electricity demand and whole-house demand from five UK homes
	- *Jack Kelly and William Knottenbelt. Scientific Data 2, 2015*
- Smart Meter Disaggregation: Data Collection & Analysis
	- *Jack Kelly & William Knottenbelt. Poster 2013*