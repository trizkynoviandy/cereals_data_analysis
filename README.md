# Cereals Data Analysis

## Dataset

Dataset source: [Kaggle](https://www.kaggle.com/datasets/crawford/80-cereals)

| Column Name | Description |
|-------------|-------------|
| Name | Name of the cereal |
| mfr | Manufacturer of cereal:<br>A = American Home Food Products;<br>G = General Mills;<br>K = Kelloggs;<br>N = Nabisco;<br>P = Post;<br>Q = Quaker Oats;<br>R = Ralston Purina |
| type | Type of cereal:<br>cold<br>hot |
| calories | Calories per serving |
| protein | Grams of protein per serving |
| fat | Grams of fat per serving |
| sodium | Milligrams of sodium per serving |
| fiber | Grams of dietary fiber per serving |
| carbo | Grams of complex carbohydrates per serving |
| sugars | Grams of sugars per serving |
| potass | Milligrams of potassium per serving |
| vitamins | Vitamins and minerals - 0, 25, or 100, indicating the typical percentage of FDA recommended |
| shelf | Display shelf (1, 2, or 3, counting from the floor) |
| weight | Weight in ounces of one serving |
| cups | Number of cups in one serving |
| rating | A rating of the cereals (Possibly from Consumer Reports?) |

## Data Analysis Process

### 1. Ask

1. *What is the average calorie content of cereals in the dataset?*
2. *Is there a relationship between the sugar content and rating of cereals?*
3. *Which manufacturer produces the most highly rated cereals?*
4. *How to create a machine learning model using this dataset?*

### 2. Prepare

* We have checked the missing values and inconsistencies in this dataset. We also explorer the data and identify the relationship of each variables.

### 3. Process

* We have split the data into train and test set
* We encode the categorical data using Label Encoder
* We scale the data using Standard Scaler

### 4. Analyze

* We build a linear regression model to predict the cereals rating
* The model have good performance, with R2 = 0.92 on the test set

### 5. Share

* The jupyter notebook files contains our findings and insights about this dataset.

### 6. Act

* Manufacturer can used our findings and insight to get information or to take action. Our machine learning model can also be used to predict cereals rating by the variables that can be seen on the dataset.