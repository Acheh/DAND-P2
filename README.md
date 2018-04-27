# Introduction

The purpose of this project is to perform analysis on a dataset containing demographic and passenger information of the RMS Titanic and to find likely factors that affect passenger's chance of survival aboard the sinking ship. More information regarding the dataset can be found at https://www.kaggle.com/c/titanic.

# Questions To Explore
- did a female passenger have a better chance of survival than a male passenger?
- did socio-economic status of a passenger count as a factor on the passenger's survival rate?
- did traveling alone (without family member: parents, spouse, children, and/or siblings) give a passenger a better chance at surviving?
- did children (18 year-old or younger) have a better chance of survival?

# Process
Data wrangling and data cleaning were both performed on the original dataset to remove duplicate entries, extract variables of interest, create new variable from combination of available variables, and handle incorrect or missing values. 

Data exploration and visualization were both performed to answer questions about the dataset. Chi-square analysis was performed on the socio-economic status versus survival outcome to determine its dependency. Another Chi-square analysis was performed on the travel buddy status of the passenger against survival outcome to determine its dependency.

# Limitation
- data set is only a sample - contains records of only 891 out of 2224 passengers and crews aboard the Titanic, and contains 177 missing age values. Sample size and missing value can skew the result of analysis in this report.
- data sampling method is unknown at this point. A bias sampling selection violate the assumption of simple random sampling used in chi-squre tests rendering invalid results.

# Future Research
- there are few other variables that are not considered in this report, such as cabin location, fare, and port of embarkation, which are worthy of detailed analysis in order to give us a better insight about the Titanic survivors and victims.
- acquisition of complete datasest would bring more interesting discoveries, such as the comparison between passengers and crew, and would give true perspective about Titanic survivors and victims.
- confirming the simple random sampling method will strengthen the conclusion of this report.

# Resources
- http://seaborn.pydata.org/tutorial/categorical.html
- http://stackoverflow.com/questions/24789671/change-the-title-of-factor-plot-in-seaborn
- http://www.secnetix.de/olli/Python/lambda_functions.hawk
- http://www.history.com/topics/titanic
- http://www.titanicfacts.net/titanic-survivors.html
- https://www.encyclopedia-titanica.org/titanic-survivors/
- http://www.stat.cmu.edu/~rnugent/PCMI2016/papers/ViolinPlots.pdf
