# Random Forest Classification Lab

**Aim:** Build a Random Forest Classifier on the Insurance dataset and compare different `max_depth` and `n_estimators` using Accuracy, Precision and Recall.

Target `high_charges`: 1 = charges above median, 0 = at/below median.

## How to run
1. Place **insurance.csv** in this folder (dataset not included).
2. `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
3. `jupyter notebook Lab_Random_Forest_Classification.ipynb` and run all cells.

## Conclusion
- Accuracy ≈ 0.93 across settings; best was depth 8 / 10 trees (0.9366).
- Deeper trees add flexibility but can overfit; more trees make the forest more stable but cost more compute.
- Final model (100 trees, depth 6): Accuracy 0.9328, Precision 0.9677, Recall 0.8955.
