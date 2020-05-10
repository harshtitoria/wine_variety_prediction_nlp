# wine_varity_prediction_nlp
Here we use NLP to determine the wine "varity" by analyzing the "review description" feature and creating a "bag of words" model and we use logistic
regression for classification as it works better as a text related classifier.
Also, we do some visualization to find the correlation between different features.

# The Data Description is as follows:
    • user_name - user_name of the reviewer
    • country -The country that the wine is from.
    • review_title - The title of the wine review, which often contains the vintage.
    • review_description - A verbose review of the wine.
    • designation - The vineyard within the winery where the grapes that made the wine are from.
    • points - ratings given by the user. The ratings are between 0 -100.
    • price - The cost for a bottle of the wine
    • province - The province or state that the wine is from.
    • region_1 - The wine-growing area in a province or state (ie Napa).
    • region_2 - Sometimes there are more specific regions specified within a wine-growing area (ie Rutherford inside the Napa Valley), but this value can sometimes be blank.
    • winery - The winery that made the wine
    • variety - The type of grapes used to make the wine. Dependent variable for task 2 of the assignment
