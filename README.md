# Titanic-Machine-Learning-from-Disaster:
Binary Classification using Random Forest, Support Vector Machine and Logistics Regression 

Introduction:
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, 
the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the
international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew.
Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others,
such as women, children, and the upper-class.

Overview
The data has been split into two groups:
training set (train.csv)
test set (test.csv)

Data Dictionary
1. Age: Age in years

2. sibsp: # of siblings / spouses aboard the Titanic

3. parch: # of parents / children aboard the Titanic

4. ticket: Ticket number

5. fare: Passenger fare

6. cabin: Cabin number

7. embarked: Port of Embarkation
C = Cherbourg, Q = Queenstown, S = Southampton

Variable Notes
pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

Models used for Classification:
1. Random Forest
2. Support Vector Classifier
3. Logistics Regression

Results:
Both Logistic Regression and Support Vector Classifier performed equally well and better than Random Forest on the given data set. 
