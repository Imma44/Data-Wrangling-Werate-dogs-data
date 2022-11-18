# Data-Wrangling
Introduction
Real-world data rarely comes clean. Using Python and its libraries,we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling.

The dataset that we will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

Step 1:Gather
In this step,we will obtain data from three sources

The WeRateDogs Twitter archive which has been provided to us which contains basic tweet data for all 5000+ of their tweets
The tweet image predictions that contains image predictions that classify dog breeds
Additional data from the Twitter API that contains retweet count and favorite count

Step 2:Assess Data
When assessing, you're inspecting your data set for two things:

Data quality issues:

Completeness: do we have all of the records that we should? Do we have missing records or not? Are there specific rows, columns, or cells missing?

Validity: we have the records, but they're not valid, i.e., they don't conform to a defined schema. A schema is a defined set of rules for data. These rules can be real-world constraints (e.g. negative height is impossible) and table-specific constraints (e.g. unique key constraints in tables).

Accuracy: inaccurate data is wrong data that is valid. It adheres to the defined schema, but it is still incorrect.

Consistency: inconsistent data is both valid and accurate, but there are multiple correct ways of referring to the same thing. Consistency, i.e., a standard format, in columns that represent the same data across tables and/or within tables is desired.

Lack of tidiness: Data that has specific structural issues that slow you down when cleaning and analyzing, visualizing, or modeling your data later.
Each variable forms a column
Each variable forms a row
Each type of observational unit forms a table
We will perform this using Visual & Programmatic methods

Step 3:Cleaning Data
In this step we are are going to

Define
Code
Test

Step 4:Storing Data


Step 5: Analyzing and Visualizing Data
