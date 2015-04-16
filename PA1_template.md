# Reproducible Research: Peer Assessment 1
Sam Edgemon  
April 16, 2015  


## Loading and preprocessing the data

setwd("~/GitHub/RepData_PeerAssessment1")
data <- read.table(unz("activity.zip", "activity.csv"), header=T, quote="\"", sep=",")

# convert date to date data type
data$date <- as.Date(data$date) 




## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
