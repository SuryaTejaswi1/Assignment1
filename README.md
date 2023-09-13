## Big Data with examples and Types:
 Big data means collection of large data which cannot be processed or analysed by traditional data base management systems.
 " It is different from an ordinary data because of
 its high volume, high velocity, and heterogeneous variety."[1]

 ### Examples:
 1. Social media like twiter, instagram, facebook generated huge data in the form of text, images and videos.
 2. Demographic data
 3. Transactional data
 4. Customer created feedback/ reviews texts.
 5. Web data
 6. Healthcare data
 7. Sensor data - as everything is becoming more digitalized(" Smart"), huge amount of data is being generated in indutries and day to day lives.

 ### Types:
 1. Batch data - This is a type of data which is collected over time.
 2. Stream data - This is live or real time data
 3. Spatio temporal - real time, time varying data generated by satellities, GPS data and wireless communication devices.
 "Recent rapid development of wireless communication, mobile computing, global navigational satellite systems (GNSS), and spatially enabled sensors is leading to an exponential growth of available spatio-temporal data produced continuously at high speed."[2]

## 6 ‘V’s of Big Data (define each) 
#### Volume:
Big data itself means enormous amount of data, which cant be handled by traditional systems and requires specialized tools and techniques to process the data. "With regards to Volume, it refers to that the data scale is very large, ranging from several PB (1000TB) to  ZB(a billion TB)"[3]
#### Velocity:
This basically refers to how fast the data is being generated or how fast the data is being processed. For example, the data generated online( through websites/apps) is high speed data.
#### Variety:
With increase in the sources of data, various forms of data is being generated like text, images, videos, graphs, audio. These can be classified as structured(tabular data,relational data), unstructured(text, images, audio, video,logs) and semi-structured data (XML,JSON data, graphs).
#### Value:
This refers to meaningful or usefulness property of data. The data can provide more insights if it has more value. "The signicance of big data is not the  great volume, but rather the huge value. How to extract the  value from massive data through powerful algorithms, is the key to improve competitiveness".[3]
#### Variability: 
This is simply, the inconsistencies in data or how spread out the data is. The data can also be said it is variable if there are so many different types and sources of data.
#### Veracity: 
This refers to the accuracy of data / Trust in data that is being used for analysis. If the data is inaccurate/ incomplete then it will be difficult to obtain insights from it.

<img src = "https://github.com/SuryaTejaswi1/Assignment1/assets/144848077/24165321-6305-494a-a8c5-abf106eda071" width ="400"/>
   
fig: Characteristics of big data, Source : classroom PPT
                                   
## Phases of Big Data analysis (discuss each)
### Data Acquistion: 
As per the business requirements,data can be collected from various sources(sensors, websites, social media, databases). These sources may generate data in a variety of formats, such as structured (relational databases, Excel files), semi-structured (JSON, XML), and unstructured (text, photos, and videos). The primary challenge in data acquisition is the need to filter the collected data, which involves the removal of unwanted information. Unwanted data can take the form of duplicates, irrelevant information, or noise. It is of utmost importance to use the appropriate set of filters, as incorrect filtering could result in the loss of valuable data.
### Data Cleaning:
The first step is to convert the filtered data into a structured format. Afterward, the process of data cleaning involves keeping the essential information while removing incorrect or noisy data."Data cleansing offers a better data quality which will be a great help for the organization to make sure their data is ready for the analyzing phase. However, the amount of data collected by the organizations has been increasing every year, which is making most of the existing methods no longer suitable for big data. Data cleansing process mainly consists of identifying the errors, detecting the errors and corrects them."[4] 
### Data Aggregation & Representation:
"Data aggregation refers to the process by which raw data are gathered, reformatted, and presented in a summary form for subsequent data sharing and further analyses."[5]
In today's world, data aggregation poses a challenge due to the diversity of data sources.For example, if one source may have collected data over time and another one source may have actively generating data. In these scenarios, time definitely cannot be the aggregative function and to have some common factor to merge/aggregate these datas will be more difficult.
Data Representation refers to the different ways in which the same data can be visually presented. This includes various visualization techniques such as bar charts, histograms, box plots, and pie charts.
### Data Analysis:
The steps involved in data analysis for big data differs when compared to traditional data sets. In the smaller data sets by using querying for example, using SQL we can obtain information. But, this is not in the case of big data as the data is more complex."Big Data is noisy, dynamic, heterogeneous, inter-related and untrustworthy. But even noisy Big Data can be valuable, as reliable hidden patterns and knowledge can be disclosed. It also avoid from overpower individual fluctuations and other small sampling biases."[6]
### Interpretation:
This phase is where we understand what the results of our analysis are. Visualizing the data can be a big help in making it easier to understand and share but, it's more than just showing the data through visualisations. When interpreting data, we don't just describe what the data shows, we should also think about what it might mean for the business.With the information like where the data came from, how we got each result, and what specific information we used, we can more valuable insights from the data. 

## Challenges in Big Data analysis (discuss each)
### Heterogeneity and Incompleteness:
### Scale:
### Timeliness:
### Privacy:
### Human Collaboration:

## References:
1. M. M. Rathore, S. A. Shah, D. Shukla, E. Bentafat and S. Bakiras, "The Role of AI, 
   Machine Learning, and Big Data in Digital Twinning: A Systematic Literature Review, 
   Challenges, and Opportunities," in IEEE Access, vol. 9, pp.32030-32052, 2021, 
   doi:10.1109/ACCESS.2021.3060863.
2. Galić, Z. (2016). Spatio-Temporal Data Streams and Big Data Paradigm. In: Spatio-Temporal Data Streams.
   SpringerBriefs in Computer Science. Springer, New York, NY. https://doi.org/10.1007/978-1-4939-6575-5_3
3. Q. Qi and F. Tao, "Digital Twin and Big Data Towards Smart Manufacturing and Industry 
   4.0: 360 Degree Comparison," in IEEE Access, vol. 6, pp. 3585-3593, 2018,
   doi: 10.1109/ACCESS.2018.2793265.
4. Ridzuan, F., & Zainon, W. M. N. W. (2019). A review on data cleansing methods for big data. Procedia Computer Science, 161, 731–738. https://doi.org/10.1016/j.procs.2019.11.177
5. Wen, T. (2020). Data Aggregation. In: Schintler, L., McNeely, C. (eds) Encyclopedia of Big Data. Springer, Cham. https://doi.org/10.1007/978-3-319-32001-4_296-1
6. Zhao, C. (n.d.). Five Phases in the Big Data Processing Pipeline (notes). www.linkedin.com. https://www.linkedin.com/pulse/five-phases-big-data-processing-pipeline-notes-christiane-zhao/
7. Indicative Analytics. (2021, September 15). What is data variability? Data defined - indicative. Indicative. https://www.indicative.com/resource/data-variability/
8. GeeksforGeeks. (2021). Big Data Analytics life cycle. GeeksforGeeks. https://www.geeksforgeeks.org/big-data-analytics-life-cycle/

 
