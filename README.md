# Getting-and-Cleaning-Data-Project

Overview
The steps need were taken to transform the initial data set:
1-	The test and train sets have been merged
2-	The subject identifiers and activity labels were pulled in to create a single data set. 
3-	The activity identifiers were translated from identifiers into human-readable names.(Only the mean and standard deviation variables were kept). 
4-	The resulted variables were further summarized by taking their mean for each subject/activity pair.(The data is in "wide" format as described by Wickham; there is a single row for each subject/activity pair, and a single column for each measurement).
5-	The final data set can be read into R with  read.table("tidyMeans.txt", header = TRUE) . 
6-	The basic naming convention is : Mean{timeOrFreq}{measurement}{meanOrStd}{XYZ}
A detailed description of the variables can be found in CodeBook.md.
