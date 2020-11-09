# Machine Learning Homework - Exoplanet Exploration

* Comparison Table among the models used
    |      filename |                  model |      Score bef. GridSearchCV |  Score aft. GridSearchCV | accuracy |
    |---------------|------------------------|------------------------------|--------------------------|----------|
    | model_1.ipynb |   SVC(kernel='rbf')    | Training: 0.991955756661639  |       0.991957586675516  |     0.99 |
    |               |                        |     Test: 0.9856711915535445 |                          |          |
    | model_2.ipynb |   SVC(kernel='linear') | Training: 0.991955756661639  |       0.991957586675516  |     0.99 |
    |               |                        |     Test: 0.9856711915535445 |                          |          |
    | model_3.ipynb | RandomForestClassifier | Training: 1.0                |       0.9904487848045257 |     0.98 |
    |               |                        |     Test: 0.9834087481146304 |                          |          |
    | model_4.ipynb |     LogisticRegression | Training: 0.991955756661639  |       0.991957586675516  |     0.99 |
    |               |                        |     Test: 0.9856711915535445 |                          |          |
    | model_5.ipynb | DecisionTreeClassifier | Training: 1.0                |       0.9869302487279163 |     0.98 |
    |               |                        |     Test: 0.9811463046757164 |                          |          |
    | model_6.ipynb |   KNeighborsClassifier | Training: 0.993              |                          |          |
    |               |                        |     Test: 0.986              |                          |          |

* Result
  * Both the SVC models and the LogisticRegression model are the best among the models I tested.
  * I used Logistic Regression to predict which planets are not false planets because most columns have coefficients when I use the model.

* Files
  * joonil_kim.sav: trained model save file
  * predicted_candidates.csv: Predicted candidates
