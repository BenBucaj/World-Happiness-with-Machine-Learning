## Description
Using classic machine learning models to understand driving factors of happiness globally

## About the Data: World Happiness Report & the United Nations
The **World Happiness Report** is an annual publication that ranks countries based on happiness metrics derived from **Gallup World Poll** data. It is produced by the **Sustainable Development Solutions Network (SDSN)**, an initiative of the **United Nations**. The report evaluates happiness based on key factors such as:
- **GDP per capita**
- **Social support (family & friends)**
- **Healthy life expectancy**
- **Freedom to make life choices**
- **Generosity**
- **Perceptions of corruption**

This project leverages machine learning models to analyze these factors and extract meaningful insights. By studying these trends, policymakers can develop **data-driven strategies** aligned with the **UN’s Sustainable Development Goals (SDGs)** to improve well-being globally.

#### Project goal
<ul>
  <li>Analyze the World Happiness Report to identify factors driving happiness</li>
  <li>Ultimately, provide actionable insights for policymakers to improve well-being globally</li>
</ul>

## Installations
Check [./prerequisites](https://github.com/FilipLe/World-Happiness/tree/main/prerequisites) for more

## Methodology
### 1. Data Handling ([./data](https://github.com/FilipLe/World-Happiness/tree/main/data) for more)
<ol>
  <li>
    Data Preprocessing
  </li>
  <li>
    Feature Engineering
  </li>
</ol>

### 2. Predictive Methods ([./src](https://github.com/FilipLe/World-Happiness/tree/main/src) for more)
<ol>
  <li>
    Traditional Decision Tree
  </li>
  <li>
    Logistic Regression
  </li>
  <li>
    K-Nearest Neighbors
  </li>
  <li>
    Lasso Regression
  </li>
  <li>
    Random Forest (Ensemble Method)
  </li>  
</ol>

### 3. Nested Cross Validation ([./src](https://github.com/FilipLe/World-Happiness/tree/main/src) for more)

## Source Code
Check [./src](https://github.com/FilipLe/World-Happiness/tree/main/src) for more

## Dataset
Check [./data](https://github.com/FilipLe/World-Happiness/tree/main/data) for more

## Results
For in-depth analysis of the outcome, go to [./src](https://github.com/FilipLe/World-Happiness/tree/main/src) 
```
Average KNN Accuracy: 0.9593889325990034
Average Decision Tree Accuracy: 0.938290060319958
Average Lasso Accuracy: 0.9504656311556591
Average Random Forest Accuracy: 0.9610149488591659
Average Logistic Regression Accuracy: 0.9528979805927091
```
==> Random Forest achieved the highest accuracy, making it the best-performing model.

## Key Takeaways
<ul>
  <li>
    Predictive analysis shows GDP, Family, Health, and Freedom as strong contributors (in that order) to happiness
  </li>
  <li>
    No single factor is sufficient to bring about happiness. In countries with a high happiness ranking, multiple factors (e.g., those listed above) work together in strong combination.
  </li>
</ul>
==> Look at top ranking countries in the Happiness Index and identify policies that relate to the aforementioned predictors

## Implications
### Policy
<ul>
  <li>
    Countries can use happiness metrics as a blueprint for relevant policies that would improving well-being create sustainable development and global well-being
  </li>
</ul>

### Broader Impact
<ul>
  <li>
    <b>Improved Global Stability:</b> Happier nations are often healthier, more productive, and more stable politically and economically.
  </li>
  <li>
    <b>Social Equity:</b> Policies that enhance happiness often reduce inequality, fostering more inclusive societies.
  </li>
  <li>
    <b>Inspiration for Developing Nations:</b> The index serves as a framework for nations striving to improve the quality of life despite economic limitations.
  </li>
</ul>


## Authors
[Ben Bucaj](https://www.linkedin.com/in/ben-bucaj/)
<br>[Nguyen Le](https://www.linkedin.com/in/nguyenle04/)
<br>[Ryan Rodriguez](https://www.linkedin.com/in/ryanrodriguez-/)
<br>[Belen Ramirez](https://www.linkedin.com/in/belenramirezp/)
