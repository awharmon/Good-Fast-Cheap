# Good-Fast-Cheap

For this project, my teammates and I were broken up into 3 teams and given 3 hours to create the best model possible.  This is playing to the old addage "Good, Fast, and Cheap -- Pick Two".

We competed to create the best model with our given constraints.  I was on "Team Sample Constraint" which meant we had to use the cheap training sample dataset.

---

### Team Sample Constraint
- Your choice of algorithm
- Your choice of features
- **Must use the cheap train sample**

### Team Features Constraint
- Your choice of algorithm
- **Limited to a maximum of 20 features**
- Your choice of samples

### Team Algorithm Constraint
- **Must use a Random Forest**
- Your choice of features
- Your choice of samples

Descriptions of the data can be found [here](http://archive.ics.uci.edu/ml/machine-learning-databases/adult/old.adult.names) and [here](http://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.names).
 
---

## Results

As it turns out, my team was able to create the best model using a Support Vector Machine (SVM) prediction.  We ended up with ~94% classification accuracy on the unseen test set (via a Kaggle competition), and we were ~2% ahead of the Feature Constraint team who were able to use PCA to cheat the 20 feature limitations.