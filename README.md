# California-Housing-ML
Machine learning-projekt på California housing data, med reproducerbart workflow som ger handlingsbara insikter.

Python 3.14

## Arbetsmoment
### Supervised Learning
- EDA
- Feature Engineering
- Train/test Split
- Preprocessing & Pipeline
- Cross Validation
- Hyperparameter tuning & out-of-fold
- Model performance on test data

### Unsupervised Learning
- Principal Component Analysis
    - Scree, Cumulative variance
- KMeans clusters
    - Elbow, Silhouette score
- Model interpretation
    - Feature Importance
- Error analysis
    - Precision/recall trade-off
    - Model's worst mistakes

## Resultat
### Supervised Learning
#### Geografi av huspriserna
![Housing Prices](https://github.com/MaWe96/California-Housing-ML/blob/main/Visualer/Housing_Prices.png)

#### Förvirringsmatris
![Förvirringsmatris (tuned Logistic Regression & OOF)](https://github.com/MaWe96/California-Housing-ML/blob/main/Visualer/F%C3%B6rvirringsmatris_LogReg.png)

#### Mätvärden: Modellens prestation
![Metrics: Logistic Regression](https://github.com/MaWe96/California-Housing-ML/blob/main/Visualer/Logistic_Regression_OOF_Resultat.png)

### Unsupervised Learning: PCA
#### Scree & Explained Variance
![Scree & Explained Var-plot](https://github.com/MaWe96/California-Housing-ML/blob/main/Visualer/Scree_and_ExplainedVar.png)

### Unsupervised Learning: KMeans
#### Elbow Method & Silhouette Score
![Elbow & Silhouette Score](https://github.com/MaWe96/California-Housing-ML/blob/main/Visualer/Elbow_Silhouette.png)

#### KMeans Clusters
![KMeans Clusters](https://github.com/MaWe96/California-Housing-ML/blob/main/Visualer/KMeans_clusters.png)

### Model interpretation & Error analysis
#### Feature Importance
![Feature Importance](https://github.com/MaWe96/California-Housing-ML/blob/main/Visualer/Feature_importance.png)

#### Precision vs. Recall
![Precision vs Recall](https://github.com/MaWe96/California-Housing-ML/blob/main/Visualer/Precision_vs_recall.png)
