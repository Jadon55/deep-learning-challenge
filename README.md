# deep-learning-challenge
Data Science Bootcamp - Module 21 Challenge

## Overview
The purpous of this analysis is to predict if a fundrasing campain would be successful

## Results
Target: IS_SUCCESSFUL
<br>
Features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
<br>
Columns not used: EIN,	NAME
<br><br>

The orignal model used 2 hidden layers and got a overall accuracy of 72.86%.
<br>
The optomized model used 5 hidden layers and despite hiting 75% in training, still only managed a overall accuracy of 72.94%
<br>
The target accuracy of 75% wasn't reached in the optomized model, and using keras_tuner also failed to meet the requirement
