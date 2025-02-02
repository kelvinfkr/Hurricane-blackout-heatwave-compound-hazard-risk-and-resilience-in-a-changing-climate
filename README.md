# Hurricane-blackout-heatwave-compound-hazard-risk-and-resilience-in-a-changing-climate

This is the data set for paper "Hurricane-blackout-heatwave compound hazard risk and resilience in a changing climate" submitted to PNAS (2020).
Authors are "Kairui Feng, Ouyang Min, and Ning Lin"
from "Civil and Environmental Engineering, Princeton University andSchool of Artificial Intelligence and Automation, Huazhong University of Science and Technology"

License(s) 	
Open Data Commons Attribution
Creative Commons Attribution Share Alike
GNU General Public License 

Date: 06/22/2020

For those who use this data set should follow the copy right regulation of both PANS and designsafe.

The data set contains the data for 6 figures in the paper.

Fig 1 contains modelled and real observed power outage for hurricane Harvey and Ike.
The Modelled data set contains error bar, which should be added to the median number to get the correct power outage range.
The Day column means the number of days post-hurricane and is one-to-one connected to the power outage columns.

Fig 2a is the post-hurricane heatwave lasting probability curve under historical and future climate.  It contains the "Days" information and the probability for a heatwave to happen post hurricane after some time.

Fig 2b is the relative climate risk (multiply). This is not directly divide the median numbers in Fig 2, but resample hurricanes for different climates and get one relative risk every simulation. The number would be different from directly divide the median number. 

Fig 3a,b,c,d are 99 quantiles for post-hurricane power outage rate under historical/future climate and post-hurricane compound hazard rate under historical/future climate. It contians a day post-hurricane and a rate corresponding to that. It is ranked from the most insiginificant cases to the most severe cases from 1 to 99.

Fig 4 contains the data to use in GIS systems. Every census tract has a State/County/Tract number and one expected power outage rate under historical and future climate and compound hazard rate  historical and future climate. 

Fig 5a are 97 cases selected for scaling analysis. Because the total failures for pole are different case by case, the columns are not with the same length. So this table should be read vertically with one P number (x-data) corresponding to one W number (y-data). Due to the file is too large, half of the cases is submitted in a separate xls file.

Fig 5b is the average branch length of each census tract versus average outage number under histrocial climate.

Fig 6 is the result for different retorfitting methods. It is the retrofitting rate versus compound hazard rate. Enhancement rate with three strategies are represented in different colors: randomly undergrounding power transmis- sion network (green), randomly undergrounding power distribution network (red), and greedily undergrounding power distribution network (blue).
