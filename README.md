# 2017/2018 ACT & SAT Data

## Overview
In this project, I was gifted some data in four files, and tasked with deriving insights from it, and conducting additional research as needed if I found anything that stood out. (Surprise: I did.)

## Data
    - act_2017.csv (contained 2017 state averages for the ACT)
    - act_2018.csv (contained 2018 state averages for the ACT)
    - sat_2017.csv (contained 2017 state averages for the ACT)
    - sat_2018.csv (contained 2018 state averages for the ACT)
    - final.csv (final dataset that contained the above four data files combined neatly, and cleaned)

## Data Dictionary

|Column|Type|ACT/SAT|Description|
|---|---|---|---|
|**state**|*object*|ACT/SAT|The name of the state that contains the row of data with it| 
|**sat_participation_[year]**|*float*|SAT|Participation rate of SAT with custom year (percentage)|
|**act_participation_[year]**|*float*|ACT|Participation rate of SAT with custom year (percentage)|
|**sat_total_[year]**|*int*|SAT|Total score of the SAT by state in a given year|
|**act_composite_[year]**|*float*|ACT|Total score of the ACT by state in a given year|
|**sat_[subject]_[year]**|*int*|SAT|Score in a SAT test subject in a given year. State average|
|**act_[subject]_[year]**|*float*|ACT|Score in a ACT test subject in a given year. State average|

## Methodology
    1) Data from the CSVs had to be loaded and cleaned
    2) This involved removing some extra characters, cross checking against the source data (some values were incorrect), and then converting numerical values to float that weren't already float/int
    3) Following cleaning all files were combined into one large, albeit succinct data file + dataframe (for delving deeper)
    4) After that, a myriad of charts and graphs were made to look into the data to try to identify trends


## Insights
    1) Participation rates for SATS increased from 2017 to 2018 nationwide
    2) Resultant from this caused SAT related scores to drop slightly, and cause for a broader range of scores. (Expected from more of the general populace taking the test, whether good, bad, or great as a test taker
    3) States that had SAT test taking mandated by law as a gradation requirement saw strongest participation rate increases (external factor)
    4) ACT overall participation rates remained mostly unchanged year-to-year

## Conclusion/Recommendation
Strongest recommendation is for any spokesperson, whether for ACT or SAT: If you want your participation rate to surge in a target state, the strongest factor appears to be having the state mandate the test as a high school graduation requirement

## Presentation Slides:
https://docs.google.com/presentation/d/1tDAN0mGBizdcHwssnxnbhw8qMnOlGn8noV9Qfuxzclk/edit?usp=sharing



```python

```
