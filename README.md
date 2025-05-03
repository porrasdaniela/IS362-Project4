# IS362 – Project 4: Predictive Analysis Using scikit-learn  
Daniela Porras-Lo  
IS 362 


## Project Overview  
This project builds predictive models to determine which mushroom attributes are the best predictors of whether a mushroom is edible or poisonous. The dataset is sourced from the UCI Machine Learning Repository (Agaricus-lepiota dataset).

I focus on two categorical features:
- `odor`
- `gill_color`

The goal is to compare the predictive accuracy of each feature using logistic regression.

## Tools Used  
- Python  
- pandas  
- scikit-learn  
- Jupyter Notebook  

## Steps Performed  
1. Loaded and cleaned the mushroom dataset  
2. Selected relevant features and target variable (`is_poisonous`)  
3. Applied one-hot encoding to categorical predictors  
4. Built and evaluated logistic regression models  
5. Compared model performance using accuracy  
6. Stated final conclusions based on findings

## Key Results  
- `odor` alone achieved **98.40% accuracy**
- `gill_color` alone achieved **80.19% accuracy**
- Combining both resulted in **98.77% accuracy**

## Conclusion  
Odor is a highly reliable feature for predicting mushroom toxicity. While gill color adds slight improvement when combined, it is not as effective alone. Future work could explore adding more features such as bruises, cap shape, or spore print color.

## Files  
- `IS362_Project4.ipynb`: Jupyter Notebook with all code and analysis  
- `agaricus-lepiota.data`: Original dataset used in the analysis  
