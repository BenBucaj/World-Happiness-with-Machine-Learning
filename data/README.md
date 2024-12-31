## Source
Kaggle, World Happiness Report: https://www.kaggle.com/datasets/unsdsn/world-happiness/data


## Preprocessing
For full code for preprocessing, find the below subheadings in the [notebook](https://github.com/FilipLe/World-Happiness/blob/main/src/Happiness_Project.ipynb)
##### 1. Combining Datasets 
==> 5 .csv files for each year into 1 big DataFrame
##### 2. Dropping Redundant + Duplicate Values
==> Creates a list of unique country names from the 'Country' column of df by converting it to a set (removes duplicates).
<br>==> Sorts the unique countries alphabetically using sorted().
##### 3. Handling Missing Values
==> If all the regions are missing, the code removes the rows for that country completely from the DataFrame.
<br>==> If any region is present, it replaces the missing (NaN) regions with the first valid region found for that country and adds the updated region information to the new_regions list.
##### 4. Defining Classes for Training
==> Create a binary target variable that distinguishes high-ranking (top 20 = (1)) from lower-ranking countries (non-top 20 = (0))

##### 5. Shuffle dataset to prevent weird training

## Feature Engineering
Since existing features after cleaning the raw data were good enough, there was no need to create new features, but just to adjust existing ones to enhance the model's performance.
### Scaling Data
```
from sklearn.preprocessing import MinMaxScaler
scaler = MinMaxScaler()
scaled_data = scaler.fit_transform(df)
```
### Dealing with Skew Distribution
```
df.skew()
```

## Train-Test Split
Split data into training (80%) and test (20%)
```
n = len(df)
percent = int(0.8 * n)
features = df.columns
```
Slice up to 0.8 of dataset for training
```
x = df[list(features)][:percent]
y = output[:percent
```
Slice from 0.8 of dataset onwards to testing
```
x_test = df[list(features)][percent:]
y_test = output[percent:]
```
