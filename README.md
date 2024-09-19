# Heart-Disease-Data

Select the most accurate Naive bayes model for predicting heart disease and explore the data by creating  data visualizations (box plots, paired plots with distributions and scatter points, and 2 dimensional binning  with seaborn and pandas)

#### Results
The multinomial naive Bayes model was the best; it explained 90% of the variation between having heart disease or not for both the training and test data (indicating there is no overfitting). 
 This model contains only the categorical predictors in the data set.  This agrees with the findings in our exploration with visualizations.  We can see little difference between sleep hours for those with heart disease or not from the box plot. While it appears that those with heart disease tend to have a higher BMI, from our boxplots, it doesn't appear to be extreme.  There is a higher proportion of people between the ages 50-74 that make up those that have heart disease. 


#### Data
Note that this is a clean version (no missing values) and it only contains 18 variables (the original dataset has more than 300 variables). HeartDisease is the response variable. And this is a classification problem.

The `heart2020` dataset is based on the 2020 annual CDC survey data of 400k adults related to their health status.
* `HeartDisease:` Respondents that have ever reported having coronary heart disease (CHD) or myocardial infarction (MI)
* `BMI:` Body Mass Index (BMI)
* `Smoking:` Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes]
* `AlcoholDrinking:` Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week)
* `Stroke:` (Ever told) (you had) a stroke?
* `PhysicalHealth:` Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good? (0-30 days)
* `MentalHealth:` Thinking about your mental health, for how many days during the past 30 days was your mental health not good? (0-30 days)
* `DiffWalking:` Do you have serious difficulty walking or climbing stairs?
* `Sex:` Are you male or female?
* `AgeCategory:` Fourteen-level age category
* `Race:` Imputed race/ethnicity value
* `Diabetic:` (Ever told) (you had) diabetes?
* `PhysicalActivity:` Adults who reported doing physical activity or exercise during the past 30 days other than their regular job
* `GenHealth:` Would you say that in general your health is...
* `SleepTime:` On average, how many hours of sleep do you get in a 24-hour period?
* `Asthma:` (Ever told) (you had) asthma?
* `KidneyDisease:` Not including kidney stones, bladder infection or incontinence, were you ever told you had kidney disease?
* `SkinCancer:` (Ever told) (you had) skin cancer?
