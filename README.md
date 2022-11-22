# Neural_Network_Charity_Analysis
This analysis was done to help Alphabet Soup get a better idea of which applicants would be successful if their ideas and projects were accepted for funding by Alphabet Soup's Charity Foundation. Using data from 34,000+ previous applicants, I built a predicting model with over 70% accuracy.

## Results
- The IS_SUCCESSFUL Variable in the table was used as the dependent variable
- The Feature Variables were all other variables in the table other than EIN and NAME.
- More variables could have been removed.
- I removed Use_Case as a feature and added 10 nodes to both layer1 and layer to improve the accuracy. It actually went down, so I reversed that.
- I was unable to achieve 75%.

## Summary
The results provide Alphabet Soup's Charity a tool that will give them roughly 70% accuracy on project success. Increasing the number of params could probably increase accuracy. More bucketing and dropping one or two other columns may increase the accuracy as well.
