# Feature-Selection

<h3>-VarianceThreshold</h3><br>
<!--   sklearn.feature_selection.VarianceThreshold< -->
  Feature selector that removes all low-variance features. <br>
  This feature selection algorithm looks only at the features (X), not the desired outputs (y), and can thus be used for unsupervised learning.<br>

<h3>-Chi-Squared statistical test (SelectKBest)</h3><br>
  Chi2 is a measure of dependency between two variables.<br>
  It gives us a goodness of fit measure because it measures how well an observed distribution of a particular feature fits with the distribution that is expected if two         features are independent.<br>
  Scikit-Learn offers a feature selection estimator named SelectKBest which select K numbers of features based on the statistical analysis.<br>
