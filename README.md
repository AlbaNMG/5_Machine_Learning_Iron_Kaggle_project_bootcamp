<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Project: Machine Learning - Iron Kaggle

## Overview

The dataset can be found here.

The objective is to predict the revenue of shops. Each row of our data contains the following information:

shop_ID : Shop's unique identifier.
day_of_the_week : Encoded from 0 to 6.
date : day, month and year of the data point.
number of customers : Quantity of customers that showed up that day.
open : Binary variable equal to 0 if shop closed that day and 1 if shop open.
promotion : Binary variable equal to 0 if shop had no promotions that day and 1 if it did.
state_holiday : Encoded 0, a, b, c indicating if there was a state holiday at all (0 if not), and otherwise, the number indicates which state holiday it was.
school_holiday : Binary variable equal to 0 if there was a school holiday that day and 1 if not.
At 16:00 a validation file will be uploaded here (see here for template - the validation file will be much larger). Your submission is due at 16:30 and should consist of an output file with just the index and sales prediction for the row (see here for template), as well as a pickled version of your model, a requirements.txt file and any feature engineering steps you may have used (preferably pickled as well).

We must be able to run your model and generate predictions in our computers, so we strongly advise you to try to emulate in a clean environment what we would do and see if you are delivering all necessary artifacts.

The scoring metric will be R2.
