# Project 6 Grading Guidelines

You can find details about the grading process [here](../p1/grading-guidelines.md). 

### Part 1 (10 points): 
* Hardcoding, **-10**
    * e.g., displaying empty plot 
* Setting up train & test sets (4 points)
    * If didn't add all land use feature, **-2**
    * If didn't split train & test sets, **-1**
* Building model (2 points)
    * If didn’t use all land use columns as feature columns or didn't use `POP100` as label column, **-1**
    * If didn't use train set to fit the model, **-1**
* Barplot (2 points)
    * If wrong shape, **-2**
    * If no x, y labels or x ticks for each feature, **-1**
* Interpretation (2 points)
    * If incorrect interpretation, **-2**

### Part 2 (15 points): 
* Hardcoding, **-15**
    * e.g., displaying any number larger than 0.35
* Building models (4 points)
    * If didn't use `POP100` as label column, **-1**
    * If didn't use train set to fit the model, **-1**
    * If the two models are not different, **-2**
* Evaluating models (5 points)
    * If use test set to compute cross validation scores, **-1**
    * For each model: 
        * If mean of cross validation scores is missing, **-1**
        * If variance of cross validation scores is missing, **-1**
* Recommendation (3 points)
    * If wrong recommendation, **-3**
    * If the reasoning is insufficient, **-1**
* Evaluating recommended model (3 points)
    * If didn't use test set to compute score, **-1**

