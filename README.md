# Aim
Perform data preprocessing method then explore and analyse Big Data using R and Unix Shell

# Questions
- Part A
  1. Decompress the file. How big is it?
  2. Whatdelimiterisusedtoseparatethecolumnsinthefileandhowmany columns are there?
  3. The first column is a unique identifier for a Tweet. What are the other columns?
    
  4. How many Tweets are there in the file?
  5. What is the date range for Tweets in this file?
  6. How many unique users are there? [Hint: It could take 5 minutes to sort such a big list, so be patient!]1
  7. When was the first mention in the file of “Donald Trump” and what was the tweet?
  8. DoyouthinkwehavecapturedallthereferencestoDonald?Whatother strings might we need to try? What problems might we face?
  
- Part B: Graphing the Data in R
  1. How many times does the term ‘Obama’ appear in tweets?
  2. You will need to write a format string, starting with “%a %b“ to tell the function how to parse the particular date/time format in your file. What format string do you need to use?
  3. Onceyou’veconvertedthetimestamps,usethehist()functiontoplotthe data. 
  4. The plot has a bit of an unusual shape. Can you see a pattern before Feb 15 and what happens after that?
  5. Basedonthehistogramin(3),chooseonedate/daythathasthehighest mention of Obama. Plot another histogram for this date/day, to show the frequency for every hour for that date/day. Can you deduce anything from observing the histogram?
1 If you don’t want to be patient, redirect the output of the command to a file and run the command “in the background” by typing an ampersand character "&" at the end.
  6. Plot a second histogram, but this time showing the distribution over number of tweets per author in the file.

# What I Learned
- Able to manipulate big data using Unix Shell (Deduce, extract, convert, and read big data file for analysis)
- Able to perform k-means clustering

