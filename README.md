# KNN-Heart-Disease
In statistics, the k-nearest neighbors algorithm is a non-parametric supervised learning method first developed by Evelyn Fix and Joseph Hodges in 1951, and later expanded by Thomas Cover. It is used for classification and regression. In both cases, the input consists of the k closest training examples in a data set.

![image](https://user-images.githubusercontent.com/86295676/179417013-c030ebd3-3225-4e02-b5a1-45803c65c817.png)

## Code
knn = KNeighborsClassifier(n_neighbors = 10)
knn.fit(X_train,y_train)
y_pred1 = knn.predict(X_test)
print(accuracy_score(y_test,y_pred1))
