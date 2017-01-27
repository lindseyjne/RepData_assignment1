R Markdown file for Reproducible Research Week 2
=================================================

First steps is to load the data and look at some basic summary statistics of the data 

Now, I want to look at a **histogram** of the total number of steps taken each day. 
To do this, I need to:

          1. Calculate the sum of the steps taken each day
          2. Create the histogram of the calculated steps

Next, I want to to know what the **mean** and **median** number of steps taken each day and rounded to one digit

I want to view a time series plot of the average number of steps taken per interval.  
To do this, I need to:

                   1. Calculate the mean number of steps per interval
                   2. Create a data frame with the caluclated mean
                   3. Create the plot of the new data frame as a time series plot
                   
Next, I want to find the maximum number of steps taken during a 5-minute interval

This code shows how I dealt with missing data
first step is to calculate the number of missing data values
Next, I need to apply the median for a 5-minute interval and use that number of fill the missing data values. Here are my steps to do this:

        1. Calculate the median number of steps for each interval. 
        2. Create a data frame from the median calculated. 
        3. Merge the created data frame with the original data set. 
        4. Replace the missing values with the calculated median. 


Let's look at a histogram of the total steps taken where the missing data is replaced with the median of the 5-minute interval
To do this, I need to:

          1. Calculate the total steps per each day
          2. create a histogram of this calculation

I want to look at the differences in average number of steps taken per 5-minute interval across weekdays and weekends

      1. Create a variable that labels each oberservation as a weekend or weekday based on the given date
      2. Calculate the mean number of steps per each interval
      3. Load lattice because we want to stack two graphs
      4. Plote the data


