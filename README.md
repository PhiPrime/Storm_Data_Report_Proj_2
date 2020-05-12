# Storm_Data_Report_Proj_2

##Introduction
This project involves exploring the U.S. National Oceanic and Atmospheric Administration's (NOAA) storm database. This database tracks characteristics of major storms and weather events in the United States, including when and where they occur, as well as estimates of any fatalities, injuries, and property damage. This project is the second project for the reproducible research course on Coursera (https://www.coursera.org/learn/reproducible-research/home/welcome)

An example of an analysis by Peng can be **[found on RPubs](https://www.rpubs.com/rdpeng/13396)**  
##Data

The data for this assignment come in the form of a comma-separated-value file compressed via the bzip2 algorithm to reduce its size. You can download the file here:  

* **[Storm Data](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2) [47Mb]

There is also some documentation of the database available, where you will find how some of the variables are constructed/defined:  
* **[National Weather Service Storm Data Documentation](./References/repdata_peer2_doc_pd01016005curr.pdf)**  
* **[National Climatic Data Center Storm Events FAQ](./References/repdata_peer2_doc_NCDC_Storm_Events-FAQ_Page.pdf)**  

The events in the database start in the year 1950 and end in November 2011. In the earlier years of the database there are generally fewer events recorded, most likely due to a lack of good records. More recent years should be considered more complete.  

## Criteria  
1) Create a valid RPubs URL pointing to a data analysis document for this assignment  
2) The analysis include description and justification for any data transformations?  
3) The document has a title that briefly summarizes the data analysis  
4) The document has a synopsis that describes and summarizes the data analysis in less than 10 sentences  
5) There is a section titled "Data Processing" that describes how the data were loaded into R and processed for analysis  
6) There is a section titled "Results" where the main results are presented  
7) There is at least one figure in the document that contains a plot  
8) There are at most 3 figures in this document  
9) The analysis starts from the raw data file (i.e. the original .csv.bz2 file)  
10) The analysis addresses which types of events are most harmful to population health  
11) The analysis addresses the question of which types of events have the greatest economic consequences  
12) All the results of the analysis (i.e. figures, tables, numerical summaries) are reproducible  
13) The figure(s) have descriptive captions (i.e. there is a description near the figure of what is happening in the figure)  

## Assignment  
The basic goal of this assignment is to explore the NOAA Storm Database and answer some basic questions about severe weather events. The database must be used to answer the questions below and the code is to be shown for the entire analysis. The analysis can consist of tables, figures, or other summaries. Any R package can be used to support the analysis.  

## Questions  
1) Across the United States, which types of events (as indicated in the `EVTYPE` variable) are most harmful with respect to population health?  
2) Across the United States, which types of events have the greatest economic consequences?  

Consider writing your report as if it were to be read by a government or municipal manager who might be responsible for preparing for severe weather events and will need to prioritize resources for different types of events. However, there is no need to make any specific recommendations in your report.



