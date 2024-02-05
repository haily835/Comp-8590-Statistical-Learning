
Conceptual - Exercise 3

I collect a set of data (n = 100 observations) containing a single predictor and a quantitative response. I then fit a linear regression
model to the data, as well as a separate cubic regression, i.e. $Y = \beta_0 + \beta_{1} X + \beta_{2}X^2 + \beta_{3}X^3 + \epsilon$

(a)

The training RSS of the cubic regression will be **lower** than that of the linear regression. This is because the cubic regression has higher degree and will fit the curve tightly to training data points better than a straight line.

(b)

On test set, however the RSS of linear regression will be lower than the cubic regression. The linear regression is more generalized and approximately capture the true linear relationship that existing.

Although cubic regression would perform well on the training data, it tends to memorize the training sample without actually learn the true relationship which will cause the problem of overfitting. As a result the RSS of cubic regression on test set is larger than linear regression.

(c)

If the true relationship is not linear, the cubic function will still have lower RSS on training set than linear regression. In case of non-linear relationship, the more flexible model - the cubic regression is more likely to provide better prediction for the sample.

(d)

It is **not enough information** to compare the RSS of linear and cubic regression. This is because the true relationships is not linear but we do not know whether how far it is from linear. We do not know how much of flexibility should be better for this dataset.

If the true relationship is not too far from linear, let say just a slightly curvy straight line, then the RSS of linear regression on test set will be smaller.

If the true relationship is far from linear, high chances are the cubic regression will perform better with lower RSS on test set.
