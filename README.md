This is my Capstoe Project for DATA 205 at Montgomery College 


**Project Overview**

For my Capstone Project I set out to conclude whether our nation's capital can truly be considered a “disabled-friendly city” by analyzing DC’s public transportation and infrastructure. My main way of determining how accessible the city is for the disabled community was by collecting and cross examining the city’s ADA (American with Disabilities Act) public transportation and infrastructure data (bus stops, curb ramps, crosswalks, metro stations and sidewalks) with DC’s disabled population data. All of the data I gathered was collected directly from opendata.dc.gov. The differences I found between the DC’s eight wards were staggering beyond what I ever expected, showing that there are variations. 


**Answered Project Questions**

- Is ADA  infrastructure evenly distributed across all wards? If not, what are the disabilities?
- What is the most common type of disability? Does this reflect the most common type of accessibility assistance? 
- What's the median distance from a metro stop and bus stop for a disabled person?
- Which type of infrastructure is the least compliant? Which is the best?
- Is there noticeable overlap in infrastructure quality in certain regions, ie curb ramps, sidewalks and crosswalks are all subpar
- What type of barriers/hazards obstruct sidewalk mobility?
- Are there any economic correlations? If so what are they?


**Tools**

The tools I utilized during this project were QGIS, R studio, and Jupyter Notebook. I used R studio for exploratory and statistical analysis, as well as to create the more basic visualizations for my project. Jupyter Notebook was used for higher quality visualizations, such as the comparison between the wards. Finally, the main tool I used was QGIS, specifically for all mapping and joining, as well as the statistical analysis for distancing.  


**Datasets**

- The first repository is the collection of all the datasets implemented in this project. In case you would like to replicate any of the code if conducted, the datasets are ordered from project by repository use. 
- The datasets falling under Mapping Datasets are identical to the standard dataset listed previously, they have just been converted to geoJson for easier mapping usage.

**EDA & Graphs** 
Before diving into mapping, I conducted Exploratory Data Analysis (EDA) in R Studio to understand the distributions, check for missing values, and identify initial patterns across DC’s eight wards. The goal was simple: let the data speak before I forced it onto a map.

Key EDA Findings:

- Population Disparity: Ward 3 has the highest concentration of disabled residents (approx. 18.2% of its population), while Ward 6 has the lowest (approx. 9.5%). This immediately raised a red flag, given Ward 3’s reputation for wealth and historical underinvestment in curb ramps.
- Most Common Disability: Across all wards, mobility-related disabilities (ambulatory difficulties) are the most reported (approx. 38% of disabled respondents). The second most common is cognitive disability (22%). Interestingly, the most widely available ADA infrastructure targets mobility (ramps, level boarding, tactile pavers), leaving a potential gap for those with sensory or cognitive needs.
- Least Compliant Infrastructure: Sidewalks. By a wide margin. Nearly 14% of DC’s sidewalks have at least one documented barrier or hazard—with missing segments, extreme cracking, and overgrown vegetation being the top three culprits. The most compliant? Metro stations (96% of surveyed stations met or exceeded ADA boarding requirements).
- Median Distance for Disabled Residents:
To a bus stop: 138 meters (less than a 2-minute walk for most)
To a Metro stop: 1,420 meters (approx. a 17-minute walk)
Interpretation: Buses are the true accessibility backbone. If you cannot walk long distances, rail is functionally less accessible.
- Correlation Check (Economic):
Yes—and it’s uncomfortable. Wards with higher median household incomes (Ward 3, Ward 2) had fewer ADA-compliant curb ramps per capita but higher-quality sidewalks. Lower-income wards (Ward 7, Ward 8) had more ramps (likely due to recent grant funding) but worse sidewalk continuity. This suggests reactive rather than proactive investment.

**Mapping**

Following the Exploratory Analysis Repositories will be my mapping section. The map file will contain the various types of maps I made for my project. Directly below that repository will be the Word Document explaining the step by step process to recreate each map in QGIS.

**Research**

To get a better understanding of my project I conducted research as to why I’m seeing certain trends. These websites were not used for my analysis but to help provide context and overall better understanding. My research notes and links to source material can be found in the Word Document under the research Repository 

**Limitations**

- I didn’t have exact locations for specific disabilities due to CDC guidelines that prohibit including too much trackable information for safety concerns 
- Unable to join most datasets together, restricting certain analysis options 
- Technical Difficulties, my main laptop was dysfunctional for almost 2 weeks—limiting my mapping capabilities

**Acknowledgements**
I would like to thank my colleagues for providing feed back that was critical to my Project, friends and family who painstakingly listened to my ideas and frustrations, and finally professor Perine for continuous guidance from start to finish on my Capstone Project.
