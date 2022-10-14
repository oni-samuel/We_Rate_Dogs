# (We_Rate_Dogs)



## Dataset

>The objective of the study was to gather, clean and analyse over 5000+ tweets from a twitter account @dog_rates (WeRateDogs), draw some insights and make a visualization to communicate one of the insights drawn. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.

>We are going through the enetire process of data wrangling:

>- Data gathering

>- Data assessing

>- Data cleaning


### DATA GATHERING:
>In this phase, three datasets were indicated to be necesary for the analysis. One was provided beforehand (twitter_archive_enhanced.csv), and all that was needed to be done was to read it in as a CSV file into a dataframe.

>The second file (image-predictions.tsv), was to be downloaded programmtically using the 'requests' library and then stored into a file. This time though, it was required to specify the delimiter as an argument because tsv files are separated using tabs instead of commas like in a csv file.

>The third file required requesting access to Twitter's API. Unfortunately I wasn't granted access on time to the API so I used another alternative provided by Udacity. This alternative involved downloading an already provided text file (tweet-json.text), and then reading the file line by line into a pandas dataframe.

### DATA ASSESSING

>For this stage, I have to analyze the three datasets both visually and programmatically to point out any possible quality or tidiness issue in the datasets before cleaning them in the next phase. A couple of issues were noted and documented in preparation for the cleaning phase. As with most data set, there were two major types of issues with the dataset, tidiniess and quality issues.


### DATA CLEANING

>This involves tackling the quality and tidiness issues that were noted in the previous phase. The entire datasets were not to be cleaned, a minimum of 8 quality issues and 2 tidiness issues were to be worked on. During the cleaning the datasets, I combined the three into one master dataset (twitter_archive_master.csv) and saved it in preparation for analysis and visualization.

>For insights on analysis and visualization, please refer to the 'act_report.html' file which contains a brief summary of the insights gotten from analysis.