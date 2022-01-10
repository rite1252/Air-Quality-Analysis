# Air-Quality-Analysis
In This project we have to analyse data on air quality in one of the cities in Italy. We need to determine whether the concentration of air pollutants increase or decrease over time.
# Data Description
The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device.

The device was located on the field in a significantly polluted area, at road level, within an Italian city. Data were recorded from March 2004 to April 2005 (one year) representing the longest freely available recordings of on field-deployed air quality chemical sensor devices responses. A co-located reference certified analyzer provided **Ground Truth (GT)** hourly averaged concentrations for Carbon Monoxide (CO), Non-Methane Hydrocarbons (NMHC), Benzene (C6H6), total Nitrogen Oxides (NO) & Nitrogen Dioxide (NO2), and Ozone (O3). These chemical compounds are commonly occurring air pollutants.

|Index|Columns|Description|
|-|-|-|
|0|Date|Date (DD/MM/YYYY)|
|1|Time|Time (HH.MM.SS)|
|2|CO(GT)|True hourly averaged concentration CO in mg/m3 (reference analyzer)|
|3|PT08.S1(CO)|PT08.S1 (tin oxide) hourly averaged sensor response (nominally (CO) targeted)|
|4|NMHC(GT)|True hourly averaged overall Non-Methane Hydrocarbons concentration in μg/m3 |
|5|C6H6(GT)|True hourly averaged Benzene concentration in μg/m3 |
|6|PT08.S2(NMHC)|PT08.S2 (titania) hourly averaged sensor response (nominally (NMHC) targeted)|
|7|NOx(GT)|True hourly averaged (NO) concentration in Parts per billion (ppb)|
|8|PT08.S3(NOx)|PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally (NOx) targeted)|
|9|NO2(GT) |True hourly averaged (NO2) concentration in μg/m3 |
|10|PT08.S4(NO2)|PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally (NO2) targeted)|
|11|PT08.S5(O3) |PT08.S5 (indium oxide) hourly averaged sensor response (nominally (O3) targeted)|
|12|T|Temperature in Â°C|
|13|RH|Relative Humidity (%)|
|14|AH|AH Absolute Humidity|
