# Machine Learning Homework - Exoplanet Exploration

* model_1.ipynb

**SVC - Kernel: rbf
**Data Score before GridSearchCV
***Training Data Score: 0.991955756661639
***Test Data Score: 0.9856711915535445
**GridSearchCV Parameters
***C: [1, 5, 10, 50] - 5 is the best
***gamma: [0.0001, 0.0005, 0.001, 0.005] - 0.005 is the best
**Best Training Data Score after GridSearchCV: 991957586675516
**Classification Report
    |                 | precision | recall | f1-score | support |
    |-----------------|-----------|--------|----------|---------|
    |      CONFIRMED  |      1.00 |   0.96 |     0.98 |     451 |
    | FALSE POSITIVE  |      0.98 |   1.00 |     0.99 |     875 |
    |       accuracy  |           |        |     0.99 |    1326 |
    |      macro avg  |      0.99 |   0.98 |     0.98 |    1326 |
    |   weighted avg  |      0.99 |   0.99 |     0.99 |    1326 |
