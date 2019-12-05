# STAT8017_Churn_Modelling

Hey people,

just plugged the data into the assignments where it was possible.

In my opinion we can omit the columns Rownumber and Surname, because they aren't interesting to the outcome.
Furthermore I would definitely want a line in the code that says there are no missing values.

I always used Exited as the target variable, but couldn't include Gender and Geography in the models as they weren't made for explanatory string values.
I only turned Gender into the integers 0 and 1 but we should probably have a better solution for that.
If we get a couple models, we could do something like run them over 20 different randomstates and take their mean accuracy so we get the best one.

Suggestions welcome :)
