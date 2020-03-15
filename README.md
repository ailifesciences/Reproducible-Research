# Reproducible-Research
The files in this repo are:
1. A R markdown file of the data analysis. (PA1_template.rmd)
2. The data itself. (activity.csv)
3. A html file corresponding to the rmd file. (PA1_template.html)
4. Plots in the document.



# Introduction
It is now possible to collect a large amount of data about personal movement using activity monitoring devices such as a Fitbit, Nike Fuelband, or Jawbone Up. These type of devices are part of the “quantified self” movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. But these data remain under-utilized both because the raw data are hard to obtain and there is a lack of statistical methods and software for processing and interpreting the data.

This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and include the number of steps taken in 5 minute intervals each day.

# Variables of the activity monitoring data are given by:

* steps: number of steps taken in a 5-minute interval (missing values are denoted NA)
* date: date on which the measurement was taken in yyyy-mm-dd format.
* interval: identifier for the five minute intervals.

The data is stored in a comma separated CSV file with 17568 rows.

# Assignment
Show the following codes and results:

1. Loading the data and preprocessing.
2. Loading data using read.csv().
3. Processing the data into a format fit for analysis.
4. What is the mean total number of steps taken per day?
a. (Ignoring NA values) calculate the total number of steps taken per day.
b. Make a histogram of the total number of steps taken per day.
5. Compute the mean and median of the total steps per day.
6. What is the average daily activity pattern?
a. Make a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, average across all days (y-axis).
b. Which 5-minute interval, on average across all the days in the dataset, contains the maximum number of steps?
7. Imputing missing values. Presence of NA days may introduce bias into some calculations or summaries of the data.
a. Calculate and report the total number of mising values in the data set (total number of rows in NA).
b. Devise a strategy for filling in all of the missing values in the data set. Example, the mean or median for the day could be used or the mean for the five minute interval.
c. Create a new dataset that is equal to the original dataset with the missing NA values filled in.
d. Make a histogram of the total number of steps taken each day, Calculate and report the median and mean total number of steps per day. How do these values compare to the cases where NA values were simply ignored? What is the impact of imputing missing data on the estimates of the total daily number of steps taken?
9. Are there differences in activity patterns between weekdays and weekends? weekdays() function might be useful for this part. Use the data set with the filled in missing values.
a. Create a new factor variable in the dataset with the two levels - "weekdays" and "weekend".
b. Make a panel plot containing the time series plot (i.e. type = "l") of the five-minute interval and the average number of steps taken averaged across all weeday days and weekend days (y-axis).
